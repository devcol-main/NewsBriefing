# 📈 2026-11-23 (월) 아침 브리핑

> 생성 07:55 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한눈에 (3줄)
- 전 거래일(11-20) 美·韓 지수 모두 AI 버블 우려가 재점화되며 동반 급락했다: 코스피 −5.21%(4,869.96)·코스닥 −5.71%(645.68), S&P500 −3.70%·나스닥 −5.28%로 S&P500은 10월 고점 대비 10%대 조정 국면에 들어섰다.
- 반도체 대형주가 급락을 주도했다: 엔비디아는 SEC 회계조사 보도로 하루 14.01% 급락했고, AMD는 공매도 보고서·美 하원 외교위의 中向 AI칩 수출허가 신청 기록 공개로 13.25% 내렸다. 관심 종목 중에서는 삼성전자(−7.01%)·SK하이닉스(−5.92%)·스페이스X(−7.69%)·테슬라(−7.64%)도 큰 폭으로 하락했고, 애플(−1.90%)이 가장 선방했다.
- 오늘(11-23) 국내·미국 모두 확인된 주요 경제지표 발표나 관심 종목 실적 일정은 없다. 이번 주는 11-25(수) 美 GDP·PCE 물가지수, 11-26(목) 한국은행 금융통화위원회·美 추수감사절 휴장이 예정돼 있다.

## 2. 지수
| 지수 | 종가 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| KOSPI | 4,869.96 | −5.21% | 11-20 종가 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 645.68 | −5.71% | 11-20 종가 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 6,910.39 | −3.70% | 11-20 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 22,617.73 | −5.28% | 11-20 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |

<sub>국내·美 모두 전 거래일은 11-20(금). 11-20~11-23 국내·美 증시 휴장 없음([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/), 둘 다 11-23 조회 — 美 추수감사절은 11-26로 이번 주간 해당 없음). 등락률은 11-19 종가(KOSPI 5,137.89·KOSDAQ 684.81, 둘 다 [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) 조회; S&P500 7,175.83·NASDAQ 23,879.20, [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) 조회)와 위 11-20 종가를 `python3 -c`로 직접 계산. KOSPI·KOSDAQ 등락률(−5.21%·−5.71%)은 kr.investing.com 히스토리 표의 표시 등락률과 일치. S&P500 등락률은 [investing.com 마감 기사](https://www.investing.com/news/stock-market-news/us-stocks-lower-at-close-of-trade-dow-jones-industrial-average-down-193-5042683)의 −3.70%(본문 −3.69% 표기와 소수점 차이 있음)와 일치. 같은 기사에서 다우존스는 48,147.33(−1.93%)으로 집계됐으나 watchlist 대상이 아니라 표에는 넣지 않음.</sub>

## 2-1. 현금·환율
| 항목 | 값 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| 달러 인덱스 (DXY) | 103.81 | −0.09% | 11-20 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) |
| USD/JPY | 158.64 | −0.83% | 11-20 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-20?from=USD&to=JPY,KRW) |
| USD/KRW | 1,339.44 | +0.83% | 11-20 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-20?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 844.30 | +1.67% | 11-20 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-20?from=JPY&to=KRW) |

<sub>등락은 11-19 값(DXY 103.90, [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/); USD/JPY 159.97·USD/KRW 1,328.45, [Frankfurter 11-19](https://api.frankfurter.dev/v1/2026-11-19?from=USD&to=JPY,KRW); JPY/KRW 830.43, [JPY 기준](https://api.frankfurter.dev/v1/2026-11-19?from=JPY&to=KRW))과 비교해 `python3 -c`로 계산. DXY는 교차 확인한 [investing.com](https://www.investing.com/indices/usdollar-historical-data)에서 11-19 103.89→11-20 103.81로 집계돼 Yahoo Finance(103.90→103.81)와 11-19 값에서 소수점 수준 불일치가 있음(등락률은 Yahoo Finance 기준 계산).</sub>

## 3. 관심 종목
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 애플 · 2. 마이크로소프트 · 3. 알파벳 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/)) — 엔비디아는 주가 급락으로 Top 3에서 탈락했다.

| 종목 | 종가 | 등락 | 기준 | 한 줄 메모 | 출처 |
|---|---|---|---|---|---|
| 애플 (AAPL) | $342.56 | −1.90% | 11-20 종가 | 복수 매체가 애플이 자체 AI 에이전트를 개발 중이라고 보도해 프리마켓에서 주가가 올랐으나, CNBC는 밸류에이션이 역사적으로 높다며 헤지를 고려할 때라는 의견을 전했고 이사회 멤버 1명이 약 3,100만달러 규모 지분을 매도했음 | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/) |
| 마이크로소프트 (MSFT) | $484.52 | −2.77% | 11-20 종가 | CEO 사티아 나델라가 AI로 인한 장애가 앞으로 더 잦아질 수 있다고 경고했고, 11월 중순 아웃룩 장애 후속 조사에서 신형 서버에서만 결함이 발견된 사실이 확인됐음 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/) |
| 알파벳 (GOOGL) | $265.29 | −2.70% | 11-20 종가 | 시가총액이 2년여 만에 처음으로 엔비디아를 앞질렀다는 보도가 있었으나, 애널리스트가 구글의 2027년 TPU 8i 주문이 약 20% 줄었다고 분석해 브로드컴 주가가 11-20 하루 11% 급락하며 자체 AI 칩 수요 우려가 부각됐음 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) |
| AMD | $424.39 | −13.25% | 11-20 종가 | 공매도 세력(헌터브룩미디어)의 "中 블랙리스트 서버업체向 펌웨어 유입" 의혹 보고서에 더해 美 하원 외교위원회가 AMD의 中向 첨단 AI칩 60만개 수출허가 신청 기록을 공개하며 급락했음(회사는 사업 관행을 잘못 전달했다고 반박) | [stockanalysis.com](https://stockanalysis.com/stocks/amd/) |
| 테슬라 (TSLA) | $345.82 | −7.64% | 11-20 종가 | 의결권 자문사들이 이사회 의장 로빈 데넬름의 재선임에 반대 의견을 내며 주가가 내렸고, 전반적 AI·기술주 매도세도 겹쳤음 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) |
| 스페이스X (SPCX) | $127.79 | −7.69% | 11-20 종가 | 약 320~440억달러 규모 채권 발행으로 AI 인프라 투자 자금을 조달한다는 소식에 레버리지 우려가 부각됐고, 커서(Cursor)가 中 AI 모델 사용을 재검토한다는 보도도 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) |
| 삼성전자 | 183,100원 | −7.01% | 11-20 종가 | - | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data) |
| SK하이닉스 | 1,113,000원 | −5.92% | 11-20 종가 | - | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data) |

<sub>개별 종목 등락률은 11-19 종가(애플 $349.21·마이크로소프트 $498.30·알파벳 $272.66·AMD $489.19·테슬라 $374.41·스페이스X $138.43, 모두 [stockanalysis.com history](https://stockanalysis.com/stocks/aapl/history/) 등 각 종목 히스토리 페이지; 삼성전자 196,900원·SK하이닉스 1,183,000원, [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data))와 위 11-20 종가를 `python3 -c`로 직접 계산해 각 출처 페이지의 표시 등락률과 일치함을 확인. 나스닥 Top3 순위는 조회 시각 기준(시총 애플 4.98T·마이크로소프트 3.60T·알파벳 3.26T)이며 종가 기준일 표기는 페이지에 없음. 마이크로소프트·알파벳은 watchlist 3번과 중복돼 별도 행을 추가하지 않음. 엔비디아(NVDA, watchlist·Top3 어디에도 해당 없음)는 참고로 $145.98→$125.53, 11-19~11-20 하루 −14.01%를 기록함([stockanalysis.com](https://stockanalysis.com/stocks/nvda/)).</sub>

## 4. 주요 뉴스 (최대 5건)
1. **美 AI 버블 우려 재점화 — 다우·S&P500·나스닥 동반 급락, S&P500 조정 국면 진입** — 11-20(현지) 다우존스(−1.93%, 48,147.33)·S&P500(−3.70%, 6,910.39)·나스닥(−5.28%대)이 동반 급락했다. S&P500은 10월 고점 대비 약 12% 낮아져 기술적 조정(10%+) 국면에 진입했고, 공포지수(VIX)는 35.89로 26.2% 급등했다. ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/us-stocks-lower-at-close-of-trade-dow-jones-industrial-average-down-193-5042683), 11-20 16:30 ET 입력)
2. **엔비디아, SEC 회계조사 보도로 하루 14% 급락 — 주간 23% 하락** — 로이터는 11-20(현지) SEC가 엔비디아의 회계 관행을 조사하고 있다고 보도했고, 이 영향으로 엔비디아는 하루 14.01% 내린 $125.53으로 52주 신저가를 기록했다(주간 −23%). ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/nasdaq-plunges-5-a-day-after-anthropic-debut-but-investors-still-believe-in-ai-5042641), 11-20 16:17 ET 입력)
3. **AMD, 공매도 보고서·中수출허가 신청 기록 공개로 13.25% 급락** — 헌터브룩미디어의 "AMD 펌웨어가 中 블랙리스트 서버업체로 흘러갔다"는 의혹 보고서에 더해, 美 하원 외교위원회가 11-20 AMD의 中向 첨단 AI칩 60만개 수출허가 신청 기록을 공개하며 반도체 수출통제 우려가 재부각됐다. AMD는 사업 관행이 잘못 전달됐다고 반박했다. ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 Barron's·TheFly 기사, 11-19~20)
4. **투자자, 성장주서 가치주로 이동 — 나스닥 연초 대비 첫 마이너스 전환** — AI 대형주 급락으로 나스닥 종합지수가 2026년 들어 처음 연초 대비 마이너스로 전환했다. S&P500 가치지수는 연초 대비 +7%인 반면 성장지수는 −4%를 기록해, 2022년 이후 처음으로 가치주가 성장주를 앞지를 수 있다는 분석이 나왔다. ([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/ai-tech-rout-prompts-us-investors-to-rush-into-value-stocks-5042534), 11-20)
5. **테슬라, 의결권 자문사 반대로 이사회 의장 재선임 불확실성 — 주가 7.64% 하락** — 의결권 자문사들이 이사회 의장 로빈 데넬름의 재선임에 반대 의견을 내며 11-20 테슬라 주가가 7.64% 내렸다. ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 TipRanks 기사, 11-20)

## 5. 오늘 일정
- 오늘(11-23)로 확인된 국내·미국 주요 경제지표 발표는 없다 ([investing.com 경제 캘린더](https://www.investing.com/economic-calendar/), 11-23 조회)
- 애플·마이크로소프트·알파벳·AMD·테슬라·스페이스X·삼성전자·SK하이닉스의 실적 발표·주주총회 등 오늘로 확인된 일정은 없다 (각 종목 stockanalysis.com·kr.investing.com 페이지 확인, 11-23)
- 국내·미국 증시 휴장 없음 ([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/))
- 참고(이번 주 일정, [2026-11-22 다음 주 미리보기](2026-11-22-NewsBriefing.md) 참고): 11-25(수) 22:30 KST 美 GDP 3분기 2차 추정치·근원 PCE 물가지수(10월), 11-26(목) 한국은행 금융통화위원회 기준금리 결정, 11-26(목) 美 추수감사절 휴장·11-27(금) 조기 폐장(13:00 ET)

## 6. 전망 (자체 판단)
**직전 전망 점검:** 직전 일일 브리핑([2026-11-19](2026-11-19-NewsBriefing.md))의 전망 13건(상승 우세 2건[AMD·스페이스X]·방향성 불분명 10건·판단 보류 1건[애플], 일일 밴드 ±0.5%, 기간 11-19~11-20)을 11-19→11-20 종가로 확인한 결과(값은 위 2·2-1·3번 및 [stockanalysis.com NVDA](https://stockanalysis.com/stocks/nvda/) 참고) 적중 0건, 빗나감 12건(KOSPI −5.21%·KOSDAQ −5.71%·S&P500 −3.70%·NASDAQ −5.28%·마이크로소프트 −2.77%·엔비디아 −14.01%·알파벳 −2.70%·테슬라 −7.64%·삼성전자 −7.01%·SK하이닉스 −5.92%는 모두 "방향성 불분명"의 ±0.5% 밴드를 크게 벗어났고, AMD −13.25%·스페이스X −7.69%는 "상승 우세" 예측과 반대 방향으로 나타났다), 판단 보류 1건(애플, 집계 제외). 11-19 美 증시가 반등한 다음 날(11-20) 엔비디아 SEC 회계조사 보도와 AMD 공매도 보고서·수출허가 신청 기록 공개가 겹치며 AI 버블 우려가 한꺼번에 터져, 직전 전망 작성 시점에는 예상하지 못한 변수로 전 종목·지수가 예측 범위를 크게 벗어나 하락했다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 하락 우세 | 11-23~11-24 | 1. 美 나스닥·S&P500이 11-20 AI 버블 우려로 각각 5.28%·3.70% 급락하며 반도체 밸류체인 전반에 투자심리 악화가 번졌다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-lower-at-close-of-trade-dow-jones-industrial-average-down-193-5042683))<br>2. 엔비디아가 SEC 회계조사 보도로 하루 14.01% 급락했고 AMD도 공매도 보고서·中수출허가 신청 기록 공개로 13.25% 내려, 국내 반도체 대형주(삼성전자 −7.01%·SK하이닉스 −5.92%)에 대한 투자심리도 11-20 이미 크게 악화됐다 (위 3번 표 참고) | 클리어스테드 어드바이저스의 짐 아와드는 AI 지출 펀더멘털이 주가만큼 악화되지 않았다며 이번 급락을 일반적인 조정으로 평가해, 과매도에 따른 기술적 반등 가능성이 있다 ([investing.com](https://www.investing.com/news/stock-market-news/ai-tech-rout-prompts-us-investors-to-rush-into-value-stocks-5042534)) | 보통 — 독립적 하락 근거 2개(美 지수 급락 전이, 반도체 밸류체인 투자심리 악화)가 있으나 과매도 반등 가능성이 반대 요인으로 있음 |
| KOSDAQ | 하락 우세 | 11-23~11-24 | 1. 美 나스닥이 11-20 하루 5.28% 급락했고 코스닥은 반도체 비중이 높아 업종 전반 투자심리 악화에 더 민감하게 반응해 온 터라 11-20 하루 5.71% 내렸다 ([kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data))<br>2. AMD의 수출허가 신청 기록 공개로 반도체 수출통제 우려가 반도체 밸류체인 전반에 재부각됐다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 Barron's·TheFly 기사) | 짐 아와드의 "AI 지출 펀더멘털 훼손 아님" 평가가 맞다면 과매도 구간에서 반등이 나타날 수 있다 ([investing.com](https://www.investing.com/news/stock-market-news/ai-tech-rout-prompts-us-investors-to-rush-into-value-stocks-5042534)) | 보통 — 독립적 하락 근거 2개(나스닥 급락 전이, 반도체 수출통제 우려)가 있으나 과매도 반등 가능성이 반대 요인으로 있음 |
| S&P 500 | 하락 우세 | 11-23~11-24 | 1. S&P500은 10월 고점 대비 약 12% 낮아져 기술적 조정 국면에 진입했고, 공포지수(VIX)가 35.89로 26.2% 급등했다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-lower-at-close-of-trade-dow-jones-industrial-average-down-193-5042683))<br>2. 엔비디아가 SEC 회계조사 보도로 7거래일 넘게 이어진 하락세 속에 하루 14.01% 급락했다 ([investing.com](https://www.investing.com/news/stock-market-news/nasdaq-plunges-5-a-day-after-anthropic-debut-but-investors-still-believe-in-ai-5042641)) | 일부 애널리스트는 AI 투자의 장기 흐름 자체는 훼손되지 않았다고 평가했다 ([investing.com](https://www.investing.com/news/stock-market-news/ai-tech-rout-prompts-us-investors-to-rush-into-value-stocks-5042534)) | 보통 — 독립적 하락 근거 2개(기술적 조정 진입·VIX 급등, 엔비디아 급락)가 있으나 펀더멘털 훼손 아니라는 반론이 반대 요인으로 있음 |
| NASDAQ | 하락 우세 | 11-23~11-24 | 1. 나스닥은 11-20 하루 5.28% 내려 2026년 들어 처음 연초 대비 마이너스로 전환했다 ([investing.com](https://www.investing.com/news/stock-market-news/nasdaq-plunges-5-a-day-after-anthropic-debut-but-investors-still-believe-in-ai-5042641))<br>2. 투자자들이 성장주에서 가치주로 이동하며 성장지수가 연초 대비 −4%를 기록해 2022년 이후 처음 가치주에 뒤처질 수 있다는 분석이 나왔다 ([investing.com](https://www.investing.com/news/stock-market-news/ai-tech-rout-prompts-us-investors-to-rush-into-value-stocks-5042534)) | 일부 애널리스트는 AI 투자의 장기 흐름 자체는 훼손되지 않았다고 평가했다 (같은 출처) | 보통 — 독립적 하락 근거 2개(나스닥 연초 대비 마이너스 전환, 성장주 이탈)가 있으나 장기 AI 투자 흐름은 훼손되지 않았다는 반론이 있음 |
| 애플 (AAPL) | 상승 우세 | 11-23~11-24 | 1. 복수 매체(TechCrunch·CNBC·Bloomberg 인용 TheFly·MarketWatch)가 애플이 자체 AI 에이전트를 개발 중이라고 보도했다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/) 관련 기사)<br>2. MarketWatch에 따르면 해당 보도 이후 프리마켓에서 주가가 상승했다 (같은 출처) | CNBC의 Mike Khouw는 애플 밸류에이션이 역사적으로 높다며 헤지를 고려할 때라고 평가했고, 이사회 멤버 1명이 약 3,100만달러 규모 지분을 매도했다 (같은 출처) | 보통 — 독립적 상승 근거 2개(AI 에이전트 개발 보도, 프리마켓 반응)가 있으나 밸류에이션 경계·내부자 매도라는 반대 요인이 있음 |
| 마이크로소프트 (MSFT) | 방향성 불분명 | 11-23~11-24 | 상승: 데이너허와의 AI 계측기기 협력, 인텔의 Azure 고객사 확보 등 AI 파트너십 확대 소식이 있었다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/) 관련 기사)<br>하락: CEO 사티아 나델라가 AI로 인한 장애가 앞으로 더 잦아질 수 있다고 경고했고, 11월 아웃룩 장애의 후속 조사에서 신형 서버에서만 결함이 발견된 사실이 재확인됐다 (같은 출처) | 약 6만명 대상 자발적 퇴직 프로그램 등 구조조정이 장기적으로 비용 효율화로 이어질 수 있어, 단기 약세 요인이 희석될 가능성이 있다 (같은 출처) | 낮음 — 상승·하락 근거가 팽팽함 |
| 알파벳 (GOOGL) | 방향성 불분명 | 11-23~11-24 | 상승: 알파벳의 시가총액이 2년여 만에 처음으로 엔비디아를 앞질렀다는 보도가 있었다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 MarketWatch 기사)<br>하락: 애널리스트 분석에 따르면 구글의 2027년 TPU 8i 주문이 약 20% 줄어 브로드컴 주가가 11-20 하루 11% 급락하며 구글 자체 AI 칩 수요에 대한 우려가 부각됐다 (같은 출처) | 추가로 YouTube의 약 30억달러 규모 학군 대상 소송 합의가 임박했다는 보도는 불확실성을 일부 해소하는 요인이 될 수 있다 (같은 출처) | 낮음 — 상승·하락 근거가 팽팽함 |
| AMD | 하락 우세 | 11-23~11-24 | 1. 공매도 세력(헌터브룩미디어)이 "AMD 펌웨어가 中 블랙리스트 서버업체로 흘러갔다"는 의혹 보고서를 내며 주가가 급락했다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 Barron's 기사)<br>2. 美 하원 외교위원회가 11-20 AMD의 中向 첨단 AI칩 60만개 수출허가 신청 기록을 공개하며 수출통제 우려가 재부각됐다 (같은 출처 관련 TheFly 기사) | AMD 측은 해당 보고서가 회사의 사업 관행과 관계를 잘못 전달했다고 반박했다 (같은 출처) | 보통 — 독립적 하락 근거 2개(공매도 보고서, 하원 외교위 수출허가 기록 공개)가 있으나 회사측 반박이라는 반대 요인이 있음 |
| 테슬라 (TSLA) | 하락 우세 | 11-23~11-24 | 1. 의결권 자문사들이 이사회 의장 로빈 데넬름의 재선임에 반대 의견을 내며 주가가 11-20 하루 7.64% 내렸다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 TipRanks 기사)<br>2. 전반적 AI·기술주 매도세가 겹치며 동반 하락했다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-lower-at-close-of-trade-dow-jones-industrial-average-down-193-5042683)) | 아르헨티나 1호 매장 개장, 텍사스 폴리실리콘 공장(31억달러 규모) 추진 등 사업 확장은 계속되고 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 기사) | 보통 — 독립적 하락 근거 2개(이사회 의장 재선임 반대, 업종 전반 매도세)가 있으나 사업 확장이 일부 상쇄 요인 |
| 스페이스X (SPCX) | 하락 우세 | 11-23~11-24 | 1. 약 320~440억달러 규모 채권 발행으로 AI 인프라 투자 자금을 조달한다는 소식에 레버리지 우려가 부각됐다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/) 관련 기사)<br>2. 커서(Cursor)가 中 AI 모델 사용을 재검토한다는 보도로 지정학적 불확실성이 부각됐다 (같은 출처 관련 CNBC 기사) | 테슬라와의 합병 검토가 진행 중이라는 점은 하락세를 일부 상쇄할 수 있다 (같은 출처) | 보통 — 독립적 하락 근거 2개(대규모 채권 발행에 따른 레버리지 우려, 中 AI 모델 사용 재검토 보도)가 있으나 합병 기대라는 반대 요인이 있음 |
| 삼성전자 | 방향성 불분명 | 11-23~11-24 | 상승: 엔비디아가 지난주 3분기 실적에서 공급 약정·클라우드 백로그 확대를 밝혀 HBM 등 메모리 수요 전망 자체는 유지됐다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097))<br>하락: 엔비디아의 SEC 회계조사·AMD의 수출허가 신청 기록 공개로 반도체 밸류체인 전반 투자심리가 악화돼 11-20 삼성전자는 7.01% 내렸다 (위 3번 표 참고) | 11-26 한국은행 금융통화위원회 기준금리 결정 결과에 따라 변동성이 커질 수 있다 ([investing.com](https://www.investing.com/economic-calendar/south-korean-interest-rate-decision-473)) | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 방향성 불분명 | 11-23~11-24 | 상승: 엔비디아가 지난주 3분기 실적에서 공급 약정(2,790억→3,900억달러)·클라우드 백로그(2조→2.5조달러) 확대를 밝혀 HBM 수요 전망 자체는 유지됐다 ([investing.com](https://www.investing.com/news/stock-market-news/nvidia-forecasts-quarterly-revenue-above-estimates-in-first-report-since-huangs-exit-as-ceo-5034097))<br>하락: 핵심 고객사 엔비디아의 SEC 회계조사 보도와 AMD의 수출허가 신청 기록 공개로 반도체 밸류체인 전반 투자심리가 악화돼 11-20 SK하이닉스는 5.92% 내렸다 (위 3번 표 참고) | 11-26 BOK 기준금리 결정 결과에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
