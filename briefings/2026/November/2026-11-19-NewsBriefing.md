# 📈 2026-11-19 (목) 아침 브리핑

> 생성 07:50 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한눈에 (3줄)
- 전 거래일(11-18) 코스피·코스닥은 엔비디아 실적 훈풍에 반도체株가 반등하며 하루 만에 5,000선을 되찾았다: 코스피 +1.99%(5,067.44)·코스닥 +1.96%(662.81), 관심 종목 중에서는 SK하이닉스(+4.19%)·삼성전자(+2.31%)가 가장 많이 올랐으나 외국인 순매도는 이어졌다.
- 美 지수는 반도체주 강세(AMD +5.31%)에 나스닥이 +0.42% 오른 반면 S&P500은 −0.23% 소폭 내렸다. 엔비디아는 3분기 호실적·가이던스 상향에도 SEC 조사 보도·CEO 복귀 불확실성 속에 −2.89% 내렸다.
- FOMC 10월 회의록이 오늘 새벽(KST) 공개돼 "대부분 위원이 추가 금리 인상에 공감한다"는 내용이 확인됐다. 오늘은 수능일로 국내 증시가 1시간 늦게 열리고(10:00~16:30), 美 신규 실업수당 청구건수가 밤에 발표된다.

## 2. 지수
| 지수 | 종가 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| KOSPI | 5,067.44 | +1.99% | 11-18 종가 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 662.81 | +1.96% | 11-18 종가 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 7,323.63 | −0.23% | 11-18 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 24,429.88 | +0.42% | 11-18 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |

<sub>국내·미국 모두 전 거래일은 11-18(수). 11-18·11-19 국내·미국 증시 휴장 없음([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/), 둘 다 11-18 조회). 등락률은 11-17 종가(KOSPI 4,968.48·KOSDAQ 650.06·S&P500 7,340.53·NASDAQ 24,328.38, [2026-11-18 브리핑](2026-11-18-NewsBriefing.md) 참고)와 위 11-18 종가를 `python3 -c`로 직접 계산. KOSPI·KOSDAQ 등락률(+1.99%·+1.96%)은 kr.investing.com 히스토리 표에 함께 표시된 변동률과 일치. S&P500·NASDAQ 등락률(−0.23%·+0.42%)도 Yahoo Finance 히스토리 표의 전일 대비 수치와 일치.</sub>

## 2-1. 현금·환율
| 항목 | 값 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| 달러 인덱스 (DXY) | 103.78 | +0.28% | 11-18 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) |
| USD/JPY | 159.42 | +0.08% | 11-18 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-18?from=USD&to=JPY,KRW) |
| USD/KRW | 1,332.33 | −0.29% | 11-18 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-18?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 835.74 | −0.37% | 11-18 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-18?from=JPY&to=KRW) |

<sub>등락은 11-17 값(USD/JPY 159.30·USD/KRW 1,336.21 [Frankfurter 11-17](https://api.frankfurter.dev/v1/2026-11-17?from=USD&to=JPY,KRW), JPY/KRW 838.82 [JPY 기준](https://api.frankfurter.dev/v1/2026-11-17?from=JPY&to=KRW), 모두 [2026-11-18 브리핑](2026-11-18-NewsBriefing.md) 참고)과 비교해 `python3 -c`로 계산. DXY는 Yahoo Finance 히스토리 표 11-17→11-18 종가(103.49→103.78)로 계산(해당 페이지는 조회 시각 기준 "Market Open"으로 표시돼 있어 11-18 종가가 장중 갱신될 수 있음). 교차 확인한 [investing.com](https://www.investing.com/indices/usdollar-historical-data)에서는 11-17 103.49→11-18 103.79로 집계돼 소수점 수준의 불일치가 있음(등락률은 Yahoo Finance 기준 계산).</sub>

## 3. 관심 종목
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 애플 · 2. 마이크로소프트 · 3. 엔비디아 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))

| 종목 | 종가 | 등락 | 기준 | 한 줄 메모 | 출처 |
|---|---|---|---|---|---|
| 애플 (AAPL) | $352.45 | +0.15% | 11-18 종가 | 전날 발생한 서비스 전반(iCloud·App Store·Apple Pay 등) 장애 복구가 보도됐고, CNBC는 밸류에이션이 역사적으로 높다며 헤지를 고려할 때라고 분석했음 | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/) |
| 마이크로소프트 (MSFT) | $508.29 | +0.40% | 11-18 종가 | Ignite 콘퍼런스 발표 효과가 이어졌으나, 빌 애크먼의 퍼싱스퀘어가 지분 약 200만 주(약 35%)를 매도했다는 소식도 있었음(배당락일은 오늘 11-19) | [stockanalysis.com](https://stockanalysis.com/stocks/msft/) |
| 엔비디아 (NVDA) | $150.96 | −2.89% | 11-18 종가 | 3분기 호실적·4분기 가이던스 상회에도 주가는 내렸고, 임시 CEO 콜레트 크레스는 복귀 질문을 받지 않겠다고 밝혔으며 정기 10-Q 보고서를 즉시 제출하지 않겠다고 언급해 주목받았음 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) |
| AMD | $530.14 | +5.31% | 11-18 종가 | 엔비디아 실적 호조의 반사효과로 반도체주가 동반 강세를 보이며 급등했음(마이크론·브로드컴도 동반 상승) | [stockanalysis.com](https://stockanalysis.com/stocks/amd/) |
| 알파벳 (GOOGL) | $282.44 | +0.80% | 11-18 종가 | 캘리포니아 DMV의 "급박한 위험" 판정으로 웨이모 로보택시의 美 전국 고속도로 운행이 중단됐고, 앤트로픽 IPO 공모가가 목표 범위를 웃돈 83달러로 확정돼 구글 보유 지분 가치가 주목받았음 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) |
| 테슬라 (TSLA) | $383.72 | +0.95% | 11-18 종가 | 건물 전력 공급 등 에너지 사업을 강조한 신제품 'Powercore'를 공개했으나, 사이버캡 충전 문제·사고 8건 보고 우려도 이어졌음 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) |
| 스페이스X (SPCX) | $143.50 | +1.27% | 11-18 종가 | 억만장자 Len Blavatnik이 약 50억달러 규모 지분을 보유한다는 보도가 있었고, 텍사스 데이터센터 허가 진행·무선 사업 확장 소식도 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) |
| 삼성전자 | 194,700원 | +2.31% | 11-18 종가 | - | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data) |
| SK하이닉스 | 1,144,000원 | +4.19% | 11-18 종가 | - | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data) |

<sub>개별 종목 등락률은 11-17 종가(애플 $351.91·마이크로소프트 $506.24·엔비디아 $155.46·AMD $503.41·알파벳 $280.20·테슬라 $380.11·스페이스X $141.70·삼성전자 190,300원·SK하이닉스 1,098,000원, [2026-11-18 브리핑](2026-11-18-NewsBriefing.md) 참고)와 위 11-18 종가를 `python3 -c`로 직접 계산해 각 출처 페이지의 표시 등락률과 일치함을 확인. 나스닥 Top3 순위는 조회 시각 기준(애플 5.12T·마이크로소프트 3.77T·엔비디아 3.65T)이며 종가 기준일 표기는 페이지에 없음. 마이크로소프트·엔비디아는 watchlist 3번과 중복돼 별도 행을 추가하지 않음.</sub>

## 4. 주요 뉴스 (최대 5건)
1. **코스피·코스닥, 하루 만에 5,000·650선 회복 — 엔비디아 실적 훈풍에 반도체株 반등** — 11-18 코스피는 1.99% 오른 5,067.44, 코스닥은 1.96% 오른 662.81로 마감했다. 전날(11-17) 5,000선이 깨졌던 코스피가 하루 만에 다시 올라선 것으로, 엔비디아의 3분기 호실적과 기관 매수세가 반등을 이끌었다. 다만 외국인은 삼성전자·SK하이닉스를 포함해 순매도를 이어갔다. ([뉴스핌](https://www.newspim.com/news/view/20261118001065), 11-18)
2. **美 반도체주 동반 강세 — AMD 5%대 급등, 엔비디아는 호실적에도 하락** — 엔비디아의 3분기 매출이 전년대비 103% 늘어 예상을 웃돌았다는 소식에 AMD·마이크론·브로드컴 등 반도체주가 11-18 동반 강세를 보이며 나스닥을 끌어올렸다. 반면 엔비디아 자체 주가는 SEC 조사 보도와 CEO 공석 관련 불확실성 속에 2.89% 내렸다. ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 TipRanks 기사, 11-18)
3. **FOMC 10월 회의록 공개 — "대부분 위원, 추가 금리 인상 필요"** — 연준은 10월 27~28일 회의에서 기준금리를 3.75~4.00%로 동결했으나(10대2, 리사 쿡·베스 해머크 이사가 0.25%p 인상에 찬성해 반대표를 던짐) 11-18(현지) 공개된 회의록에서 "거의 모든" 위원이 경제가 예상대로 흐르면 추가 인상이 필요하다는 데 공감했다고 밝혔다. 일부 위원은 인플레이션이 불리하게 나오면 0.50%p 인상도 검토해야 한다고 주장했다. ([investing.com(Reuters)](https://www.investing.com/news/economy-news/fed-policymakers-focused-on-inflation-risks-in-october-with-some-seeing-need-for-bigger-rate-hike-5036863), 11-18 14:05 입력)
4. **구글 웨이모 로보택시, 美 전국 고속도로 운행 중단** — 캘리포니아 DMV가 웨이모 로보택시에 "급박한 위험(imminent hazard)" 판정을 내리면서 웨이모는 美 전역에서 고속도로 로보택시 운행을 중단했다. ([stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 TechCrunch 기사, 11-18)
5. **앤트로픽 IPO 공모가 83달러로 확정 — 목표 범위 상회** — 앤트로픽 기업공개(IPO) 공모가가 목표 범위(70~78달러)를 웃도는 83달러로 확정됐다. 나스닥에서 ANT 티커로 거래될 예정이며, 아마존과 구글이 합산 28.4%의 비의결권 지분을 보유하고 있어 상장 후 지분 가치가 주목받고 있다. ([stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 TechCrunch 기사, 11-18)

## 5. 오늘 일정
- 오늘(11-19)은 2027학년도 대학수학능력시험(수능)일로, 한국거래소 정규장이 평소보다 1시간 늦게 열리고 늦게 닫힌다(10:00~16:30). 대체거래소 프리마켓(평소 08:00)은 열리지 않고, 애프터마켓도 1시간 늦은 17:00에 시작한다 ([스마트투데이](https://www.smarttoday.co.kr/ko-kr/articles/113471), 11-05 보도 — 원문은 클라우드 네트워크 허용 목록 밖이라 WebSearch 결과로만 확인, 열람 불가)
- FOMC 10월(27~28일) 회의록은 오늘 새벽 04:00 KST(현지 11-18 14:00 ET)에 이미 공개됐다 ([federalreserve.gov](https://www.federalreserve.gov/monetarypolicy/files/fomcminutes20261028.pdf))
- 美 신규 실업수당 청구건수가 오늘 밤 22:30 KST(현지 11-19 08:30 ET) 발표된다. 컨센서스 19.8만 건, 직전치 20.0만 건 ([investing.com](https://www.investing.com/economic-calendar/initial-jobless-claims-294))
- 마이크로소프트(MSFT)의 배당(주당 $3.92, 수익률 0.77%) 배당락일이 오늘(11-19)이다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/))
- 애플·엔비디아·AMD·알파벳·테슬라·스페이스X·삼성전자·SK하이닉스의 실적 발표·주주총회 등 확인된 일정은 없다 (BEA·BLS·Fed·investing.com 경제 캘린더, 종목별 stockanalysis.com 확인, 11-18~19)
- 국내·미국 증시 휴장 없음 ([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/))

## 6. 전망 (자체 판단)
**직전 전망 점검:** 직전 일일 브리핑([2026-11-18](2026-11-18-NewsBriefing.md))의 전망 13건(상승 우세 2건[엔비디아·스페이스X]·방향성 불분명 11건, 일일 밴드 ±0.5%, 기간 11-18~11-19)을 11-17→11-18 종가로 확인한 결과(값은 위 2·2-1·3번과 [2026-11-18 브리핑](2026-11-18-NewsBriefing.md) 참고) 적중 5건(S&P500 −0.23%·NASDAQ +0.42%·애플 +0.15%·마이크로소프트 +0.40%는 모두 ±0.5% 밴드 안, 스페이스X +1.27%는 "상승 우세"와 일치), 빗나감 8건(KOSPI +1.99%·KOSDAQ +1.96%·AMD +5.31%·알파벳 +0.80%·테슬라 +0.95%·삼성전자 +2.31%·SK하이닉스 +4.19%는 ±0.5% 밴드를 벗어났고, 엔비디아는 "상승 우세" 예상과 반대로 −2.89% 하락), 판단 보류 0건. 엔비디아 실적 발표를 계기로 반도체주·코스피·코스닥이 예상보다 큰 폭으로 반등한 반면, 엔비디아 자체는 SEC 조사·CEO 공석 우려에 눌려 예상과 반대로 하락했다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 11-19~11-20 | 상승: 엔비디아 실적 호조를 계기로 기관 매수세가 유입돼 코스피가 하루 만에 5,000선을 회복했다 ([뉴스핌](https://www.newspim.com/news/view/20261118001065))<br>하락: 외국인은 삼성전자·SK하이닉스 등을 포함해 순매도를 이어갔고, FOMC 10월 회의록은 "거의 모든" 위원이 추가 금리 인상에 공감한다고 밝혔다 ([investing.com](https://www.investing.com/news/economy-news/fed-policymakers-focused-on-inflation-risks-in-october-with-some-seeing-need-for-bigger-rate-hike-5036863)) | 오늘은 수능일로 거래시간이 1시간 지연돼(10:00~16:30) 평소보다 유동성·변동성 패턴이 달라질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 방향성 불분명 | 11-19~11-20 | 상승: 반도체 업황 기대에 코스닥도 11-18 1.96% 올랐다 ([kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data))<br>하락: FOMC 의사록의 추가 인상 시사와 외국인 수급 둔화가 부담 요인이다 ([investing.com](https://www.investing.com/news/economy-news/fed-policymakers-focused-on-inflation-risks-in-october-with-some-seeing-need-for-bigger-rate-hike-5036863)) | 수능일 거래시간 지연으로 평소와 다른 수급 패턴이 나타날 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| S&P 500 | 방향성 불분명 | 11-19~11-20 | 상승: 반도체주 강세(AMD +5.31%)가 지수를 지지했다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/))<br>하락: FOMC 10월 회의록에서 "거의 모든" 위원이 추가 금리 인상에 공감했다고 밝혀 긴축 장기화 우려가 부각됐다 ([investing.com](https://www.investing.com/news/economy-news/fed-policymakers-focused-on-inflation-risks-in-october-with-some-seeing-need-for-bigger-rate-hike-5036863)) | 엔비디아의 실적 자체(매출 +103%, 가이던스 상회)는 AI 수요 전망을 지지해 하락 압력을 상쇄할 수 있다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097)) | 낮음 — 상승·하락 근거가 팽팽함 |
| NASDAQ | 방향성 불분명 | 11-19~11-20 | 상승: 엔비디아 실적 호조의 반사효과로 AMD(+5.31%)·마이크론·브로드컴 등 반도체주가 동반 강세를 보이며 나스닥을 끌어올렸다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/))<br>하락: 나스닥 시총 1위 엔비디아 자체는 SEC 조사 보도·CEO 공석 우려 속에 2.89% 내렸다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/)) | FOMC 의사록의 추가 인상 시사가 성장주 밸류에이션에 부담이 될 수 있다 ([investing.com](https://www.investing.com/news/economy-news/fed-policymakers-focused-on-inflation-risks-in-october-with-some-seeing-need-for-bigger-rate-hike-5036863)) | 낮음 — 상승·하락 근거가 팽팽함 |
| 애플 (AAPL) | 판단 보류 | 11-19~11-20 | 서비스 전반(iCloud·App Store·Apple Pay) 장애 복구 소식과 CNBC의 밸류에이션 부담·헤지 권고 분석을 확인했으나, 둘 다 방향과 직접 연결되는 실적·수급 사실은 아니어서(장애는 복구 중이고 헤지 권고는 의견 기사) 방향 판단의 근거로 쓰기 어렵다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/)) | 판단 보류 — 방향성 근거가 확인되지 않아 반대 요인도 특정하지 않음 | 해당 없음 — 판단 보류 |
| 마이크로소프트 (MSFT) | 방향성 불분명 | 11-19~11-20 | 상승: Ignite 콘퍼런스에서 신규 AI 모델 7종을 공개했고, The Information에 따르면 ByteDance와 약 5억달러 규모 클라우드 계약을 추진 중이다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/))<br>하락: 빌 애크먼의 퍼싱스퀘어가 지분 약 35%를 매도한 데 더해, 오늘(11-19)이 배당(주당 $3.92) 배당락일이라 기계적 가격 조정 요인이 있다 (같은 출처) | AI 수익화에 대한 Citi의 긍정적 평가는 하락 압력을 상쇄할 수 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/)) | 낮음 — 상승·하락 근거가 팽팽함 |
| 엔비디아 (NVDA) | 방향성 불분명 | 11-19~11-20 | 상승: 3분기 매출이 전년대비 103% 늘어 예상을 웃돌았고 4분기 가이던스도 컨센서스를 상회했다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097))<br>하락: 임시 CEO 콜레트 크레스가 정기 10-Q 보고서를 즉시 제출하지 않겠다고 밝혀 공시 불확실성이 부각됐고, WSJ 보도에 따른 SEC 조사 우려도 남아 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/)) | - | 낮음 — 상승·하락 근거가 팽팽함 |
| AMD | 상승 우세 | 11-19~11-20 | 1. 엔비디아의 3분기 실적 호조(매출 +103%, 가이던스 상회)에 반사효과를 받아 11-18 AMD·마이크론·브로드컴 등 반도체주가 동반 강세를 보였다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/))<br>2. Invezz·TipRanks는 프리마켓에서도 추가 상승세가 이어졌다고 전했다 (같은 출처) | 11-18 하루에만 5.31% 오른 만큼 차익 매물에 따른 되돌림 가능성이 있다 (위 3번 표 참고) | 보통 — 독립적 상승 근거 2개(엔비디아 실적 반사효과, 프리마켓 추가 상승)가 있으나 단기 급등에 따른 되돌림 위험이 있음 |
| 알파벳 (GOOGL) | 방향성 불분명 | 11-19~11-20 | 상승: 앤트로픽 IPO 공모가가 목표 범위를 웃도는 83달러로 확정돼 구글이 보유한 비의결권 지분(아마존과 합산 28.4%) 가치가 재평가될 수 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/))<br>하락: 캘리포니아 DMV가 "급박한 위험" 판정을 내려 웨이모 로보택시의 美 전국 고속도로 운행이 중단됐다 (같은 출처) | UBS가 중립(Neutral) 의견으로 커버리지를 개시한 점은 중립적 요인이라 방향성을 강하게 좌우하지 않는다 (같은 출처) | 낮음 — 상승·하락 근거가 팽팽함 |
| 테슬라 (TSLA) | 방향성 불분명 | 11-19~11-20 | 상승: 건물 전력 공급을 강조한 신제품 'Powercore'를 공개했다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 TipRanks 기사)<br>하락: 사이버캡 충전 문제와 사고 8건 보고가 이어지고 있다 (같은 출처) | 에너지 사업 확장이 시장에서 긍정적으로 재평가되면 우려를 상쇄할 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 스페이스X (SPCX) | 상승 우세 | 11-19~11-20 | 1. Bloomberg 보도에 따르면 억만장자 Len Blavatnik이 약 50억달러 규모의 스페이스X 지분을 보유하고 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/) 관련 Bloomberg 기사)<br>2. 텍사스의 데이터센터 허가 진행과 무선 사업 확장 소식이 전해졌다 (같은 출처 관련 TipRanks·Invezz 기사) | TipRanks에 따르면 이번 주 약 40억달러 규모 채권 발행이 준비되고 있어 레버리지·희석 우려가 있다 (같은 출처) | 보통 — 독립적 상승 근거 2개(대주주 지분 보도, 사업 확장 소식)가 있으나 대규모 채권 발행이라는 반대 요인이 있음 |
| 삼성전자 | 방향성 불분명 | 11-19~11-20 | 상승: 엔비디아의 3분기 실적 호조로 AI 서버·메모리 수요 기대가 유지되며 11-18 삼성전자는 2.31% 올랐다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097))<br>하락: 외국인은 11-18에도 순매도를 이어갔다 ([뉴스핌](https://www.newspim.com/news/view/20261118001065)) | 오늘은 수능일로 거래시간이 1시간 지연돼 평소와 다른 수급 흐름이 나타날 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 방향성 불분명 | 11-19~11-20 | 상승: 엔비디아가 공급 약정·클라우드 백로그 확대를 밝혀 HBM 등 메모리 수요 전망이 유지됐고, SK하이닉스는 11-18 4.19% 올랐다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097))<br>하락: 반도체 대형주 전반이 하루 만에 큰 폭으로 오른 만큼 차익 매물 출회 가능성이 있다 (위 3번 표 참고) | - | 낮음 — 상승·하락 근거가 팽팽함 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
