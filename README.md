# NewsBriefing

매일 07:30 KST, 관심 종목·환율·시장 뉴스 브리핑을 자동으로 만들어 `briefings/` 에 커밋하고 Slack(#ai-newsbriefing)으로 알린다.

- 평일: 일일 브리핑 · 토: 주간 요약 · 일: 다음 주 미리보기 · 매달 마지막 날: 월간 브리핑 추가
- 결과물 위치: `briefings/YYYY/<Month>/` (예: `briefings/2026/September/`)
- 절차: [briefing-prompt.md](briefing-prompt.md) · 종목: [watchlist.md](watchlist.md) · 소스: [sources.md](sources.md)
- 실행: claude.ai 클라우드 루틴 (Default 환경, Network access 허용 목록은 [sources.md](sources.md#클라우드-네트워크-허용-목록))

정보 요약용이며 투자 권유가 아니다.
