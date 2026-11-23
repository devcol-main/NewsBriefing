# 📈 2026-11-24 (화) 아침 브리핑

> 생성 07:55 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한눈에 (3줄)
- 전 거래일(11-23, 현지) 엔비디아 이사회가 젠슨 황을 사장·CEO·이사로 전격 복귀시켰다고 발표하면서 美 증시가 폭등했다: 다우존스 +3.01%, S&P500 +4.73~4.74%, 나스닥 +6.51%, VIX는 26.61로 25.86% 급락했다. 엔비디아 주가는 하루 31.48% 급등했다.
- 해당 소식은 KRX 마감(15:30) 이후인 현지 11-23 오후(한국시간 11-24 새벽)에 나와 국내 증시에는 반영되지 못한 채, 코스피 −3.31%·코스닥 −1.58%로 추가 하락했다. 관심 종목 중에서는 테슬라(+12.12%)·알파벳(+6.56%)·AMD(+6.83%)·스페이스X(+6.20%)·마이크로소프트(+2.50%)·애플(+1.90%)이 美 랠리에 동반 급등했고, 삼성전자(−3.06%)·SK하이닉스(−2.52%)는 반대로 하락했다.
- 오늘(11-24) 국내·미국 모두 확인된 주요 경제지표 발표나 관심 종목 실적 일정은 없다. 이번 주는 11-25(수) 美 GDP 3분기 2차 추정치·근원 PCE 물가지수, 11-26(목) 한국은행 금융통화위원회·美 추수감사절 휴장이 예정돼 있다.

## 2. 지수
| 지수 | 종가 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| KOSPI | 4,708.54 | −3.31% | 11-23 종가 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 635.45 | −1.58% | 11-23 종가 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 7,237.17 | +4.73% | 11-23 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 24,089.56 | +6.51% | 11-23 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |

<sub>국내·美 모두 전 거래일은 11-23(월). 11-20~11-23 국내·美 증시 휴장 없음(두 시장 모두 주말 외 공백 없이 종가가 이어짐, 11-24 조회). 등락률은 11-20 종가(KOSPI 4,869.96·KOSDAQ 645.68, 둘 다 [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) 조회; S&P500 6,910.39·NASDAQ 22,617.73, [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) 조회)와 위 11-23 종가를 `python3 -c`로 직접 계산. S&P500은 [investing.com 마감 기사](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-301-5046476)가 종가 7,237.90·+4.74%로 집계해 Yahoo Finance(7,237.17·+4.73%)와 소수점 수준 불일치가 있음(등락률은 Yahoo Finance 기준 계산). 같은 기사에서 다우존스는 49,595.31(+3.01%, +1,447.98p)로 집계됐으나 watchlist 대상이 아니라 표에는 넣지 않음. 공포지수(VIX)는 같은 기사 기준 26.61로 −25.86%.</sub>

## 2-1. 현금·환율
| 항목 | 값 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| 달러 인덱스 (DXY) | 104.33 | +0.50% | 11-23 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) |
| USD/JPY | 159.07 | +0.27% | 11-23 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-23?from=USD&to=JPY,KRW) |
| USD/KRW | 1,348.85 | +0.70% | 11-23 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-23?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 847.95 | +0.43% | 11-23 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-23?from=JPY&to=KRW) |

<sub>등락은 11-20 값(DXY 103.81, [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/); USD/JPY 158.64·USD/KRW 1,339.44, [Frankfurter 11-20](https://api.frankfurter.dev/v1/2026-11-20?from=USD&to=JPY,KRW); JPY/KRW 844.30, [JPY 기준](https://api.frankfurter.dev/v1/2026-11-20?from=JPY&to=KRW))과 비교해 `python3 -c`로 계산. DXY는 교차 확인한 [investing.com](https://www.investing.com/indices/usdollar-historical-data)에서도 11-23 104.33(+0.46%, 전일 대비)으로 Yahoo Finance와 일치.</sub>

## 3. 관심 종목
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 애플 · 2. 엔비디아 · 3. 마이크로소프트 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/)) — 엔비디아가 주가 급등으로 Top 3에 복귀했고(11-20~11-23 탈락 상태였음), 알파벳이 Top 3에서 빠졌다.

| 종목 | 종가 | 등락 | 기준 | 한 줄 메모 | 출처 |
|---|---|---|---|---|---|
| 애플 (AAPL) | $349.08 | +1.90% | 11-23 종가 | 엔비디아 CEO 복귀발 AI·반도체 랠리에 동반 상승 (애플 자체 뉴스는 확인되지 않음) | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/history/) |
| 엔비디아 (NVDA) | $165.05 | +31.48% | 11-23 종가 | 이사회가 사임(11-12) 11일 만에 젠슨 황을 사장·CEO·이사로 만장일치 복귀시켰다고 발표하며 하루 최대폭 급등 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/history/) |
| 마이크로소프트 (MSFT) | $496.61 | +2.50% | 11-23 종가 | 엔비디아 CEO 복귀발 AI·반도체 랠리에 동반 상승 (CEO 나델라의 "사이버 방어·인프라 투자가 프리미엄" 발언 관련 기사도 있었음) | [stockanalysis.com](https://stockanalysis.com/stocks/msft/history/) |
| 알파벳 (GOOGL) | $282.69 | +6.56% | 11-23 종가 | 엔비디아 CEO 복귀발 AI 랠리에 동반 급등 — 전일(11-20) 부각됐던 구글 자체 TPU 수요 우려(브로드컴 주문 축소설)에 대한 반작용 성격 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/history/) |
| AMD | $453.37 | +6.83% | 11-23 종가 | 엔비디아 CEO 복귀발 반도체 랠리에 동반 급등했으나, 공매도 보고서·中수출허가 신청 기록 공개 관련 의혹은 아직 해소되지 않음 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/history/) |
| 테슬라 (TSLA) | $387.73 | +12.12% | 11-23 종가 | 엔비디아 CEO 복귀발 AI 랠리에 스페이스X 합병 기대가 겹치며 급등했으나, 이사회 의장 재선임 반대 이슈는 미해소 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/history/) |
| 스페이스X (SPCX) | $135.71 | +6.20% | 11-23 종가 | 엔비디아 CEO 복귀발 AI 인프라 투자 랠리에 동반 급등했으나, 대규모 채권 발행에 따른 레버리지 우려는 미해소 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/history/) |
| 삼성전자 | 177,500원 | −3.06% | 11-23 종가 | 엔비디아 CEO 복귀 소식이 KRX 마감 이후 나와 반영되지 못함 | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data) |
| SK하이닉스 | 1,085,000원 | −2.52% | 11-23 종가 | 엔비디아 CEO 복귀 소식이 KRX 마감 이후 나와 반영되지 못함 | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data) |

<sub>개별 종목 등락률은 11-20 종가(애플 $342.56·마이크로소프트 $484.52·알파벳 $265.29·엔비디아 $125.53·AMD $424.39·테슬라 $345.82·스페이스X $127.79, 모두 [stockanalysis.com history](https://stockanalysis.com/stocks/aapl/history/) 등 각 종목 히스토리 페이지; 삼성전자 183,100원·SK하이닉스 1,113,000원, [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data))와 위 11-23 종가를 `python3 -c`로 직접 계산해 각 출처 페이지의 표시 등락률과 일치함을 확인. 나스닥 Top3 순위는 조회 시각 기준(시총 애플 $5.07T·엔비디아 $3.99T·마이크로소프트 $3.66T)이며 종가 기준일 표기는 페이지에 없음. 마이크로소프트는 watchlist 3번과 중복돼 별도 행을 추가하지 않음. 엔비디아의 CEO 복귀·급등 배경은 아래 4번 뉴스 1·2번 참고.</sub>

## 4. 주요 뉴스 (최대 5건)
1. **엔비디아 이사회, 젠슨 황 CEO 전격 복귀시켜 — 주가 하루 31.48% 폭등** — 엔비디아 이사회가 11-23(현지) 만장일치로 젠슨 황을 사장·최고경영자·이사로 복귀시켰다고 발표했다. 황은 11-12 혼외관계 등 스캔들로 전격 사임했고, 이사회는 11-17~18 "복귀 계획이 없다"는 입장을 밝혔으나 뒤집었다. 이 소식에 엔비디아 주가는 하루 31.48% 급등해 $165.05로 마감했다(가격·등락률은 [stockanalysis.com](https://stockanalysis.com/stocks/nvda/history/) 확인). ([PBS NewsHour](https://www.pbs.org/newshour/nation/nvidia-board-unanimously-reinstates-jensen-huang-as-ceo-and-chairman), 11-23; [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 Schwab Network·Business Insider 기사, 11-23 14시대 ET 입력)
2. **美 3대 지수 동반 폭등 — 다우 +3.01%·S&P500 +4.74%·나스닥 +6.51%, VIX 25.86%↓** — 엔비디아 CEO 복귀 소식에 힘입어 11-23(현지) 다우존스(49,595.31)·S&P500(7,237.90)·나스닥 종합지수가 동반 급등했고, 공포지수(VIX)는 26.61로 25.86% 내렸다. ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-301-5046476), 11-23 16:30 ET 입력)
3. **트럼프 대통령, 황 복귀 관여 주장 — "국가안보 위험 없다"** — CNN은 트럼프 대통령이 부통령 JD 밴스를 통해 엔비디아 이사회와 직접 접촉해 황의 복귀를 도왔다고 보도했고, 트럼프는 "미 정부는 젠슨의 복귀가 국가안보에 위험이 된다고 볼 이유가 없다"고 밝혔다. 이사회도 "황의 복귀가 국가안보 위험이 되지 않는다고 확신한다"는 입장을 냈다. ([CNN](https://edition.cnn.com/2026/11/23/business/live-news/jensen-huang-reinstated-as-ceo-of-nvidia), 11-23; 기업 지배구조·수출통제 우려 관련 [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 MarketWatch 기사 "Jensen Huang Is Back at Nvidia. What Happens Now?", 11-23 13:43 ET 입력)
4. **AMD·테슬라·알파벳·스페이스X 등 AI 관련주 동반 급등** — 엔비디아 랠리에 힘입어 AMD(+6.83%)·테슬라(+12.12%)·알파벳(+6.56%)·스페이스X(+6.20%)·마이크로소프트(+2.50%)·애플(+1.90%) 등 AI·반도체 관련주가 일제히 급등했다. ([stockanalysis.com](https://stockanalysis.com/stocks/amd/history/) 등 각 종목 히스토리 페이지, 11-23)
5. **코스피·코스닥, 美 호재 반영 전 마감 — 각각 −3.31%·−1.58% 추가 하락** — 엔비디아 CEO 복귀 소식은 KRX 마감(15:30 KST) 이후인 현지 11-23 오후(한국시간 11-24 새벽)에 나와, 11-23 국내 증시는 이를 반영하지 못한 채 코스피(4,708.54)·코스닥(635.45)이 전 거래일보다 추가로 내렸다. ([kr.investing.com](https://kr.investing.com/indices/kospi-historical-data), [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data), 11-23)

## 5. 오늘 일정
- 오늘(11-24)로 확인된 국내·미국 주요 경제지표 발표는 없다 ([investing.com 경제 캘린더](https://www.investing.com/economic-calendar/), 11-24 조회)
- 애플·엔비디아·마이크로소프트·알파벳·AMD·테슬라·스페이스X·삼성전자·SK하이닉스의 실적 발표·주주총회 등 오늘로 확인된 일정은 없다 (각 종목 stockanalysis.com·kr.investing.com 페이지 확인, 11-24)
- 국내·미국 증시 휴장 없음 ([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/))
- 참고(이번 주 일정, [2026-11-22 다음 주 미리보기](2026-11-22-NewsBriefing.md) 참고): 11-25(수) 22:30 KST 美 GDP 3분기 2차 추정치·근원 PCE 물가지수(10월), 11-26(목) 한국은행 금융통화위원회 기준금리 결정, 11-26(목) 美 추수감사절 휴장·11-27(금) 조기 폐장(13:00 ET)

## 6. 전망 (자체 판단)
**직전 전망 점검:** 직전 일일 브리핑([2026-11-23](2026-11-23-NewsBriefing.md))의 전망(기간 11-23~11-24)은 대상일인 오늘(11-24)이 아직 마감되지 않아 두 종가 모두를 확인할 수 없어 점검이 불가능하다. 일일 전망 점검은 통상 전전 거래일 브리핑의 전망(전전 거래일→전 거래일 종가로 확인 가능)을 대상으로 하는데, 전전 거래일(11-20, 금)의 일일 브리핑은 생성되지 않았고(루틴 미실행, [2026-11-21 주간 요약](2026-11-21-NewsBriefing.md) 참고), 그 이전 11-19 브리핑의 전망(기간 11-19~11-20)은 [2026-11-23 브리핑](2026-11-23-NewsBriefing.md)에서 이미 점검을 마쳤다. 따라서 오늘 새로 점검할 수 있는 직전 일일 전망이 없다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 상승 우세 | 11-24~11-25 | 1. 엔비디아 CEO 복귀 소식이 11-23 KRX 마감 이후 나와 美 나스닥(+6.51%)·엔비디아(+31.48%) 급등이 아직 국내 증시에 반영되지 않았다 (위 2·3·4번 참고)<br>2. 삼성전자·SK하이닉스는 엔비디아의 핵심 HBM 공급사로, 엔비디아 리더십 불확실성 해소는 그간 반도체 밸류체인 투자심리를 눌렀던 요인의 해소로 이어질 수 있다 ([PBS NewsHour](https://www.pbs.org/newshour/nation/nvidia-board-unanimously-reinstates-jensen-huang-as-ceo-and-chairman), 11-23) | 코스피는 전 거래일(11-23)에도 −3.31% 추가 하락해 단기 투자심리가 여전히 취약하며, 11-26 한국은행 금융통화위원회 결과를 앞두고 경계감이 남아있다 ([investing.com](https://www.investing.com/economic-calendar/south-korean-interest-rate-decision-473)) | 보통 — 독립적 상승 근거 2개(美 반도체 랠리 미반영, 리더십 불확실성 해소)가 있으나 전일 약세 연장·BOK 변수가 반대 요인으로 있음 |
| KOSDAQ | 상승 우세 | 11-24~11-25 | 1. 엔비디아 CEO 복귀 소식이 KRX 마감 이후 나와 美 나스닥 급등이 아직 반영되지 않았고, 코스닥은 반도체 비중이 높아 업종 전반 투자심리 개선에 더 민감하게 반응해 온 터다 (위 2·3·4번 참고)<br>2. AMD·엔비디아 등 美 반도체 대형주 랠리는 국내 반도체 밸류체인 전반에 긍정적 전이 요인이 될 수 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/history/)) | 코스닥도 전 거래일 −1.58% 추가 하락해 단기 투자심리가 취약하다 ([kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data)) | 보통 — 독립적 상승 근거 2개(美 반도체 랠리 미반영, 반도체 비중에 따른 민감도)가 있으나 전일 약세 연장이 반대 요인으로 있음 |
| S&P 500 | 상승 우세 | 11-24~11-25 | 1. 엔비디아 CEO 복귀로 리더십 불확실성이 해소되며 11-23 하루 +4.73~4.74% 급등했고 공포지수(VIX)도 26.61로 25.86% 내려 투자심리가 크게 개선됐다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-301-5046476))<br>2. 트럼프 대통령·이사회 모두 "국가안보 위험 없다"고 밝혀 엔비디아를 둘러싼 정치적 불확실성의 핵심 축이 일부 해소됐다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 MarketWatch 기사) | 엔비디아에 대한 SEC 회계조사는 아직 진행 중이며 해소되지 않았고([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/nasdaq-plunges-5-a-day-after-anthropic-debut-but-investors-still-believe-in-ai-5042641)), 하루 만에 급등한 만큼 밸류에이션 부담에 따른 되돌림 가능성도 있다 | 보통 — 독립적 상승 근거 2개(리더십 불확실성 해소·VIX 급락, 국가안보 우려 완화 발언)가 있으나 SEC 조사 미해소·급등 후 되돌림 가능성이 반대 요인으로 있음 |
| NASDAQ | 상승 우세 | 11-24~11-25 | 1. 엔비디아 CEO 복귀 소식에 나스닥이 11-23 하루 +6.51% 급등했고 엔비디아는 하루 31.48% 올랐다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-301-5046476))<br>2. AMD·테슬라·알파벳·스페이스X 등 AI 관련주 전반이 동반 급등하며 랠리가 개별 종목에 국한되지 않고 업종 전반으로 확산됐다 (위 3번 표 참고) | 엔비디아 SEC 회계조사가 미해소 상태로 남아있고([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/nasdaq-plunges-5-a-day-after-anthropic-debut-but-investors-still-believe-in-ai-5042641)), 혼외관계·스캔들 관련 논란도 12월 의회 증언을 앞두고 있어 재부각될 수 있다 | 보통 — 독립적 상승 근거 2개(지수·엔비디아 급등, 업종 전반 확산)가 있으나 SEC 조사·스캔들 논란 재부각 가능성이 반대 요인으로 있음 |
| 애플 (AAPL) | 방향성 불분명 | 11-24~11-25 | 상승: 엔비디아 CEO 복귀발 AI·반도체 랠리에 11-23 하루 1.90% 오르며 동반 상승했다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/history/))<br>하락: 애플 자체의 새로운 호재성 뉴스는 확인되지 않아, 랠리가 업종 전반 베타에 그칠 경우 상대적으로 덜 오를 수 있다 (같은 출처) | 애플은 이번 급락장에서도 관심 종목 중 가장 선방했던 종목으로, 상대적 안전자산 선호가 이어질 가능성도 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/history/)) | 낮음 — 상승·하락 근거가 팽팽함 |
| 엔비디아 (NVDA) | 상승 우세 | 11-24~11-25 | 1. 이사회가 만장일치로 젠슨 황을 CEO로 복귀시키며 2주 가까이 주가를 눌렀던 리더십 공백 우려가 해소돼 11-23 하루 31.48% 급등했다 ([PBS NewsHour](https://www.pbs.org/newshour/nation/nvidia-board-unanimously-reinstates-jensen-huang-as-ceo-and-chairman), 11-23)<br>2. 트럼프 대통령과 이사회 모두 "국가안보 위험이 없다"고 밝혀 복귀를 둘러싼 정치적 불확실성이 일부 해소됐다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 MarketWatch 기사) | SEC의 회계 관행 조사는 여전히 진행 중이며 해소되지 않았고([investing.com(Reuters)](https://www.investing.com/news/stock-market-news/nasdaq-plunges-5-a-day-after-anthropic-debut-but-investors-still-believe-in-ai-5042641)), 황의 사임을 불렀던 혼외관계·스캔들 논란도 12월 의회 증언을 앞두고 있어 재부각될 수 있다. 하루 31% 급등 이후 되돌림 가능성도 있다 | 보통 — 독립적 상승 근거 2개(리더십 불확실성 해소, 국가안보 우려 완화)가 있으나 SEC 조사 미해소·스캔들 재부각 가능성·급등 후 되돌림 가능성이 반대 요인으로 있음 |
| 마이크로소프트 (MSFT) | 방향성 불분명 | 11-24~11-25 | 상승: 엔비디아 CEO 복귀발 AI 랠리에 11-23 하루 2.50% 오르며 동반 상승했다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/history/))<br>하락: CEO 나델라가 AI로 인한 장애가 더 잦아질 수 있다고 경고한 발언과 11월 아웃룩 장애 후속 조사 이슈는 아직 해소되지 않았다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/) 관련 기사) | 데이너허와의 AI 계측기기 협력 등 파트너십 확대 소식은 긍정적 요인으로 일부 상쇄할 수 있다 (같은 출처) | 낮음 — 상승·하락 근거가 팽팽함 |
| 알파벳 (GOOGL) | 방향성 불분명 | 11-24~11-25 | 상승: 엔비디아 CEO 복귀발 AI 랠리에 11-23 하루 6.56% 급등하며 전일(11-20) 부각됐던 AI 반도체 수요 우려의 일부를 되돌렸다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/history/))<br>하락: 브로드컴 애널리스트의 구글 2027년 TPU 8i 주문 축소 분석은 아직 해소되지 않은 사실로 남아있다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 기사) | 알파벳 시가총액이 엔비디아를 앞질렀다는 보도 등 상대적 강세 요인이 이어질 수 있다 (같은 출처) | 낮음 — 상승·하락 근거가 팽팽함 |
| AMD | 방향성 불분명 | 11-24~11-25 | 상승: 엔비디아 CEO 복귀발 반도체 랠리에 11-23 하루 6.83% 급등하며 동반 상승했다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/history/))<br>하락: 헌터브룩미디어의 공매도 보고서 의혹과 美 하원 외교위의 中向 수출허가 신청 기록 공개 논란은 아직 해소되지 않았다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 Barron's·TheFly 기사) | AMD 측은 해당 보고서가 사업 관행을 잘못 전달했다고 반박했다 (같은 출처) | 낮음 — 상승·하락 근거가 팽팽함 |
| 테슬라 (TSLA) | 방향성 불분명 | 11-24~11-25 | 상승: 엔비디아 CEO 복귀발 AI 랠리와 스페이스X와의 합병 검토 기대가 겹치며 11-23 하루 12.12% 급등했다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/history/))<br>하락: 의결권 자문사들의 이사회 의장(로빈 데넬름) 재선임 반대 이슈는 아직 해소되지 않았다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 TipRanks 기사) | 하루 12% 급등한 만큼 단기 과열에 따른 되돌림 가능성도 있다 (같은 출처) | 낮음 — 상승·하락 근거가 팽팽함 |
| 스페이스X (SPCX) | 방향성 불분명 | 11-24~11-25 | 상승: 엔비디아 CEO 복귀발 AI 인프라 투자 랠리에 11-23 하루 6.20% 급등하며 동반 상승했다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/history/))<br>하락: 약 320~440억달러 규모 채권 발행에 따른 레버리지 우려는 아직 해소되지 않았다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/) 관련 기사) | 테슬라와의 합병 검토가 진행 중이라는 점은 상승 요인을 뒷받침할 수 있다 (같은 출처) | 낮음 — 상승·하락 근거가 팽팽함 |
| 삼성전자 | 상승 우세 | 11-24~11-25 | 1. 엔비디아 CEO 복귀 소식이 11-23 KRX 마감 이후 나와 아직 국내 증시에 반영되지 않았고, 삼성전자는 엔비디아의 핵심 HBM 공급사다 ([PBS NewsHour](https://www.pbs.org/newshour/nation/nvidia-board-unanimously-reinstates-jensen-huang-as-ceo-and-chairman), 11-23)<br>2. 엔비디아 리더십 불확실성 해소는 그간 메모리 공급망 전반을 눌렀던 투자심리 악화 요인의 해소로 이어질 수 있다 (위 3번 표 참고) | 삼성전자는 전 거래일(11-23)에도 −3.06% 추가 하락해 단기 투자심리가 취약하며, 11-26 한국은행 기준금리 결정 결과에 따라 변동성이 커질 수 있다 ([investing.com](https://www.investing.com/economic-calendar/south-korean-interest-rate-decision-473)) | 보통 — 독립적 상승 근거 2개(美 반도체 랠리 미반영, 핵심 고객사 리더십 불확실성 해소)가 있으나 전일 약세 연장·BOK 변수가 반대 요인으로 있음 |
| SK하이닉스 | 상승 우세 | 11-24~11-25 | 1. 엔비디아 CEO 복귀 소식이 KRX 마감 이후 나와 아직 반영되지 않았고, SK하이닉스는 엔비디아의 핵심 HBM 공급사다 ([PBS NewsHour](https://www.pbs.org/newshour/nation/nvidia-board-unanimously-reinstates-jensen-huang-as-ceo-and-chairman), 11-23)<br>2. 엔비디아 리더십 불확실성 해소는 HBM 수요 전망에 대한 투자심리 개선으로 이어질 수 있다 (위 3번 표 참고) | SK하이닉스도 전 거래일 −2.52% 추가 하락했고, 11-26 BOK 기준금리 결정 결과에 따라 변동성이 커질 수 있다 | 보통 — 독립적 상승 근거 2개(美 반도체 랠리 미반영, 핵심 고객사 리더십 불확실성 해소)가 있으나 전일 약세 연장·BOK 변수가 반대 요인으로 있음 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
