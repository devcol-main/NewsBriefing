# NewsBriefing

DevCol(Development Collaboration) 브랜드의 주식·시장 뉴스 브리핑 자동화 프로젝트다.
오너: Master. 모든 최종 결정권은 오너에게 있다.
2026-09-27 `devcol-main/AIAutomationSampling` 의 `stock-news/` 에서 분리했다 (git 기록 유지). 2026-09-28 저장소 이름을 `news-briefing` → `NewsBriefing` 으로 변경.

## 목표
매일 아침 관심 종목과 시장 주요 뉴스를 요약한 브리핑을 만든다. (평일 일일 브리핑, 토 주간 요약, 일 다음 주 미리보기)
주 실행은 claude.ai 클라우드 루틴 "stock-news 아침 브리핑 (cloud)" — 매일 07:30 KST, 절차는 `briefing-prompt.md`.

## 파일
- `briefing-prompt.md` 루틴이 따르는 절차·규칙 (요일별 모드)
- `watchlist.md` 관심 종목·섹터 (오너가 관리)
- `sources.md` 데이터 소스와 우선순위
- `templates/` 모드별 양식: `briefing.md`, `weekly-recap.md`, `week-ahead.md`
- `briefings/YYYY-MM-DD-NewsBriefing.md` 브리핑 결과물 (평일·주말 모두 같은 규칙, 샘플은 `-NewsBriefing-sample.md`)
- `docs/confirm-protocol.md` 오너 컨펌 형식, `docs/notify.md` Slack 알림
- `PLAN.md` 계획, `STATUS.md` 진행 상황 (한 줄 요약 + 다음 할 일)

## 작업 방식
1. 큰 요청은 `pm` 에이전트가 먼저 계획(태스크, 담당, 완료 기준)을 `PLAN.md` 에 만든다.
2. 계획은 오너 컨펌 후 실행한다. (`docs/confirm-protocol.md`)
3. 실행은 `developer`, `researcher` 가 맡고, `reviewer` 가 완료 기준으로 검수한 뒤 오너에게 컨펌 요청한다.
4. 진행 상황은 `STATUS.md` 에 기록한다.

## 규칙
- 정보 요약까지만 한다. 매수·매도 추천, 목표가, 투자의견, 자체 전망 금지.
- 모든 수치와 뉴스에는 출처와 기준 시각을 단다. 확실하지 않은 사실은 "확인 필요"로 표시한다.
- 언어: 산출물은 한국어, 코드 주석과 커밋 메시지는 영어. 커밋 prefix `[NewsBriefing]` (루틴의 브리핑 커밋은 `[NewsBriefing] briefing YYYY-MM-DD`).
- main 브랜치에 직접 push 금지. 작업 브랜치 → PR → 머지.
  - 머지는 Claude가 직접 한다 (2026-09-28 오너 승인). 머지 전 `reviewer` 체크리스트로 diff 전체를 검사하고, 하나라도 걸리면 머지하지 않고 오너에게 보고한다. 머지 후 PR 링크와 한 줄 요약을 오너에게 보고한다.
  - 머지·권한 규칙(이 조항, `docs/confirm-protocol.md` 의 머지 항목, `.claude/settings.json` 의 permissions)을 바꾸는 PR도 Claude가 직접 머지한다 (2026-09-30 오너 승인, 기존 "오너가 직접 머지" 예외 폐지). 같은 검사와 사후 보고를 따른다.
  - 예외: 예약 작업이 만드는 `briefings/` 파일은 main에 직접 커밋·push 한다. 이때 브리핑 파일 외에는 커밋하지 않는다.
- API 키·토큰·웹훅 URL은 `.env`(로컬) 또는 클라우드 환경 변수에만 둔다. 커밋하거나 메시지로 보내지 않는다.
- 외부 게시·발송은 오너 컨펌 후 실행한다. 브리핑 완료·에러 Slack 알림은 컨펌 불필요.
