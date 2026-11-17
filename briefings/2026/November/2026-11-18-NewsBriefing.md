# 📈 2026-11-18 (수) 아침 브리핑

> 생성 07:55 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한눈에 (3줄)
- 전 거래일(11-17) 美 지수는 엔비디아 실적 발표를 앞두고 동반 하락했다: 다우존스 −1.64%(3개월 신저가)·S&P500 −1.03%(7월來 최저 마감)·나스닥 −0.74%로, AI 투자 위축 우려와 中 AI칩 수출통제 확대가 배경으로 꼽혔다.
- 국내 증시도 코스피 −2.59%(9개월 반만에 5,000선 붕괴)·코스닥 −2.34%로 동반 하락했고, 관심 종목 중에서는 삼성전자(−3.30%)가 가장 많이 내렸고 테슬라(+0.10%)·스페이스X(+3.16%)만 올랐다.
- 엔비디아는 장 마감 후(현지 11-17) 3분기 매출이 전년대비 103% 늘어난 호실적과 4분기 가이던스 상회를 발표했으나, WSJ는 SEC가 젠슨 황 전 CEO 사임 이후 회사를 조사하고 있다고 보도했다.

## 2. 지수
| 지수 | 종가 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| KOSPI | 4,968.48 | −2.59% | 11-17 종가 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 650.06 | −2.34% | 11-17 종가 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 7,340.53 | −1.03% | 11-17 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 24,328.38 | −0.74% | 11-17 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |

<sub>국내·미국 모두 전 거래일은 11-17(화). 11-17·11-18 국내·미국 증시 휴장 없음([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/), 둘 다 11-18 조회). 등락률은 11-16 종가(KOSPI 5,100.50·KOSDAQ 665.65·S&P500 7,416.59·NASDAQ 24,509.76, [2026-11-17 브리핑](2026-11-17-NewsBriefing.md) 참고)와 위 11-17 종가를 `python3 -c`로 직접 계산. KOSPI·KOSDAQ 등락률(−2.59%·−2.34%)은 kr.investing.com 히스토리 표에 함께 표시된 변동률과 일치. S&P500은 Yahoo Finance 종가(7,340.53, −1.03%)와 [investing.com 마감 기사](https://www.investing.com/news/stock-market-news/us-stocks-lower-at-close-of-trade-dow-jones-industrial-average-down-164-5034091)의 종가(7,340.89, −1.02%) 사이에 소수점 수준 불일치가 있어 둘 다 표기(등락률은 Yahoo Finance 기준 계산). 나스닥 등락률(−0.74%)은 같은 기사 수치와 일치. 같은 기사에서 다우존스 산업평균은 50,759.42(−1.64%, 3개월 신저가)로 집계됐으나, 다우는 watchlist 대상이 아니라 표에는 넣지 않음.</sub>

## 2-1. 현금·환율
| 항목 | 값 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| 달러 인덱스 (DXY) | 103.55 | 0.00% | 11-17 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) |
| USD/JPY | 159.30 | −0.19% | 11-17 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-17?from=USD&to=JPY,KRW) |
| USD/KRW | 1,336.21 | +0.10% | 11-17 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-17?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 838.82 | +0.29% | 11-17 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-17?from=JPY&to=KRW) |

<sub>등락은 11-16 값(USD/JPY 159.60·USD/KRW 1,334.87 [Frankfurter 11-16](https://api.frankfurter.dev/v1/2026-11-16?from=USD&to=JPY,KRW), JPY/KRW 836.40 [JPY 기준](https://api.frankfurter.dev/v1/2026-11-16?from=JPY&to=KRW))과 비교해 `python3 -c`로 계산. DXY는 Yahoo Finance 히스토리 표 11-16·11-17 종가가 모두 103.55로 동일해 등락 0.00%로 표기(2026-11-17 브리핑에 기록된 11-16 종가 103.58과는 소폭 다름 — Yahoo Finance 과거 데이터 갱신으로 추정). 교차 확인한 [investing.com](https://www.investing.com/indices/usdollar-historical-data)에서는 11-16 103.55→11-17 103.56(+0.01%)로 집계돼 두 소스 사이 소수점 수준 불일치가 있음.</sub>

## 3. 관심 종목
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 애플 · 2. 마이크로소프트 · 3. 엔비디아 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))

| 종목 | 종가 | 등락 | 기준 | 한 줄 메모 | 출처 |
|---|---|---|---|---|---|
| 애플 (AAPL) | $351.91 | −0.25% | 11-17 종가 | 내부 업데이트로 인한 서비스 전반(Apple Pay 등) 장애가 발생해 복구 중이고, 프랑스에서 계획적 노후화 혐의로 2027년 6월 파리에서 재판을 받는다 | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/) |
| 마이크로소프트 (MSFT) | $506.24 | −2.27% | 11-17 종가 | Ignite 콘퍼런스에서 신규 AI 모델 7종을 공개했으나, 빌 애크먼의 퍼싱스퀘어가 지분 35%를 매도했다는 소식에 주가가 밀렸음 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/) |
| 엔비디아 (NVDA) | $155.46 | −0.44% | 11-17 종가 | 3분기 매출이 전년대비 103% 늘어 예상(1,091억달러)을 웃돌았고 4분기 가이던스도 컨센서스를 상회했으나, WSJ는 SEC가 사임 이후 회사를 조사 중이라고 보도했음(실적은 장 마감 후 발표돼 정규장 종가에는 미반영) | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) |
| AMD | $503.41 | −0.17% | 11-17 종가 | 전날 반도체주 급락 이후 소폭 반등하며 거래를 시작했다는 보도가 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/) |
| 알파벳 (GOOGL) | $280.20 | −1.24% | 11-17 종가 | 캘리포니아 DMV가 "급박한 위험" 판정을 내려 웨이모 로보택시의 고속도로 운행이 전국적으로 중단됐고, UBS는 투자의견을 하향했음 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) |
| 테슬라 (TSLA) | $380.11 | +0.10% | 11-17 종가 | 사이버캡 충전 문제·사고 8건 보고 등 우려가 있었으나, 고령층 수요 증가 소식도 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) |
| 스페이스X (SPCX) | $141.70 | +3.16% | 11-17 종가 | 엔비디아가 3분기에 스페이스X 지분을 추가 매입한 것으로 나타났고, 캔터피츠제럴드는 740억달러 컴퓨팅 계약·스타십 15차 시험 성공을 근거로 긍정적으로 평가했음 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) |
| 삼성전자 | 190,300원 | −3.30% | 11-17 종가 | - | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data) |
| SK하이닉스 | 1,098,000원 | −1.96% | 11-17 종가 | - | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data) |

<sub>개별 종목 등락률은 11-16 종가(애플 $352.78·마이크로소프트 $517.99·엔비디아 $156.14·AMD $504.28·알파벳 $283.72·테슬라 $379.74·스페이스X $137.36·삼성전자 196,800원·SK하이닉스 1,120,000원, [2026-11-17 브리핑](2026-11-17-NewsBriefing.md) 참고)와 위 11-17 종가를 `python3 -c`로 직접 계산. 엔비디아 실적 발표 후 시간외 거래에서 주가는 161.20달러(+3.69%, 11-17 17:41 EST 기준)까지 올랐으나 정규장 종가(155.46달러)에는 반영되지 않음([stockanalysis.com](https://stockanalysis.com/stocks/nvda/)). 나스닥 Top3 순위는 조회 시각 기준(시총 애플 5.11T·마이크로소프트 3.76T·엔비디아 3.75T)이며 종가 기준일 표기는 페이지에 없음. 마이크로소프트는 watchlist 3번과 중복돼 별도 행을 추가하지 않음.</sub>

## 4. 주요 뉴스 (최대 5건)
1. **엔비디아 3분기 실적 호조 — 매출 103%↑·4분기 가이던스도 컨센서스 상회** — 엔비디아는 11-17(현지) 장 마감 후 3분기 매출 1,158억달러(전년대비 +103%, 애널리스트 예상 1,091억달러 상회)를 발표했다. 4분기 매출 가이던스는 1,260억~1,340억달러로 컨센서스(약 1,250억달러)를 웃돌았고, 임시 CEO 콜레트 크레스는 FY28 매출 성장 전망을 기존 70%대에서 75% 이상으로 상향했다. 콘퍼런스콜에서 회사는 젠슨 황 전 CEO의 사임에 대한 질문은 받지 않겠다며 복귀 계획이 없다고 밝혔다. ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097), 11-17 16:26 ET 입력)
2. **美 3대 지수 동반 하락 — 다우 3개월 신저가, S&P500 7월來 최저 마감** — 11-17(현지) 다우존스(−1.64%, 50,759.42)가 3개월 신저가를 기록했고 S&P500(−1.02%, 7,340.89)은 7월 이후 최저로 마감했다. 금융·유틸리티·헬스케어 업종의 손실이 하락을 주도했고, 엔비디아 실적 발표를 앞둔 경계감과 AI 투자 위축 우려가 투자심리를 눌렀다. ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-lower-at-close-of-trade-dow-jones-industrial-average-down-164-5034091), 11-17 16:30 ET 입력)
3. **WSJ: SEC, 황 전 CEO 사임 이후 엔비디아 조사 중** — 월스트리트저널은 11-17(현지) 사안을 아는 사람들을 인용해 미국 증권거래위원회(SEC)가 젠슨 황의 CEO 사임과 관련해 엔비디아를 조사하고 있다고 보도했다. SEC는 조사를 공식 확인하지 않았다. ([investing.com(WSJ 인용)](https://www.investing.com/news/stock-market-news/nvidia-facing-sec-probe-after-huangs-resignation-wsj-reports-5034040), 11-17 16:17 입력)
4. **코스피 9개월 반만에 5,000선 붕괴 — 외국인 1.443조원 순매도** — 11-17 코스피는 132.02포인트(2.59%) 내린 4,968.48로 마감해 2026-02-02 이후 처음으로 5,000선을 밑돌았다. 코스닥도 15.59포인트(2.34%) 내린 650.06으로 마감했다. 美 증시 하락과 엔비디아 실적 경계감, AI 투자 위축 우려, 美 상무부의 中 AI칩 원격접근 추가 차단 등 수출통제 확대 우려가 겹쳤다. 코스피에서 외국인이 1.443조원을 순매도했고 개인(4,261억원)·기관(5,393억원)은 순매수했다. ([머니투데이](https://www.mt.co.kr/stock/2026/11/17/2026111715442030493), 11-17 15:54 입력)
5. **美 의회, 중국向 고급 AI칩 판매 제한 입법 추진** — CNBC 보도에 따르면 초당적 미국 의원들이 중국에 대한 고급 AI칩 판매를 제한하는 내용을 국방수권법(NDAA)에 포함시키자고 주장하고 있다. 엔비디아 실적 발표를 앞두고 반도체 수출통제 강화 가능성이 다시 부각됐다. ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 CNBC 기사, 11-17)

## 5. 오늘 일정
- 오늘(KST)로 확인된 주요 경제지표 발표나 관심 종목(애플·마이크로소프트·엔비디아·AMD·알파벳·테슬라·스페이스X·삼성전자·SK하이닉스)의 실적·주주총회·배당 기준일 일정은 없다 (BEA·BLS·Fed·investing.com 경제 캘린더 확인, 11-18)
- 참고: FOMC(10월 27~28일 회의) 의사록은 오늘이 아니라 내일(11-19) 새벽 04:00 KST(현지 11-18 14:00 ET)에 공개될 예정 ([federalreserve.gov](https://www.federalreserve.gov/newsevents/2026-november.htm))
- 어제(11-17) 美 10월 소매판매는 +0.2%(MoM)로 예상(+0.1%)을 소폭 웃돌았다 — 오늘이 아닌 지난 지표로 참고용 ([investing.com](https://www.investing.com/economic-calendar/retail-sales-256))
- 국내·미국 증시 휴장 없음 ([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/))

## 6. 전망 (자체 판단)
**직전 전망 점검:** 직전 일일 브리핑([2026-11-17](2026-11-17-NewsBriefing.md))의 전망 13건(상승 우세 1건[스페이스X]·방향성 불분명 12건, 일일 밴드 ±0.5%, 기간 11-17~11-18)을 11-16→11-17 종가로 확인한 결과(값은 위 2·2-1·3번과 [2026-11-17 브리핑](2026-11-17-NewsBriefing.md) 참고) 적중 5건(애플 −0.25%·엔비디아 −0.44%·AMD −0.17%·테슬라 +0.10%는 모두 ±0.5% 밴드 안, 스페이스X +3.16%는 "상승 우세"와 일치), 빗나감 8건(KOSPI −2.59%·KOSDAQ −2.34%·S&P500 −1.03%·NASDAQ −0.74%·마이크로소프트 −2.27%·알파벳 −1.24%·삼성전자 −3.30%·SK하이닉스 −1.96%는 모두 ±0.5% 밴드를 벗어남), 판단 보류 0건. 美 지수 급락·AI 투자 위축 우려·中 수출통제 확대 우려가 겹치며 지수와 대형 기술주·반도체 대형주는 예상보다 큰 하락폭을 기록했다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 11-18~11-19 | 상승: 엔비디아 3분기 매출이 전년대비 103% 늘어 예상을 웃돌았고 4분기 가이던스·FY28 성장전망(75%+)도 상향돼 AI 반도체 수요 전망이 유지됐다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097))<br>하락: 다우존스가 3개월 신저가(−1.64%)·S&P500이 7월來 최저로 마감했고, 코스피는 AI 투자 위축 우려·中 AI칩 수출통제 확대 속에 9개월 반만에 5,000선이 깨지며 외국인이 1.443조원을 순매도했다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/17/2026111715442030493)) | FOMC 의사록(11-19 새벽 공개 예정)과 반도체주의 엔비디아 실적 반응에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 방향성 불분명 | 11-18~11-19 | 상승: 엔비디아 실적 호조로 AI 반도체 수요 전망이 유지됐고, 코스닥에서는 개인이 1,155억원을 순매수했다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/17/2026111715442030493))<br>하락: 코스닥은 AI 투자 위축 우려 속에 2.34% 내렸고 외국인(896억원)·기관(251억원)이 순매도했다 (같은 출처) | FOMC 의사록·반도체주 반응에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| S&P 500 | 방향성 불분명 | 11-18~11-19 | 상승: 엔비디아 3분기 매출이 예상을 103% 웃돌았고 4분기 가이던스도 컨센서스를 상회했다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097))<br>하락: 다우존스가 3개월 신저가, S&P500이 7월來 최저로 마감했고 금융·유틸리티·헬스케어 업종 약세가 주도했다. WSJ는 SEC가 엔비디아를 조사 중이라고 보도했다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-lower-at-close-of-trade-dow-jones-industrial-average-down-164-5034091)) | FOMC 의사록 공개(11-19 새벽)에 따른 금리 전망 변화가 변동성을 키울 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| NASDAQ | 방향성 불분명 | 11-18~11-19 | 상승: 엔비디아 실적 호조(매출 +103%, 가이던스 상회)로 AI 반도체 수요 우려가 완화됐고 시간외 거래에서 주가가 3.69% 올랐다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/))<br>하락: 나스닥 시총 2위 마이크로소프트가 애크먼의 퍼싱스퀘어 지분 매도 소식에 2.27% 내렸고, AI 투자 위축 우려가 기술주 전반에 부담을 줬다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/)) | FOMC 의사록과 엔비디아의 시간외 반응이 정규장에 어떻게 반영될지 지켜봐야 한다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 애플 (AAPL) | 방향성 불분명 | 11-18~11-19 | 상승: 애플은 대규모 자사주 매입 여력이 있는 현금 부자 기업으로 꼽혔다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/) 관련 TipRanks 기사, 11-17)<br>하락: 내부 업데이트로 인한 서비스 전반 장애가 발생해 복구 중이고, 프랑스에서 계획적 노후화 혐의로 2027년 6월 재판을 받는다 (같은 출처 관련 Reuters·TechXplore 기사, 11-17) | 서비스 장애가 단기에 해결되면 영향이 제한적일 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 마이크로소프트 (MSFT) | 방향성 불분명 | 11-18~11-19 | 상승: Ignite 콘퍼런스에서 신규 AI 모델 7종과 Copilot 관련 신제품을 다수 공개했다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/) 관련 TipRanks·GeekWire 기사, 11-17)<br>하락: 빌 애크먼의 퍼싱스퀘어가 마이크로소프트 지분 35%를 매도했다는 소식에 주가가 2.27% 내렸다 (같은 출처 관련 TipRanks 기사, 11-17) | AI 투자심리가 전반적으로 회복되면 신제품 발표가 재평가될 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 엔비디아 (NVDA) | 상승 우세 | 11-18~11-19 | 1. 3분기 매출이 전년대비 103% 늘어 애널리스트 예상(1,091억달러)을 웃돌았고, 4분기 매출 가이던스(1,260억~1,340억달러)도 컨센서스(약 1,250억달러)를 상회했다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097), 11-17)<br>2. 실적 발표 후 시간외 거래에서 주가가 3.69% 올라 161.20달러를 기록했다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/), 11-17) | WSJ는 SEC가 황 전 CEO 사임 이후 회사를 조사하고 있다고 보도했고, 가이던스에는 中 데이터센터 칩 매출이 포함되지 않아 불확실성이 남아 있다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-facing-sec-probe-after-huangs-resignation-wsj-reports-5034040)) | 보통 — 독립적 상승 근거 2개(실적·가이던스 상회, 시간외 반응)가 있으나 SEC 조사 보도라는 반대 요인이 있음 |
| AMD | 방향성 불분명 | 11-18~11-19 | 상승: 전날 반도체주 급락 이후 소폭 반등하며 거래를 시작했다는 보도가 있었고, 엔비디아의 3분기 실적 호조가 반도체 업종 전반에 반사효과를 줄 수 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 Invezz 기사, 11-17)<br>하락: 엔비디아는 콘퍼런스콜에서 4분기 가이던스에 中 데이터센터 칩 매출을 포함하지 않았다고 밝혀 AI 반도체 수요의 中 관련 불확실성이 반도체 업종 전반에 남아있다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097)) | AI 투자 위축 우려가 추가로 부각되면 반도체 업종 전반 투자심리가 다시 악화될 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 알파벳 (GOOGL) | 방향성 불분명 | 11-18~11-19 | 상승: 앤트로픽 상장을 앞두고 아마존·구글 등이 보유한 지분 가치가 재평가될 수 있다는 분석이 나왔다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 TechCrunch 기사, 11-17)<br>하락: 캘리포니아 DMV가 "급박한 위험" 판정을 내려 웨이모 로보택시의 고속도로 운행이 전국적으로 중단됐고, UBS는 투자의견을 하향했다 (같은 출처 관련 TechCrunch·TheFly 기사, 11-17) | 전반적 기술주 반등이 나타나면 동반 상승할 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 테슬라 (TSLA) | 방향성 불분명 | 11-18~11-19 | 상승: 고령층 사이에서 테슬라 수요가 늘고 있다는 보도가 나왔다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 TipRanks 기사, 11-17)<br>하락: 사이버캡 충전 문제와 사고 8건이 보고됐고, Barclays는 사이버캡의 실질 시장 규모가 제한적이라고 평가했다 (같은 출처 관련 TipRanks·TheFly 기사, 11-17) | 테슬라-스페이스X 합병 협상 기대가 다시 부각되면 투자심리가 개선될 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 스페이스X (SPCX) | 상승 우세 | 11-18~11-19 | 1. 엔비디아가 3분기에 스페이스X 지분을 추가 매입한 것으로 나타났다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/) 관련 MarketWatch 기사, 11-17)<br>2. 캔터피츠제럴드는 740억달러 규모 컴퓨팅 계약과 스타십 15차 시험 성공을 근거로 2027년 추정치보다 높은 상승 여지가 있다고 평가했다 (같은 출처 관련 TheFly 기사, 11-17) | 테슬라와의 합병은 아직 최종 합의 전이고, AI 투자심리 위축이 재부각되면 투자심리가 흔들릴 수 있다 | 보통 — 독립적 상승 근거 2개(엔비디아 지분 확대, 애널리스트 긍정 평가)가 있으나 합병 불확실성 등 반대 요인이 있음 |
| 삼성전자 | 방향성 불분명 | 11-18~11-19 | 상승: 엔비디아의 3분기 실적 호조와 4분기 가이던스 상회로 AI 서버·메모리 수요 기대가 유지됐다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097))<br>하락: 코스피가 9개월 반만에 5,000선을 밑돌았고 AI 투자 위축 우려·中 AI칩 수출통제 확대 속에 삼성전자는 3.30% 내렸다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/17/2026111715442030493)) | FOMC 의사록·美 반도체 추가 규제 여부에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 방향성 불분명 | 11-18~11-19 | 상승: 엔비디아의 3분기 실적에서 공급 약정이 2,790억→3,900억달러, 클라우드 백로그가 2조→2.5조달러로 늘었다고 밝혀 HBM 등 메모리 수요 전망이 유지됐다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097))<br>하락: 반도체 대형주 전반이 AI 투자 위축 우려·中 수출통제 확대 속에 동반 하락했고, SK하이닉스는 1.96% 내렸다 ([kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data)) | 엔비디아 실적에서 HBM 수요가 재확인된 만큼, 다음 공급사 실적·수주 소식에 투자심리가 반응할 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
