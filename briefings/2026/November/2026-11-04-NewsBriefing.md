# 📈 2026-11-04 (수) 아침 브리핑

> 생성 08:10 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한눈에 (3줄)
- 코스피·코스닥은 美 빅테크 자금조달發 AI 투자 수익성 우려 재확산에 반도체 대형주(삼성전자 −4.15%·SK하이닉스 −5.03%)가 급락하며 각각 −3.59%(5,648.79)·−4.08%(704.39)로 밀렸고, 美 증시는 중간선거일 AI주 반등에 힘입어 S&P500 +0.36%(7,568.92)·나스닥 +0.83%(25,372.01)로 소폭 올랐어요.
- 관심 종목 중에서는 AMD가 3분기 실적·가이던스 호조로 정규장 +3.65%(시간외 추가 급등)를 기록하며 가장 눈에 띄는 반등을 보였고, 반대로 SK하이닉스는 국내 반도체 재평가 우려로 가장 큰 폭(−5.03%)으로 내렸어요.
- 오늘(KST)은 美 중간선거 개표 결과가 계속 발표될 예정이며(하원 다수당 여부가 핵심 변수), AMD의 호실적·가이던스가 현지 오늘 밤(11-04) 정규장에 어떻게 반영될지도 지켜볼 예정이에요.

## 2. 지수
| 지수 | 종가 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| KOSPI | 5,648.79 | −3.59% | 11-03 종가 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 704.39 | −4.08% | 11-03 종가 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 7,568.92 | +0.36% | 11-03 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 25,372.01 | +0.83% | 11-03 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |

<sub>국내·미국 모두 전 거래일은 11-03(화). 11-03·11-04 모두 한국·미국 증시 휴장 없음([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/); 11-03은 에콰도르·일본, 11-04는 러시아 휴일만 있음). 등락률은 11-02 종가와 `python3 -c`로 직접 계산. 코스피·코스닥 등락(−3.59%·−4.08%)은 [뉴스1](https://www.news1.kr/finance/market-exr/6341583)(11-03) 기사 수치와 일치. S&P500·나스닥 등락은 [investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314)(업데이트 11-03 16:11, 시간대 미표기) 기사의 +0.3%·+0.8%(근사치)와 대체로 일치.</sub>

## 2-1. 현금·환율
| 항목 | 값 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| 달러 인덱스 (DXY) | 101.88 / 101.730 (불일치) | +0.13% / +0.10% | 11-03 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) / [investing.com](https://www.investing.com/currencies/us-dollar-index-historical-data) |
| USD/JPY | 158.29 | +0.25% | 11-03 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-03?from=USD&to=JPY,KRW) |
| USD/KRW | 1,344.59 | +0.13% | 11-03 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-03?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 849.46 | −0.12% | 11-03 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-03?from=JPY&to=KRW) |

<sub>DXY는 Yahoo Finance 히스토리 표(101.88, 지수)와 investing.com 히스토리 표(101.730, 12월물 선물)가 서로 달라 "불일치"로 표시, 전일 종가는 각각 101.75(Yahoo)·101.624(investing.com). 환율 등락은 직전 고시일 11-02 값(USD/JPY 157.90, USD/KRW 1,342.90, JPY/KRW 850.48)과 비교해 `python3 -c`로 계산([USD](https://api.frankfurter.dev/v1/2026-11-02?from=USD&to=JPY,KRW), [JPY→KRW](https://api.frankfurter.dev/v1/2026-11-02?from=JPY&to=KRW)).</sub>

## 3. 관심 종목
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 엔비디아 · 2. 애플 · 3. 마이크로소프트 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))

| 종목 | 종가 | 등락 | 기준 | 한 줄 메모 | 출처 |
|---|---|---|---|---|---|
| 엔비디아 (NVDA) | $206.69 | +2.29% | 11-03 종가 | 반도체 업종 전반 반등(필라델피아반도체지수 +3%)에 동반 상승했고, Barron's에 따르면 시가총액 세계 1위를 다시 차지했음. FT는 엔비디아가 데이터센터 파트너들에게 중국 고객 비중 축소를 요청했다고 보도했음 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/), [investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314) |
| 애플 (AAPL) | $331.90 | −1.90% | 11-03 종가 | 11-02 발표한 FY2026 4분기 실적은 매출·EPS 모두 예상을 웃돌았지만 다음 분기 매출총이익률 가이던스(45~46%)가 시장 기대(46.9%)에 못 미쳤고 메모리 칩 가격 상승이 부담으로 꼽혔음 | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/), [investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314) |
| 마이크로소프트 (MSFT) | $520.99 | +2.74% | 11-03 종가 | AI·반도체 관련주 전반 반등(매그니피센트7 다수 상승)에 동반 상승했음. 약 250억달러 투자등급 채권 발행과 약 6만명 대상 자발적 퇴직(buyout) 제안에 따른 자본지출·비용 부담 우려는 이어지고 있음 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/), [investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314) |
| AMD | $483.90 | +3.65% | 11-03 종가 | 3분기 매출 134억달러·데이터센터 매출 +97%YoY로 가이던스 상단을 상회했고 4분기 매출 전망도 월가 예상치를 웃돌아, 장 마감 후 실적 발표에 시간외 거래에서 추가로 약 6% 급등했음 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/), [investing.com(Reuters)](https://www.investing.com/news/stock-market-news/amd-forecasts-quarterly-revenue-above-estimates-as-datacenter-growth-accelerates-4996502) |
| 알파벳 (GOOGL) | $280.03 | +0.37% | 11-03 종가 | 60억유로 규모 채권 발행에 약 170억유로 수요가 몰려 자금조달력 우려가 일부 완화됐지만, 최근 분기보고서에서 공개된 985억달러 규모 잠재적 금융 의무 증가 우려는 남아 있음 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) |
| 테슬라 (TSLA) | $398.50 | −1.32% | 11-03 종가 | 美 반도체·AI 관련주 반등 속에서도 동반 상승하지 못하고 내렸음. 특별한 종목별 뉴스는 확인되지 않았음(유럽 10월 신차 등록 호조·중국 경쟁 심화라는 기존 요인이 이어지는 것으로 추정) | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) |
| 스페이스X (SPCX) | $141.31 | +3.62% | 11-03 종가 | 워싱턴포스트가 EchoStar의 Boost Mobile(이동통신) 인수·네트워크 이용 협의를 보도하며 통신사업 진출 기대가 이어졌음. 멤피스 데이터센터 대기오염 소송에서는 기각 신청이 다시 거부됐음 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) |
| 삼성전자 | 219,500원 | −4.15% | 11-03 종가 | 빅테크 자금조달發 AI 투자 수익성 우려가 재확산하며 외국인·기관이 동반 순매도해 코스피 반도체 대형주가 급락했음. 자사주 매입·소각 규모·시점 미확정 오버행도 지속되고 있음 | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data), [뉴스1](https://www.news1.kr/finance/market-exr/6341614) |
| SK하이닉스 | 1,398,000원 | −5.03% | 11-03 종가 | 같은 이유로 반도체 대형주 중 가장 큰 폭으로 급락했음. 20조원 자사주 매입(10조원 소각) 등 구체적 환원 계획은 유효하나 단기 수급 악화를 막지 못했음 | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data), [뉴스1](https://www.news1.kr/finance/market-exr/6341614) |

## 4. 주요 뉴스 (최대 5건)
1. **코스피·코스닥, AI 투자 수익성 우려 재확산에 외국인·기관 매도로 3~4%대 급락** — 11-03 코스피는 전 거래일보다 210.29포인트(3.59%) 내린 5,648.79, 코스닥은 29.97포인트(4.08%) 내린 704.39로 마감했다. 美 빅테크의 대규모 자금조달 움직임으로 AI 투자 수익성에 대한 우려가 재확산한 영향으로, 외국인(약 1.5조원)과 기관(약 5,100억원)이 순매도한 반면 개인(약 1.6조원)은 순매수했다. 삼성전자(−4.15%)·SK하이닉스(−5.03%)가 하락을 주도했다. ([뉴스1](https://www.news1.kr/finance/market-exr/6341614), 11-03 16:00)
2. **美 S&P500·나스닥, 중간선거일 AI주 반등에 소폭 상승 — 필라델피아반도체지수 5거래일 만에 반등** — 11-03(현지) S&P500은 0.3% 오른 7,567.72, 나스닥은 0.8% 오른 25,372.01로 마감했다(다우존스는 0.4% 하락). 필라델피아반도체지수(SOX)는 거의 3% 올라 5거래일 만에 처음 상승 마감했고, 오라클(+5.85%)·AMD(+3.65%)·메타(+2.35%)·마이크로소프트(+2.70%)·아마존(+2.06%) 등 매그니피센트7 다수가 올랐다. 애플(약 −2%)·팔란티어(약 −2%)는 하락했다. ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314), 업데이트 11-03 16:11)
3. **AMD, 3분기 매출 134억달러·데이터센터 +97%YoY로 가이던스 상회 — 시간외 주가 급등** — AMD는 11-03(현지) 장 마감 후 3분기 매출 134억달러(비GAAP EPS 2.09달러), 데이터센터 매출 전년대비 97% 증가를 발표했다. 8월 제시했던 가이던스(127억~133억달러) 상단을 웃돌았고, 4분기 매출 전망도 월가 예상치보다 높게 제시하며 데이터센터(AI 가속기) 성장 가속화를 시사했다. 시간외 거래에서 주가는 483.90달러에서 약 6% 추가 상승했다. ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/amd-forecasts-quarterly-revenue-above-estimates-as-datacenter-growth-accelerates-4996502), 11-03~04)
4. **애플, 매출·EPS는 예상 상회했지만 매출총이익률 가이던스는 시장 기대 하회** — 애플의 FY2026 4분기 실적은 매출·EPS 모두 예상을 웃돌았지만, 다음 분기 매출총이익률 가이던스(45~46%)가 시장 기대(46.9%)에 못 미쳐 메모리 칩 가격 상승 부담이 부각됐다. 주가는 11-03 정규장에서 약 2% 내렸다. ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314), 업데이트 11-03 16:11)
5. **美 중간선거 투표 종료, 개표 진행 중 — 하원 다수당 여부가 핵심 변수** — 하원 435석 전체와 상원 일부, 주지사 다수를 새로 뽑는 중간선거가 현지 11-03(화) 치러졌다. Deutsche Bank의 Jim Reid는 1946~2022년 중간선거 이후 1년간 S&P500이 매번 상승(평균 +14.4%)했다고 언급하며 "선거가 불확실성을 제거한다"고 평가했다. 개표 결과는 KST 기준 오늘 이후 순차적으로 확정될 것으로 추정된다. ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314), 업데이트 11-03 16:11)

## 5. 오늘 일정
- 美 중간선거 개표 결과 계속 발표 중 — 하원 다수당 교체 여부(민주 218→221석 이상 확보 필요) 등 결과에 따라 시장 변동성이 커질 수 있음 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314))
- AMD 3분기 실적(현지 11-03 장 마감 후 발표, 가이던스 상회)에 대한 시장 반응이 현지 11-04 정규장(KST 11-05 새벽 반영 추정)에 본격적으로 나타날 것으로 추정됨 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/amd-forecasts-quarterly-revenue-above-estimates-as-datacenter-growth-accelerates-4996502))
- 美 경제지표 발표 없음 ([BLS 11월 일정](https://www.bls.gov/schedule/2026/11_sched_list.htm) 기준 11-04 예정 발표 없음; 9월 JOLTS는 11-03 발표 완료)
- 국내·미국 증시 휴장 없음 ([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/))

## 6. 전망 (자체 판단)
**직전 전망 점검:** 직전 일일 브리핑(2026-11-03)의 전망 13건을 11-02→11-03 종가로 확인한 결과 적중 2건(S&P500 +0.36%·알파벳 +0.37%는 각각 "방향성 불분명" 예측의 ±0.5% 밴드 안에 들어 적중), 빗나감 11건(코스피 −3.59%·코스닥 −4.08%·애플 −1.90%·테슬라 −1.32%·스페이스X +3.62%·삼성전자 −4.15%는 "방향성 불분명" 예측의 ±0.5% 밴드를 벗어났고, 나스닥 +0.83%·엔비디아 +2.29%·마이크로소프트 +2.74%·AMD +3.65%는 "하락 우세" 예측과 반대, SK하이닉스 −5.03%는 "상승 우세" 예측과 반대), 판단 보류 0건. 美 반도체 대형주가 AMD 실적 기대·중간선거 불확실성 해소 기대로 강하게 반등한 반면 국내 반도체 대형주는 AI 투자 수익성 우려 재확산에 급락하며, 전날 예상과 반대 방향으로 움직인 항목이 많았다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 11-04~11-05 | 상승: AMD의 실적·가이던스 호조와 필라델피아반도체지수(+3%) 반등으로 글로벌 반도체 투자심리가 개선될 여지가 있다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/amd-forecasts-quarterly-revenue-above-estimates-as-datacenter-growth-accelerates-4996502))<br>하락: 11-03 외국인(약 1.5조원)·기관(약 5,100억원)이 동반 순매도하며 지수 하락을 주도했다 ([뉴스1](https://www.news1.kr/finance/market-exr/6341614)) | 美 중간선거 개표 결과에 따라 변동성이 커질 수 있다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314)) | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 방향성 불분명 | 11-04~11-05 | 상승: AMD 실적 호조·美 반도체주 반등이 코스닥 반도체 관련주에도 긍정적으로 전이될 수 있다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/amd-forecasts-quarterly-revenue-above-estimates-as-datacenter-growth-accelerates-4996502))<br>하락: 11-03 장중(오후 1시 55분) 기준으로도 외국인·기관이 코스닥에서 매도세를 보였다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/03/2026110309112639760)) | 반도체 업종 재평가 우려가 재부각되면 코스피보다 변동성이 더 크게 나타날 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| S&P 500 | 상승 우세 | 11-04~11-05 | 1. 필라델피아반도체지수(SOX)가 5거래일 만에 처음으로 약 3% 반등하며 AI 트레이드가 재개됐다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314))<br>2. Deutsche Bank의 Jim Reid는 1946~2022년 중간선거 이후 1년간 S&P500이 매번 상승(평균 +14.4%)했다며 "선거가 불확실성을 제거한다"고 평가했다 (같은 기사) | 애플의 매출총이익률 가이던스(45~46%)가 시장 기대(46.9%)에 못 미쳤고 메모리 비용 상승 부담이 대형 기술주 전반에 부정적으로 작용할 수 있다 (같은 기사) | 보통 — 반도체 반등·중간선거 불확실성 해소 기대라는 두 독립적 근거(다만 중간선거 통계는 1년 단위 평균으로 이번 주 적용에는 한계가 있음) |
| NASDAQ | 상승 우세 | 11-04~11-05 | 1. AMD가 4분기 매출 가이던스를 월가 예상치보다 높게 제시하며 데이터센터 매출 성장 가속화를 시사했고 시간외 거래에서 주가가 급등했다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/amd-forecasts-quarterly-revenue-above-estimates-as-datacenter-growth-accelerates-4996502))<br>2. 필라델피아반도체지수가 3% 반등하며 반도체주 전반 투자심리가 개선됐다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314)) | 애플 가이던스 실망과 팔란티어 하락처럼 개별 대형주 우려가 남아 있고, 10월 한 달간 AI 인프라 투자 수익성 우려로 나스닥이 5.3% 내렸던 배경은 완전히 해소되지 않았다 | 보통 — 데이터센터 성장 가속화·반도체 업종 반등이라는 두 독립적 근거 |
| 엔비디아 (NVDA) | 방향성 불분명 | 11-04~11-05 | 상승: 반도체 업종 전반 반등(SOX +3%)에 힘입어 11-03 +2.29% 올랐고 Barron's에 따르면 시가총액 세계 1위를 재탈환했다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314), [stockanalysis.com](https://stockanalysis.com/stocks/nvda/))<br>하락: FT 보도에 따르면 엔비디아가 데이터센터 파트너들에게 중국 고객 비중 축소를 요청했고, 美 법무부(DOJ)의 허깅페이스 인수 반독점 심사도 계속되고 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/)) | 美 중간선거 개표 결과에 따라 AI·반도체 전반의 투자심리가 다시 흔들릴 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 애플 (AAPL) | 하락 우세 | 11-04~11-05 | 1. 다음 분기 매출총이익률 가이던스(45~46%)가 시장 기대(46.9%)에 못 미쳤고 메모리 칩 가격 상승이 부담으로 꼽혔다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314))<br>2. 11-02 실적 발표에서 아이패드·중국 매출이 시장 예상에 못 미쳤다 ([2026-11-03 브리핑](2026-11-03-NewsBriefing.md) 참고) | 매출(1,145억달러, +12%YoY)·EPS(2.10달러)는 시장 예상(1.99달러)을 웃돌아 펀더멘털 자체는 견조했다 | 보통 — 가이던스 하회·아이패드·중국 매출 부진이라는 두 독립적 근거 |
| 마이크로소프트 (MSFT) | 상승 우세 | 11-04~11-05 | 1. 필라델피아반도체지수(+3%)·오라클(+5.85%)·메타(+2.35%) 등 반도체·AI 관련주 전반에 반등 훈풍이 불고 있다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314))<br>2. 여러 증권사가 Azure 매출 성장(+48%)에 대한 긍정적인 분석을 유지하고 있다 ([2026-10-29 브리핑](../October/2026-10-29-NewsBriefing.md) 참고) | 약 250억달러 투자등급 채권 발행과 약 6만명 대상 자발적 퇴직(buyout) 제안에 따른 자본지출·구조조정 비용 부담 우려가 여전히 남아 있다 | 보통 — 업종 반등·Azure 성장 유지라는 두 독립적 근거 |
| AMD | 상승 우세 | 11-04~11-05 | 1. 3분기(비GAAP) EPS 2.09달러·데이터센터 매출 +97%YoY로 가이던스 상단을 상회했다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/amd-forecasts-quarterly-revenue-above-estimates-as-datacenter-growth-accelerates-4996502))<br>2. 4분기 매출 가이던스를 월가 예상치보다 높게 제시했고 시간외 거래에서 주가가 약 6% 추가 급등했다 (같은 기사) | 11-02·03 이틀 연속 반도체 재평가 우려로 급락했던 여파가 완전히 해소됐는지 불확실하고, 시간외 반응이 정규장에서도 유지될지는 변동성이 클 수 있다 | 높음 — 실적·가이던스 모두 호조라는 독립적 근거 2개, 반대 요인은 상대적으로 약함 |
| 알파벳 (GOOGL) | 방향성 불분명 | 11-04~11-05 | 상승: 60억유로 규모 채권 발행에 약 170억유로 수요가 몰려 자금조달력 우려가 일부 완화됐다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/))<br>하락: 최근 분기보고서에서 공개된 985억달러 규모 잠재적 금융 의무 증가 우려가 여전히 남아 있다 ([2026-11-02 브리핑](2026-11-02-NewsBriefing.md) 참고) | 美 중간선거 결과·AI 트레이드 반등 지속 여부에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 테슬라 (TSLA) | 방향성 불분명 | 11-04~11-05 | 상승: 유럽 10월 신차 등록이 이탈리아·포르투갈·스웨덴 등 여러 나라에서 두 자릿수~세 자릿수로 늘었다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/))<br>하락: 중국에서는 BYD·샤오미 등 경쟁사의 10월 판매가 호조를 보이며 경쟁이 심화되고 있다 (같은 자료) | 스페이스X와의 합병 논의가 진전되면 밸류에이션 재평가 기대로 주가가 반응할 수 있다 ([2026-11-02 브리핑](2026-11-02-NewsBriefing.md) 참고) | 낮음 — 상승·하락 근거가 팽팽하고, 11-03에는 업종 반등에도 동반 상승하지 못했다 |
| 스페이스X (SPCX) | 방향성 불분명 | 11-04~11-05 | 상승: 워싱턴포스트가 EchoStar의 Boost Mobile(이동통신) 인수·네트워크 이용 협의를 보도하며 통신사업 진출 기대가 이어지고 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/))<br>하락: 멤피스 데이터센터 대기오염 소송에서 기각 신청이 다시 거부돼 법적 부담이 커지고 있다 (같은 자료) | 고객 집중도(앤트로픽 비중)·대주주(바이낸스) 매도 우려는 여전히 남아 있다 ([2026-11-02 브리핑](2026-11-02-NewsBriefing.md) 참고) | 낮음 — 통신사업 기대와 법적 리스크가 상충함 |
| 삼성전자 | 방향성 불분명 | 11-04~11-05 | 상승: 美 반도체 대형주(AMD +3.65%·엔비디아 +2.29%)가 동반 반등하며 글로벌 반도체 투자심리가 개선될 여지가 있다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314))<br>하락: 자사주 매입·소각 규모·시점 미확정 오버행이 여전히 남아 있고, 11-03 외국인·기관이 동반 순매도하며 지수 하락을 주도했다 ([뉴스1](https://www.news1.kr/finance/market-exr/6341614)) | AI 투자 수익성 우려가 재부각되면 다시 급락할 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 방향성 불분명 | 11-04~11-05 | 상승: 美 반도체 대형주 동반 반등과 20조원 자사주 매입(10조원 소각) 등 구체적 환원 계획이 투자심리를 지지할 수 있다 ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-apple-dips-after-mixed-earnings-4993314), [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data))<br>하락: 11-03 외국인·기관 매도에 반도체 대형주 중 가장 큰 폭(−5.03%)으로 밀렸다 ([뉴스1](https://www.news1.kr/finance/market-exr/6341614)) | 美 중간선거 결과에 따라 시장 전반 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
