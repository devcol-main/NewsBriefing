# 📈 2026-11-17 (화) 아침 브리핑

> 생성 07:55 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한눈에 (3줄)
- 전 거래일(11-16) 국내외 지수가 동반 급락했다: 코스피 −3.59%·코스닥 −4.86%·S&P500 −1.92%·나스닥 −2.49%로, 美 10년물 국채금리 상승과 엔비디아 실적(현지 11-17 장 마감 후)을 앞둔 경계감이 맞물렸다.
- 관심 종목 중에서는 SK하이닉스(−7.89%)가 가장 많이 내렸고 AMD(−5.58%)·삼성전자(−4.47%)·엔비디아(−4.12%)·알파벳(−4.07%) 등 반도체·AI 관련주가 전반적으로 약세를 보였다.
- 오늘(KST) 22:30 美 10월 소매판매 발표가 예정돼 있고, 엔비디아 3분기 실적은 내일(11-18) 새벽 발표될 예정이다.

## 2. 지수
| 지수 | 종가 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| KOSPI | 5,100.50 | −3.59% | 11-16 종가 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 665.65 | −4.86% | 11-16 종가 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 7,416.59 | −1.92% | 11-16 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 24,509.76 | −2.49% | 11-16 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |

<sub>국내·미국 모두 전 거래일은 11-16(월). 11-16·11-17 국내·미국 증시 휴장 없음([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/), 둘 다 11-17 조회). 11-14(토)·11-15(일)은 주말로 거래 없음. 등락률은 11-13 종가(KOSPI 5,290.53·KOSDAQ 699.66·S&P500 7,561.67·NASDAQ 25,136.27, [2026-11-16 브리핑](2026-11-16-NewsBriefing.md) 참고)와 위 11-16 종가를 `python3 -c`로 직접 계산. KOSDAQ 등락률(−4.86%)은 kr.investing.com 히스토리 표에 함께 표시된 변동률과 일치. 나스닥 종합(−2.49%)과 별도로, Bloomberg·Yahoo Finance(24/7 Wall St.) 보도는 나스닥100 기준 −2.7%로 더 좁은 지수 구성상 차이를 보임([Yahoo Finance](https://finance.yahoo.com/markets/stocks/articles/stock-market-today-nasdaq-100-145810375.html), 11-16).</sub>

## 2-1. 현금·환율
| 항목 | 값 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| 달러 인덱스 (DXY) | 103.58 | +0.16% | 11-16 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) |
| USD/JPY | 159.60 | −0.25% | 11-16 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-16?from=USD&to=JPY,KRW) |
| USD/KRW | 1,334.87 | −0.17% | 11-16 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-16?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 836.40 | +0.08% | 11-16 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-16?from=JPY&to=KRW) |

<sub>등락은 11-13 값(DXY 103.41 [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/), USD/JPY 160.00·USD/KRW 1,337.13 [Frankfurter 11-13](https://api.frankfurter.dev/v1/2026-11-13?from=USD&to=JPY,KRW), JPY/KRW 835.72 [JPY 기준](https://api.frankfurter.dev/v1/2026-11-13?from=JPY&to=KRW))과 비교해 `python3 -c`로 계산.</sub>

## 3. 관심 종목
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 애플 · 2. 마이크로소프트 · 3. 엔비디아 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))

| 종목 | 종가 | 등락 | 기준 | 한 줄 메모 | 출처 |
|---|---|---|---|---|---|
| 애플 (AAPL) | $352.78 | −0.98% | 11-16 종가 | Apple 마케팅 담당 부사장 그렉 조스위악은 폴더블 아이폰 Duo 최적화 앱이 20만 개를 넘었고 짧은 기간 두 배로 늘었다고 밝혔음 | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/) |
| 마이크로소프트 (MSFT) | $517.99 | −1.12% | 11-16 종가 | 지난주 전 세계 70여개국에 영향을 준 아웃룩 장애의 사후 분석이 시작됐고, MS는 7월부터 배포한 수정 작업의 버그("thundering herds")가 원인이라고 밝혔음 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/) |
| 엔비디아 (NVDA) | $156.14 | −4.12% | 11-16 종가 | 이사회는 젠슨 황 전 CEO의 복귀를 검토하지 않고 있다고 보도됐고, 모건스탠리 등 애널리스트들은 실적 발표를 앞두고 목표가를 낮췄음 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) |
| AMD | $504.28 | −5.58% | 11-16 종가 | 엔비디아 실적을 앞두고 엔비디아가 AI 생태계 투자를 줄일지 우려가 커지며 마이크론 등과 함께 동반 하락했음 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/) |
| 알파벳 (GOOGL) | $283.72 | −4.07% | 11-16 종가 | 폴슨앤코·타이거글로벌이 3분기 13F 공시에서 알파벳 지분을 각각 정리·축소한 것으로 나타났음 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) |
| 테슬라 (TSLA) | $379.74 | −2.69% | 11-16 종가 | 테슬라는 베를린 인근 공장에 €30억을 투자해 Cybercab 생산을 늘린다고 밝혔으나 발표 당일 주가는 하락했음 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) |
| 스페이스X (SPCX) | $137.36 | −1.26% | 11-16 종가 | 美 공군이 ULA·Blue Origin 등과 국가안보 발사계약을 조정했다는 소식과 기술주 매도세가 겹쳤음 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) |
| 삼성전자 | 196,800원 | −4.47% | 11-16 종가 | - | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data) |
| SK하이닉스 | 1,120,000원 | −7.89% | 11-16 종가 | - | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data) |

<sub>개별 종목 등락률은 11-13 종가(애플 $356.27·마이크로소프트 $523.88·엔비디아 $162.85·AMD $534.06·알파벳 $295.77·테슬라 $390.22·스페이스X $139.11·삼성전자 206,000원·SK하이닉스 1,216,000원, [2026-11-16 브리핑](2026-11-16-NewsBriefing.md) 참고)와 위 11-16 종가를 `python3 -c`로 직접 계산. 나스닥 Top3 순위는 11-16 조회 시각 기준(시총 애플 5.13T·마이크로소프트 3.85T·엔비디아 3.77T)이며 종가 기준일 표기는 페이지에 없음.</sub>

## 4. 주요 뉴스 (최대 5건)
1. **미국 3대 지수 동반 급락 — 엔비디아 첫 실적(황 CEO 사임 후) 앞두고 투자심리 악화** — Yahoo Finance(24/7 Wall St.)는 엔비디아가 지난주 리더십 공백으로 12%대 급락한 데 이어 11-16에도 4%대 더 하락했고, 화요일(현지 11-17) 예정된 실적 발표가 임시 CEO 콜레트 크레스 체제의 첫 실적이라는 점이 투자자 불안을 키웠다고 전했다. ([Yahoo Finance](https://finance.yahoo.com/markets/stocks/articles/stock-market-today-nasdaq-100-145810375.html), 11-16)
2. **美 10년물 국채금리 5.15%로 상승 — 연준 매파적 발언에 12월 금리인상폭 논쟁** — 같은 기사는 美 10년물 국채금리가 지난 금요일(11-13) 5.15%로 마감해 11-06(4.86%)보다 올랐고, 연준 인사들이 인플레이션 대응이 더 필요하다고 언급하며 12월 금리 인상폭(0.25%p·0.5%p)을 두고 논쟁이 벌어지고 있다고 전했다. ([Yahoo Finance](https://finance.yahoo.com/markets/stocks/articles/stock-market-today-nasdaq-100-145810375.html), 11-16)
3. **반도체 업종 전반 약세 — 美 상무부, 중국의 AI칩 원격접근 우회로도 추가 차단** — stockanalysis.com이 전한 로이터 보도에 따르면 美 상무부가 중국 기업에 미국 칩 컴퓨팅 파워를 임대하는 해외 데이터센터에도 라이선스를 요구하도록 규정을 바꿨고, 마이크론·AMD 등 반도체주가 동반 하락했다. ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 로이터 기사, 11-16)
4. **엔비디아 이사회, 젠슨 황 전 CEO 복귀 검토 안 해 — 기관투자자는 지분 확대** — 13F 공시에서 Third Point가 엔비디아를 신규 매수하고 Tiger Global·Appaloosa도 비중을 늘린 것으로 나타난 가운데, 이사회는 황 전 CEO의 복귀를 검토하지 않고 있다고 보도됐다. ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 기사, 11-16)
5. **테슬라, 베를린 인근 공장에 €30억 투자 발표 — 그래도 주가는 하락** — 로이터 등은 테슬라가 Cybercab 생산 확대를 위해 베를린 인근 공장에 약 33억달러를 투자하며 2029년 생산 개시·장기적으로 연 최대 100만대를 목표로 한다고 보도했으나, 발표 이후에도 주가는 하락했다. ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 로이터 기사, 11-16)

## 5. 오늘 일정
- 22:30 美 10월 소매판매(MoM) 발표. 컨센서스 +0.2%, 직전치(9월) +0.8% ([investing.com](https://www.investing.com/economic-calendar/retail-sales-256))
- 엔비디아(NVDA) 3분기(FY2027) 실적 발표는 내일(11-18, 현지 11-17 17:00 ET) 콘퍼런스콜 예정 — 오늘로 확인된 일정 아님. CFO 콜레트 크레스의 서면자료는 06:20 KST(현지 16:20 ET) 먼저 공개될 예정 ([investing.com](https://www.investing.com/news/company-news/nvidia-schedules-q3-fiscal-2027-earnings-call-for-nov-17-93CH-4980909))
- 국내·미국 증시 휴장 없음 ([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/))
- 그 외 관심 종목(애플·마이크로소프트·AMD·알파벳·테슬라·스페이스X·삼성전자·SK하이닉스)은 오늘로 확인된 실적·주주총회·배당 기준일 일정이 없음

## 6. 전망 (자체 판단)
**직전 전망 점검:** 직전 일일 브리핑([2026-11-16](2026-11-16-NewsBriefing.md))의 전망 13건(전부 방향성 불분명, 일일 밴드 ±0.5%, 기간 11-16~11-17)을 11-13→11-16 종가로 확인한 결과(값은 위 2·2-1·3번과 [2026-11-16 브리핑](2026-11-16-NewsBriefing.md) 참고) 적중 0건, 빗나감 13건(KOSPI −3.59%·KOSDAQ −4.86%·S&P500 −1.92%·NASDAQ −2.49%·애플 −0.98%·엔비디아 −4.12%·마이크로소프트 −1.12%·AMD −5.58%·알파벳 −4.07%·테슬라 −2.69%·스페이스X −1.26%·삼성전자 −4.47%·SK하이닉스 −7.89% 모두 ±0.5% 밴드를 크게 벗어남), 판단 보류 0건. 엔비디아 실적 발표를 앞둔 경계감과 美 10년물 국채금리 급등(5.15%)이 겹치며 13건 전부가 예상보다 훨씬 큰 하락폭을 기록했다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 11-17~11-18 | 상승: 11월 1~10일 반도체 수출이 전년대비 331% 늘었다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/12/2026111215311553061))<br>하락: 美 10년물 국채금리가 5.15%(11-13 기준)로 11-06(4.86%)보다 올랐고 연준 매파적 발언이 겹치며 11-16 뉴욕증시가 급락했다 ([Yahoo Finance](https://finance.yahoo.com/markets/stocks/articles/stock-market-today-nasdaq-100-145810375.html), 11-16) | 美 10월 소매판매(오늘 22:30 KST)·내일 엔비디아 실적 결과에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 방향성 불분명 | 11-17~11-18 | 상승: 11월 1~10일 반도체 수출이 전년대비 331% 늘었다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/12/2026111215311553061))<br>하락: 반도체 대형주(SK하이닉스 −7.89%·삼성전자 −4.47%, 11-16 종가)가 美 국채금리 상승·엔비디아 실적 경계감 속 동반 급락했다 ([Yahoo Finance](https://finance.yahoo.com/markets/stocks/articles/stock-market-today-nasdaq-100-145810375.html), 11-16) | 美 소매판매·내일 엔비디아 실적 결과에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| S&P 500 | 방향성 불분명 | 11-17~11-18 | 상승: 애널리스트들은 LSEG 집계 기준 엔비디아 3분기 매출 92%·순이익 89% 증가를 예상하고 있다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-pe-falls-to-14year-low-but-ceo-exit-and-ai-worries-cloud-the-bargain-5023158))<br>하락: 10년물 국채금리가 5.15%로 상승했고 연준 인사들이 인플레이션 대응이 더 필요하다고 언급하며 12월 금리인상폭 논쟁이 불거졌다 ([Yahoo Finance](https://finance.yahoo.com/markets/stocks/articles/stock-market-today-nasdaq-100-145810375.html), 11-16) | 美 소매판매·내일 엔비디아 실적 결과에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| NASDAQ | 방향성 불분명 | 11-17~11-18 | 상승: 애널리스트들은 엔비디아 3분기 매출 92%·순이익 89% 증가(LSEG 집계)를 예상하고 있다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-pe-falls-to-14year-low-but-ceo-exit-and-ai-worries-cloud-the-bargain-5023158))<br>하락: 美 상무부가 중국 기업의 AI칩 원격접근 우회로까지 추가로 막기로 하면서 마이크론·AMD 등 반도체주가 동반 하락했다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 로이터 기사, 11-16) | 내일 엔비디아 실적과 美 소매판매 결과에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 애플 (AAPL) | 방향성 불분명 | 11-17~11-18 | 상승: 마케팅 담당 부사장 그렉 조스위악은 폴더블 아이폰 Duo 최적화 앱이 20만 개를 넘었고 짧은 기간 두 배로 늘었다고 밝혔다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/) 관련 TheFly 기사, 11-16)<br>하락: UBS는 아이폰 Duo의 공급 부족으로 배송이 1월 말로 밀린다고 평가했다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/) 관련 TipRanks 기사, 11-11) | 반도체·AI 투자심리 악화가 대형 기술주 전반에 번질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 엔비디아 (NVDA) | 방향성 불분명 | 11-17~11-18 | 상승: 이사회는 젠슨 황 전 CEO의 복귀를 검토하지 않고 있다고 보도됐고, Third Point·Tiger Global·Appaloosa 등 복수 기관이 13F에서 엔비디아 지분을 확대한 것으로 나타났다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 기사, 11-16)<br>하락: 모건스탠리 등 애널리스트들이 실적 발표를 앞두고 목표가를 낮췄고, 美 정부가 중국의 최고성능 AI칩 접근을 추가로 제한할 계획이라는 보도가 나왔다 (같은 출처, 11-16) | 내일(11-18) 실적에서 임시 CEO 크레스의 전망 발언이 긍정적이면 불확실성이 빠르게 해소될 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 마이크로소프트 (MSFT) | 방향성 불분명 | 11-17~11-18 | 상승: MS는 Copilot을 "업무용 OS"로 포지셔닝하는 전략을 추진하고 있다고 밝혔다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/) 관련 GeekWire 기사, 11-16)<br>하락: 지난주 70여개국에 영향을 준 아웃룩 장애의 사후 분석이 시작됐고, 7월부터 배포한 수정 작업의 버그가 원인으로 지목됐다 (같은 출처, 11-16) | 美 소매판매·내일 엔비디아 실적 결과에 따른 시장 전반 변동성 | 낮음 — 상승·하락 근거가 팽팽함 |
| AMD | 방향성 불분명 | 11-17~11-18 | 상승: AMD는 World Labs 인수를 완료해 Fei-Fei Li 박사가 chief scientist로 합류했고, TensorWave가 OpenAI와 450MW 이상 규모의 AMD 기반 AI 인프라 6년 계약을 맺었다고 밝혔다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/), 11-16)<br>하락: 엔비디아 실적을 앞두고 엔비디아가 AI 생태계 투자를 줄일지 우려가 커지며 마이크론 등과 함께 동반 하락했다 (같은 출처, 11-16) | 반도체 업종 전반의 불확실성(엔비디아 실적·中 규제)이 심화되면 투자심리가 다시 악화될 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 알파벳 (GOOGL) | 방향성 불분명 | 11-17~11-18 | 상승: 구글 Gemini 4 Carbon이 회계 AI 벤치마크에서 2위를 기록했다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 로이터·Business Wire 기사, 11-11~12)<br>하락: 폴슨앤코·타이거글로벌이 3분기 13F 공시에서 알파벳 지분을 각각 정리·축소한 것으로 나타났다 (같은 출처, 11-16) | 반도체·AI 투자심리가 흔들리면 대형 기술주 전반에 영향을 줄 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 테슬라 (TSLA) | 방향성 불분명 | 11-17~11-18 | 상승: 테슬라는 베를린 인근 공장에 €30억을 투자해 Cybercab 생산을 늘리고 장기적으로 연 최대 100만대를 목표로 한다고 밝혔다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 로이터 기사, 11-16)<br>하락: WSJ는 테슬라가 사이버트럭 생산을 종료하기로 했다고 보도했다 ([2026-11-16 브리핑](2026-11-16-NewsBriefing.md) 참고, 11-13) | 테슬라-스페이스X 합병 협상 관련 정치적 변수(의회 조사 예고 등)가 남아있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 스페이스X (SPCX) | 상승 우세 | 11-17~11-18 | 1. 스타십 15차 비행시험에서 발사대 메카질라의 로봇팔 포획에 처음 성공했고 웰스파고는 완전 재사용 기술의 주요 이정표라고 평가했다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/) 관련 TipRanks·MarketWatch 기사, 11-14)<br>2. 시티는 실적 발표를 앞두고 목표가를 상향하며 투자의견을 유지했다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/) 관련 TheFly 기사, 11-16) | 부스터 회수는 이번에도 중도 포기돼 완전 재사용 기술 입증까지 시간이 더 필요할 수 있고, 테슬라와의 합병도 아직 최종 합의 전이다 | 보통 — 독립적 상승 근거 2개(비행시험 성과, 애널리스트 목표가 상향)가 있으나 반대 요인(부스터 회수 실패·합병 불확실성)이 있음 |
| 삼성전자 | 방향성 불분명 | 11-17~11-18 | 상승: 신한투자증권 강진혁 연구원은 공급망을 다변화한 삼성전자가 엔비디아 리스크 속에서도 상대적으로 강했다고 평가했다 ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2171987))<br>하락: 美 상무부의 中 AI칩 원격접근 추가 차단 등 반도체 업종 전반에 부담을 주는 소식 속에 11-16 4.47% 내렸다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 로이터 기사, 11-16) | 美 소매판매·내일 엔비디아 실적 결과에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 방향성 불분명 | 11-17~11-18 | 상승: 100조원 규모 주주환원 계획과 역대 최대 3분기 실적 펀더멘털은 유효하다 ([2026-11-07 주간 요약](2026-11-07-NewsBriefing.md) 참고)<br>하락: 엔비디아의 핵심 HBM 공급사로 분류돼 리더십·실적 불확실성에 더 민감하다는 평가가 있었고, 11-16 7.89% 내렸다 ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2171987)) | 내일(11-18) 엔비디아 실적에서 HBM 수요가 재확인되면 투자심리가 반응할 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
