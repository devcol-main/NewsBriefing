# 📈 2026-11-03 (화) 아침 브리핑

> 생성 07:55 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한눈에 (3줄)
- 코스피·코스닥은 美 반도체주 급락 여진에 하락 출발했다가 기관·연기금의 저가 매수에 힘입어 각각 +2.24%(5,859.08)·+1.38%(734.36)로 반등 마감했고, 美 증시는 AI 투자 우려와 개별 종목 약세로 S&P500 −0.51%(7,541.40)·나스닥 −1.07%(25,164.32) 소폭 내렸어요.
- 관심 종목 중에서는 AMD가 전 거래일(10-30 −10.88%)에 이어 −7.52% 추가 급락하며 가장 큰 변동을 보였고, SK하이닉스(+3.81%)·삼성전자(+1.78%)는 국내 반등에 동반 상승했어요.
- 오늘(KST)은 애플 실적(11-02 장마감 후 발표, 호실적이나 가이던스·중국 매출 우려)의 시장 반응과 美 중간선거 결과, 오늘 밤 AMD 3분기 실적 발표를 지켜볼 예정이에요.

## 2. 지수
| 지수 | 종가 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| KOSPI | 5,859.08 | +2.24% | 11-02 종가 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 734.36 | +1.38% | 11-02 종가 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 7,541.40 | −0.51% | 11-02 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 25,164.32 | −1.07% | 11-02 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |

<sub>국내·미국 모두 전 거래일은 11-02(월). 10-31·11-01은 주말이며 11-02·11-03 휴장 없음([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/)). 등락률은 10-30 종가와 `python3 -c`로 직접 계산. 코스피·코스닥 등락(+2.24%·+1.38%)은 [머니투데이](https://www.mt.co.kr/stock/2026/11/02/2026110215393141110)(11-02 15:51) 기사 수치와 일치. S&P500·나스닥 등락은 [investing.com(Reuters)](https://www.investing.com/news/stock-market-news/wall-street-futures-rise-as-ai-stocks-catch-their-breath-midterms-in-focus-4990733)(11-02) 기사 수치와 일치.</sub>

## 2-1. 현금·환율
| 항목 | 값 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| 달러 인덱스 (DXY) | 101.77 / 101.645 (불일치) | −0.11% / −0.10% | 11-02 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) / [investing.com](https://www.investing.com/currencies/us-dollar-index-historical-data) |
| USD/JPY | 157.90 | +0.41% | 11-02 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-02?from=USD&to=JPY,KRW) |
| USD/KRW | 1,342.90 | +0.57% | 11-02 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-02?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 850.48 | +0.16% | 11-02 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-02?from=JPY&to=KRW) |

<sub>DXY는 Yahoo Finance 히스토리 표(101.77, −0.11%)와 investing.com 히스토리 표(101.645, −0.10%)가 서로 달라 "불일치"로 표시, 전일 종가는 각각 101.88(Yahoo)·101.745(investing.com). Yahoo 페이지에는 "Market Open" 표시가 있어 11-02 값이 확정 종가가 아닐 수 있음. 환율 등락은 직전 고시일 10-30 값(USD/JPY 157.25, USD/KRW 1,335.27, JPY/KRW 849.13)과 비교해 `python3 -c`로 계산([USD](https://api.frankfurter.dev/v1/2026-10-30?from=USD&to=JPY,KRW), [JPY→KRW](https://api.frankfurter.dev/v1/2026-10-30?from=JPY&to=KRW)).</sub>

## 3. 관심 종목
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 애플 · 2. 엔비디아 · 3. 마이크로소프트 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))

| 종목 | 종가 | 등락 | 기준 | 한 줄 메모 | 출처 |
|---|---|---|---|---|---|
| 애플 (AAPL) | $338.32 | −1.83% | 11-02 종가 | FY2026 4분기(터너스 신임 CEO 첫 실적) 매출 1,145억달러(+12%YoY)·EPS 2.10달러로 시장 예상(1.99달러)을 웃돌았지만, 아이패드·중국 매출이 예상에 못 미쳤고 시간외 거래에서는 4.33% 하락했음(결과는 오늘 KST 반영) | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/), [investing.com(Reuters)](https://www.investing.com/news/stock-market-news/wall-street-futures-rise-as-ai-stocks-catch-their-breath-midterms-in-focus-4990733) |
| 엔비디아 (NVDA) | $202.06 | −1.26% | 11-02 종가 | 인텔이 11-02 추가로 8.8% 하락하며 반도체 업종 재평가 여진이 이어진 영향을 받았음. 美 법무부(DOJ)의 허깅페이스 인수 반독점 심사도 진행 중임 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/), [investing.com(Reuters)](https://www.investing.com/news/stock-market-news/wall-street-futures-rise-as-ai-stocks-catch-their-breath-midterms-in-focus-4990733) |
| 마이크로소프트 (MSFT) | $507.12 | −2.83% | 11-02 종가 | 약 250억달러 규모 투자등급 채권 발행(AI 투자 자금 조달) 계획과 약 6만명 대상 자발적 퇴직(buyout) 제안 보도로 자본지출·비용 부담 우려가 이어졌음 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/) |
| AMD | $466.84 | −7.52% | 11-02 종가 | 인텔발 반도체 재평가 여진으로 전 거래일(10-30 −10.88%)에 이어 추가 급락했음. 오늘(현지 11-03) 장 마감 후 3분기 실적 발표를 앞두고 있음 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/) |
| 알파벳 (GOOGL) | $278.99 | −0.30% | 11-02 종가 | 실적쇼크 여진이 이어지는 가운데, 60억유로 규모 채권 발행에 약 170억유로 수요가 몰려 자금조달력에 대한 우려는 일부 완화됐음 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) |
| 테슬라 (TSLA) | $403.82 | +1.00% | 11-02 종가 | 유럽 10월 신차 등록이 이탈리아·포르투갈·스웨덴 등에서 두 자릿수~세 자릿수로 늘었다는 보도가 호재로 작용했음. 다만 중국에서는 BYD·샤오미 등 경쟁사의 10월 판매가 호조를 보였음 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) |
| 스페이스X (SPCX) | $136.37 | +1.22% | 11-02 종가 | 워싱턴포스트가 SpaceX의 Boost Mobile(이동통신) 인수·제휴 협의설을 보도하며 통신사업 진출 기대가 호재로 작용했음. 다만 멤피스 데이터센터 대기오염 소송에서는 기각 신청에 패했음 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) |
| 삼성전자 | 229,000원 | +1.78% | 11-02 종가 | 코스피 반등에 동반 상승했음. 역대 최대 3분기 실적(영업이익률 72%)은 유효하나 자사주 매입·소각 규모·시점 미확정 오버행은 지속되고 있음 | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data) |
| SK하이닉스 | 1,472,000원 | +3.81% | 11-02 종가 | 반도체 대형주 중 가장 큰 폭으로 반등했음. 20조원 자사주 매입(10조원 소각) 등 구체적 환원 계획과 컨센서스를 웃돈 역대 최대 3분기 실적이 투자심리를 지지했음 | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data) |

## 4. 주요 뉴스 (최대 5건)
1. **코스피·코스닥, 美 반도체주 급락 여진에도 기관·연기금 매수에 반등 마감** — 11-02 코스피는 美 반도체주 급락 우려로 1.62% 내린 5,637.77로 출발했지만 기관(1조3,354억원)과 기타법인(5,418억원)의 순매수에 힘입어 2.24% 오른 5,859.08로 마감했다. 개인(1조8,634억원)·외국인(178억원)은 순매도했다. 코스닥도 기관 순매수(623억원)에 1.38% 오른 734.36으로 마감했다. 국민연금 등 연기금은 10-30·11-02 이틀간 약 1조664억원을 순매수했는데, 10-30 순매수 규모(8,965억원)는 2022년 1월 27일 이후 역대 두 번째로 크다. 증권가는 연기금의 국내주식 비중 한도 때문에 지수가 추가로 오르면 지속적인 매수 주체가 되기 어려울 수 있다고 본다. ([머니투데이](https://www.mt.co.kr/stock/2026/11/03/2026110219552994953), 11-03 03:58; [머니투데이](https://www.mt.co.kr/stock/2026/11/02/2026110216034248456), 11-02 16:17)
2. **美 S&P500·나스닥, AI 투자 우려·개별 종목 약세로 소폭 하락 — 유가는 중동 평화 기대에 급락** — 11-02(현지) S&P500은 0.51% 내린 7,541.40, 나스닥은 1.07% 내린 25,164.32로 마감했다. 오라클(약 9%↓)·마벨(13%↓, 루멘텀 인수 발표 후)·인텔(8.8%↓, 전날 29% 폭락에 이어 추가 약세)이 하락을 이끌었고, 10월 한 달간 나스닥은 AI 인프라 투자가 단기 현금 창출을 앞서는 데 대한 우려로 5.3% 내렸다. 반면 이란이 평화협상에 응할 뜻을 내비치며 유가가 급락해 에너지 섹터는 4% 내렸지만 소비재·소재 섹터는 올랐다. ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/wall-street-futures-rise-as-ai-stocks-catch-their-breath-midterms-in-focus-4990733), 11-02 05:57)
3. **애플, 터너스 신임 CEO 첫 실적에서 매출·EPS 예상 상회했지만 중국 매출·가이던스는 아쉬워** — 애플은 FY2026 4분기(9월 분기) 매출 1,145억달러(전년대비 +12%), EPS 2.10달러(예상 1.99달러)를 발표했다. 아이폰(575.8억달러)·서비스(315.7억달러)가 강했으나 중국 매출은 예상을 밑돌았고, 다음 분기 매출 가이던스는 전년대비 7~10% 증가로 제시했다. 시간외 거래에서 주가는 한때 4.33% 하락했다. ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/) 관련 자료, 11-02~03)
4. **美 중간선거, 오늘(현지 11-03) 투표 — 하원 민주당 탈환 가능성, 상원은 불투명** — 하원 435석 전체와 상원 33석, 주지사 36명을 새로 뽑는 중간선거가 현지 11-03(화) 치러진다. 여론조사에서는 민주당이 하원을 차지할 가능성이 높게 나타났지만 상원 결과는 불투명하다. 이번 선거는 트럼프 대통령의 공화당이 집권 첫 2년간 장악했던 상·하원 통제권을 민주당이 가져올 수 있을지를 가른다. ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/wall-street-futures-rise-as-ai-stocks-catch-their-breath-midterms-in-focus-4990733), 11-02 05:57)
5. **마이크로소프트, AI 투자 재원 마련 위해 약 250억달러 투자등급 채권 발행 계획** — 마이크로소프트가 AI 투자 확대를 위해 약 250억달러 규모의 투자등급 채권을 발행할 계획이라고 보도됐다(9년 만의 첫 미국 투자등급 채권 매각). 같은 시기 약 6만명의 직원에게 자발적 퇴직(buyout)을 제안한 사실도 알려져 자본지출·비용 부담에 대한 투자자 우려가 이어지고 있다. ([stockanalysis.com](https://stockanalysis.com/stocks/msft/) 관련 보도, 11-01~02)

## 5. 오늘 일정
- 美 중간선거 투표일(현지 11-03) — 하원 435석·상원 33석·주지사 36명 선출. 개표 결과는 아직 나오지 않았으며 KST 기준 오늘 밤~내일 새벽 순차적으로 반영될 것으로 추정됨 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/wall-street-futures-rise-as-ai-stocks-catch-their-breath-midterms-in-focus-4990733))
- AMD, 오늘(현지 11-03) 美 정규장 마감 후 3분기 실적 발표 예정 — 결과는 KST 11-04 새벽경 반영 추정 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 보도)
- 美 9월 구인·이직보고서(JOLTS), 美 동부시간 11-03 10:00(=KST 11-04 00:00경) 발표 예정 ([BLS 일정](https://www.bls.gov/schedule/2026/11_sched_list.htm))
- 국내·미국 증시 휴장 없음 ([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/))

## 6. 전망 (자체 판단)
**직전 전망 점검:** 직전 일일 브리핑(2026-11-02)의 전망 13건을 10-30→11-02 종가로 확인한 결과 적중 5건(나스닥 −1.07%·엔비디아 −1.26%·마이크로소프트 −2.83%·알파벳 −0.30%는 각각 "하락 우세"와 일치, SK하이닉스 +3.81%는 "상승 우세"와 일치), 빗나감 8건(코스피 +2.24%·코스닥 +1.38%·S&P500 −0.51%·AMD −7.52%·테슬라 +1.00%·삼성전자 +1.78%는 "방향성 불분명"(±0.5% 밴드, S&P500은 근소하게 초과) 또는 코스닥의 "하락 우세"를 벗어났고, 애플 −1.83%는 "상승 우세"와 반대, 스페이스X +1.22%는 "하락 우세"와 반대), 판단 보류 0건. 기관·연기금의 저가 매수가 예상보다 강하게 유입되며 국내 지수·종목 대부분에서 "방향성 불분명"·"하락 우세" 판정이 상승 방향으로 벗어났다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 11-03~11-04 | 상승: 기관·연기금이 10-30·11-02 이틀 연속 저가 매수에 나서며 지수 반등을 이끌었다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/02/2026110216034248456))<br>하락: 개인·외국인은 11-02에도 동반 순매도를 이어갔다 (같은 자료) | 애플 실적 반응과 美 중간선거 결과에 따라 변동성이 커질 수 있고, 지수가 더 오르면 연기금의 비중 한도상 매수 여력이 줄어들 수 있다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/02/2026110216034248456)) | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 방향성 불분명 | 11-03~11-04 | 상승: 11-02 기관이 코스닥에서도 623억원을 순매수하며 코스피와 함께 반등했다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/03/2026110219552994953))<br>하락: 코스피와 마찬가지로 개인·외국인 순매도 압력이 이어지고 있다 (같은 자료 종합) | 반도체 업종 재평가 우려가 재부각되면 코스피보다 변동성이 더 크게 나타날 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| S&P 500 | 방향성 불분명 | 11-03~11-04 | 상승: 이란이 평화협상에 응할 뜻을 보이며 유가가 급락해 인플레이션 우려가 완화됐고 장기 국채 금리도 내렸다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/wall-street-futures-rise-as-ai-stocks-catch-their-breath-midterms-in-focus-4990733))<br>하락: AI 인프라 투자가 단기 현금 창출을 앞서는 데 대한 우려가 10월 한 달간 지속됐다 (같은 자료) | 애플 실적 반응과 美 중간선거 결과에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| NASDAQ | 하락 우세 | 11-03~11-04 | 1. 오라클(약 9%↓)·마벨(13%↓)·인텔(8.8%↓, 전날 29% 폭락에 이어 추가 약세)이 11-02 동반 급락하며 AI·반도체 업종 전반에 재평가 우려가 커졌다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/wall-street-futures-rise-as-ai-stocks-catch-their-breath-midterms-in-focus-4990733))<br>2. 10월 한 달간 나스닥은 AI 지출 속도에 대한 우려로 5.3% 내렸다 (같은 자료) | 애플이 실적에서 매출·EPS를 예상보다 좋게 발표해 대형 기술주 전반에 긍정적으로 작용할 수 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/)) | 보통 — AI·반도체 업종 재평가라는 서로 다른 두 종목(오라클·마벨)에서 나온 독립적 근거 |
| 애플 (AAPL) | 방향성 불분명 | 11-03~11-04 | 상승: FY2026 4분기 매출(+12%YoY)과 EPS(2.10달러)가 시장 예상(1.99달러)을 웃돌았다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/))<br>하락: 시간외 거래에서 주가가 한때 4.33% 하락했다 (같은 자료) | 가이던스(다음 분기 매출 +7~10%)와 중국 매출 부진이 이미 알려져 있어 추가 하락 압력이 될 수도, 호실적으로 이미 반영된 우려가 해소될 수도 있다 | 낮음 — 시간외 반응과 실적 지표가 서로 다른 방향을 가리킴 |
| 엔비디아 (NVDA) | 하락 우세 | 11-03~11-04 | 1. 인텔이 11-02 추가로 8.8% 하락하며 반도체 업종 재평가 우려가 이어졌다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/wall-street-futures-rise-as-ai-stocks-catch-their-breath-midterms-in-focus-4990733))<br>2. 美 법무부(DOJ)가 129억달러 규모 허깅페이스 인수 건을 반독점 심사 중이다 ([2026-11-02 브리핑](2026-11-02-NewsBriefing.md) 참고) | 젠슨 황 CEO는 네오클라우드 수요가 매우 강하다고 밝혔다 ([2026-10-26 브리핑](../October/2026-10-26-NewsBriefing.md) 참고) | 보통 — 업종 재평가·DOJ 심사라는 두 독립적 근거 |
| 마이크로소프트 (MSFT) | 하락 우세 | 11-03~11-04 | 1. AI 투자 재원 마련을 위한 약 250억달러 투자등급 채권 발행 계획이 보도되며 자본지출 부담 우려가 커졌다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/))<br>2. 약 6만명 대상 자발적 퇴직(buyout) 제안 보도로 구조조정 비용 우려도 겹쳤다 (같은 자료) | 여러 증권사가 Azure 매출 성장(+48%)에 대한 긍정적인 분석을 유지하고 있다 ([2026-10-29 브리핑](../October/2026-10-29-NewsBriefing.md) 참고) | 보통 — 자본지출 부담·구조조정 비용이라는 두 독립적 근거 |
| AMD | 하락 우세 | 11-03~11-04 | 1. 인텔발 반도체 재평가 우려로 10-30(−10.88%)·11-02(−7.52%) 이틀 연속 큰 폭으로 급락했다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/))<br>2. 반도체 업종 전반의 재평가 우려가 11-02에도 인텔 추가 하락(−8.8%)으로 이어지고 있다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/wall-street-futures-rise-as-ai-stocks-catch-their-breath-midterms-in-focus-4990733)) | 메타와의 전략적 파트너십 확대(10-27, 메타 지분 발행에 약 10억달러 투자)는 긍정적 재료다. 오늘(현지 11-03) 장 마감 후 발표되는 3분기 실적에 따라 다음 거래일(11-04) 이후 변동성이 매우 커질 수 있으나, 발표 시점이 장 마감 후라 이번 거래일(11-03 종가)에는 직접 반영되지 않는다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/)) | 보통 — 이틀 연속 급락·업종 재평가 지속이라는 근거가 뚜렷함 |
| 알파벳 (GOOGL) | 방향성 불분명 | 11-03~11-04 | 상승: 60억유로 규모 채권 발행에 약 170억유로 수요가 몰려 자금조달력 우려가 일부 완화됐다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/))<br>하락: 최근 분기보고서에서 공개된 985억달러 규모 잠재적 금융 의무 증가 우려가 이어지고 있다 ([2026-11-02 브리핑](2026-11-02-NewsBriefing.md) 참고) | Scotiabank는 매수 의견을 유지했고 구글클라우드 매출은 전년대비 103% 성장했다 ([2026-10-30 브리핑](../October/2026-10-30-NewsBriefing.md) 참고) | 낮음 — 상승·하락 근거가 팽팽함 |
| 테슬라 (TSLA) | 방향성 불분명 | 11-03~11-04 | 상승: 유럽 10월 신차 등록이 이탈리아·포르투갈·스웨덴 등 여러 나라에서 두 자릿수~세 자릿수로 늘었다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/))<br>하락: 중국에서는 BYD·샤오미·XPeng 등 경쟁사의 10월 판매가 호조를 보이며 경쟁이 심화되고 있다 (같은 자료) | 스페이스X와의 합병 논의가 진전되면 밸류에이션 재평가 기대로 주가가 반응할 수 있다 ([2026-11-02 브리핑](2026-11-02-NewsBriefing.md) 참고) | 보통 — 유럽 판매 회복·중국 경쟁 심화라는 두 독립적 근거 |
| 스페이스X (SPCX) | 방향성 불분명 | 11-03~11-04 | 상승: 워싱턴포스트가 Boost Mobile(이동통신) 인수·제휴 협의설을 보도하며 통신사업 진출 기대가 커졌다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/))<br>하락: 멤피스 데이터센터 대기오염 소송에서 기각 신청에 패해 추가 소송 부담이 커졌다 (같은 자료) | 고객 집중도(앤트로픽 비중)·대주주(바이낸스) 매도 우려는 여전히 남아 있다 ([2026-11-02 브리핑](2026-11-02-NewsBriefing.md) 참고) | 낮음 — 통신사업 기대와 법적 리스크가 상충함 |
| 삼성전자 | 방향성 불분명 | 11-03~11-04 | 상승: 역대 최대 3분기 실적(반도체 부문 영업이익률 72%)과 11-02 코스피 반등에 동반 상승했다 ([kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data), [머니투데이](https://www.mt.co.kr/stock/2026/11/03/2026110219552994953))<br>하락: 자사주 매입·소각 규모·시점 미확정 오버행이 여전히 남아 있다 ([2026-11-02 브리핑](2026-11-02-NewsBriefing.md) 참고) | 반도체 업종 재평가 우려가 재부각되면 다시 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 상승 우세 | 11-03~11-04 | 1. 20조원 자사주 매입(10조원 소각) 등 구체적인 환원 계획이 투자심리를 지지하고 있다 ([kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data))<br>2. 11-02 반등에서 반도체 대형주 중 가장 큰 폭(+3.81%)으로 올라 삼성전자·코스피 대비 투자심리 우위를 재확인했다 (같은 자료) | 반도체 업종 전반 재평가 우려가 재부각되면 10-30(−7.08%)과 같은 급락이 재연될 수 있다 | 보통 — 구체적 환원 계획·상대적 강세 반등이라는 두 독립적 근거 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
