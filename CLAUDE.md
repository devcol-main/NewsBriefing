# stock-news

## 목표
매일 아침 관심 종목과 시장 주요 뉴스를 요약한 브리핑을 만든다. (평일 일일 브리핑, 토 주간 요약, 일 다음 주 미리보기)
주 실행은 claude.ai 클라우드 루틴 "stock-news 아침 브리핑 (cloud)" — 매일 07:30 KST, 절차는 `briefing-prompt.md`. 이 폴더는 브리핑 결과물과 관심 종목 목록을 보관한다.

## 파일
- `watchlist.md` 관심 종목·섹터 (오너가 관리)
- `briefings/YYYY-MM-DD.md` 브리핑 (요일별 모드)
- `templates/` 모드별 양식: `briefing.md`, `weekly-recap.md`, `week-ahead.md`

## 규칙
- 정보 요약까지만 한다. 매수·매도 추천, 목표가 제시 금지.
- 모든 수치와 뉴스에는 출처와 기준 시각을 단다.
- 브리핑 완료 시 알림만 보낸다. (컨펌 불필요)
- 예약 작업은 `briefings/` 파일만 main에 직접 커밋·push 한다.
