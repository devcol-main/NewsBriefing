# 📈 2026-11-05 (목) 아침 브리핑

> 생성 08:00 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한눈에 (3줄)
- 美 중간선거에서 민주당이 상·하원을 모두 장악하며 정치적 불확실성이 해소되자 월가는 다우존스 +3.19%(19개월 만의 최대 상승일)·S&P500 +1.58%(7,688.62)·나스닥 +1.44%(25,736.51)로 급등했지만, 데이터센터 규제 강화 우려로 AI 인프라·반도체 관련주(엔비디아 −3.12%)는 하락했어요. 코스피·코스닥도 같은 이유로 장중 한때 4%대 급락했다가 개인·기관 순매수에 반등해 각각 +0.62%(5,683.80)·+1.50%(714.95)로 마감했어요.
- 관심 종목 중에서는 마이크로소프트가 클라우드 공급 부족에 따른 가격 인상 기대와 선거 불확실성 해소로 +6.72% 올랐고 애플도 사상 최고가를 새로 쓰며 +5.33% 올랐는데, 반대로 엔비디아는 데이터센터 규제 우려로 −3.12% 내렸어요.
- 오늘(KST)은 美 3분기 생산성·단위노동비용 잠정치 발표가 예정돼 있고, 전날 중간선거 결과에 따른 데이터센터 규제 관련 후속 보도와 AMD 실적 반응이 이어질지 지켜볼 예정이에요.

## 2. 지수
| 지수 | 종가 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| KOSPI | 5,683.80 | +0.62% | 11-04 종가 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 714.95 | +1.50% | 11-04 종가 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 7,688.62 | +1.58% | 11-04 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 25,736.51 | +1.44% | 11-04 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |

<sub>국내·미국 모두 전 거래일은 11-04(수). 11-03~11-05 모두 한국·미국 증시 휴장 없음([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/); 11-04는 러시아만 휴일). 등락률은 11-03 종가와 `python3 -c`로 직접 계산. S&P500·나스닥 등락은 [investing.com(Dow 마감)](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152) 기사 본문의 +1.80%·+1.78%와는 다소 차이가 있으나, 같은 기사·페이지의 시세 위젯 수치(+1.58%·+1.44%)와는 정확히 일치한다(기사 본문은 다른 집계 시점으로 추정).</sub>

## 2-1. 현금·환율
| 항목 | 값 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| 달러 인덱스 (DXY) | 101.51 / 101.390 (불일치) | −0.35% / −0.33% | 11-04 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) / [investing.com](https://www.investing.com/currencies/us-dollar-index-historical-data) |
| USD/JPY | 158.25 | −0.03% | 11-04 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-04?from=USD&to=JPY,KRW) |
| USD/KRW | 1,338.58 | −0.45% | 11-04 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-04?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 845.87 | −0.42% | 11-04 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-04?from=JPY&to=KRW) |

<sub>DXY는 Yahoo Finance 히스토리 표(101.51, 지수)와 investing.com 히스토리 표(101.390, 12월물 선물)가 서로 달라 "불일치"로 표시, 전일 종가는 각각 101.87(Yahoo)·101.726(investing.com). 환율 등락은 직전 고시일 11-03 값(USD/JPY 158.29, USD/KRW 1,344.59, JPY/KRW 849.46)과 비교해 `python3 -c`로 계산([USD](https://api.frankfurter.dev/v1/2026-11-03?from=USD&to=JPY,KRW), [JPY→KRW](https://api.frankfurter.dev/v1/2026-11-03?from=JPY&to=KRW)).</sub>

## 3. 관심 종목
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 애플 · 2. 엔비디아 · 3. 마이크로소프트 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))

| 종목 | 종가 | 등락 | 기준 | 한 줄 메모 | 출처 |
|---|---|---|---|---|---|
| 애플 (AAPL) | $349.59 | +5.33% | 11-04 종가 | 美 중간선거 불확실성 해소와 AI 투자둔화 우려 완화 기대로 사상 최고가를 새로 썼음. 다만 일부 월가 리서치는 밸류에이션이 실적 대비 과도하다는 평가를 내놓았음 | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/) |
| 엔비디아 (NVDA) | $200.24 | −3.12% | 11-04 종가 | 민주당의 의회 장악으로 데이터센터 건설 규제가 강화될 수 있다는 우려에 반도체주 매도에 동참해 하락했음. FT는 엔비디아가 데이터센터 파트너들에 중국 고객 비중을 50% 미만으로 줄이라고 요청했다고 보도했음 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/), [investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152) |
| 마이크로소프트 (MSFT) | $556.00 | +6.72% | 11-04 종가 | 클라우드 공급 부족에 따른 가격 인상 기대와 선거 불확실성 해소로 다우 상승 상위 종목(+7.1%)에 올랐음 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/), [investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152) |
| AMD | $488.82 | +1.02% | 11-04 종가 | 2027년 매출 성장률을 애널리스트 예상(77%)을 웃도는 80%대로 제시했지만, OpenAI·Meta에 발행한 지분매입 워런트로 3분기 비현금성 비용이 10억달러 넘게 발생해 이익이 타격받으며 상승폭이 제한됐음 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/), [investing.com](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-with-midterms-in-focus-amd-rallies-on-strong-earnings-4997029) |
| 알파벳 (GOOGL) | $289.02 | +3.21% | 11-04 종가 | 선거 불확실성 해소에 따른 대형 기술주 전반 강세에 더해, 2027~2028년 말레이시아에 150억달러를 투자해 데이터센터를 확충한다는 소식이 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) |
| 테슬라 (TSLA) | $385.29 | −3.31% | 11-04 종가 | 민주당의 의회 장악에 따른 정책 리스크와 머스크의 선거 자금 지출이 기대에 못 미쳤다는 평가가 겹치며, 중간선거 랠리에도 동반 상승하지 못하고 내렸음 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) |
| 스페이스X (SPCX) | $135.84 | −3.87% | 11-04 종가 | Qualcomm과 미국 전역 5G 통신 인프라(Dragonwing) 다년 계약을 체결했다는 보도가 있었으나, 머스크 관련 정책·규제 리스크 우려로 테슬라와 함께 동반 하락했음 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) |
| 삼성전자 | 218,000원 | −0.68% | 11-04 종가 | 데이터센터 규제 강화 우려가 이어지며 전날 급락 이후에도 반도체 대형주 재평가 부담이 지속됐음 | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data), [kr.investing.com(칼럼)](https://kr.investing.com/analysis/article-200459746) |
| SK하이닉스 | 1,396,000원 | −0.14% | 11-04 종가 | 같은 흐름 속에 소폭 하락해 보합권에 머물렀음 | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data) |

## 4. 주요 뉴스 (최대 5건)
1. **美 중간선거, 민주당이 상·하원 모두 장악 — 월가는 "불확실성 해소" 랠리, AI 인프라주는 하락** — 11-04(현지) 다우존스 산업평균은 3.19% 올라 1개월 신고가를 기록했고, S&P500(+1.58%)·나스닥(+1.44%)도 동반 상승했다. VIX는 19.9% 급락해 16.69를 기록했다. 다만 데이터센터·AI 인프라 관련주는 규제 강화 우려로 하락해 코어위브(−9.9%)·IREN(−11.2%)·네비우스(−6.7%)가 급락했고, 다우 구성종목 중 엔비디아(−2.2%)·캐터필러(−5.6%)도 하락 상위에 올랐다. ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152), 11-04 15:30)
2. **코스피·코스닥, 중간선거發 급등락 끝에 반등 마감** — 11-04 코스피는 장 초반 상승 출발 후 데이터센터 규제 우려로 장중 한때 5,500선이 무너질 정도로 4% 넘게 급락했다가, 민주당 승리가 확정되며 선거 리스크가 소멸했다는 평가와 함께 반등해 결국 +0.62%(5,683.80)로 마감했다. 코스닥도 장중 683선까지 밀렸다가 +1.50%(714.95)로 마쳤다. ([kr.investing.com(칼럼)](https://kr.investing.com/analysis/article-200459746), 11-04 18:11)
3. **AMD, 2027년 매출 80%+ 성장 전망에도 워런트 비용으로 이익 타격 — 주가는 소폭 상승 그쳐** — AMD는 4분기 가이던스와 함께 2027년 매출 성장률을 애널리스트 예상(77%)을 웃도는 80% 이상으로 제시했다. 다만 OpenAI·Meta에 발행한 지분매입 워런트로 3분기에 10억달러 넘는 비현금성 비용이 발생해 이익이 타격을 받았다. 주가는 프리마켓에서 7% 넘게 올랐다가 정규장 종가 기준으로는 1% 상승에 그쳤다. ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-with-midterms-in-focus-amd-rallies-on-strong-earnings-4997029), 게시 11-03 19:36·업데이트 11-04 16:14)
4. **애플, 사상 최고가 경신** — 애플 주가는 11-04 종가 기준 349.59달러로 사상 최고치를 새로 썼다. 중간선거 결과로 투자자 불확실성이 줄고 데이터센터 투자 둔화 우려가 일부 완화된 점이 상승 배경으로 꼽혔다. ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/), 11-04)
5. **엔비디아, 데이터센터 규제 우려로 하락 — 中 고객 비중 축소 요청 보도도 부담** — 민주당의 의회 장악에 따라 데이터센터 건설 관련 규제가 강화될 수 있다는 우려로 엔비디아 주가는 11-04 3.12% 내렸다. FT는 엔비디아가 데이터센터 파트너들에게 중국 고객 비중을 50% 미만으로 줄이라고 요청했다고 보도했다. ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/), [investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152), 11-04)

## 5. 오늘 일정
- 美 3분기 생산성·단위노동비용(잠정치), 현지 11-05 오전 8:30 ET 발표 예정 ([BLS 11월 일정](https://www.bls.gov/schedule/2026/11_sched_list.htm))
- 美 중간선거 접전 지역 개표 확정 및 의회 구성 세부 확정 소식이 이어질 수 있음 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152))
- 연준은 10/27~28 FOMC에서 기준금리를 3.75~4.00%로 동결했으며(10대 2 표결), 다음 발표 일정은 없음 ([federalreserve.gov](https://www.federalreserve.gov/newsevents/pressreleases/monetary20261028a.htm))
- 국내·미국 증시 휴장 없음 ([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/))

## 6. 전망 (자체 판단)
**직전 전망 점검:** 직전 일일 브리핑(2026-11-04)의 전망 13건을 11-03→11-04 종가로 확인한 결과 적중 5건(S&P500 +1.58%·나스닥 +1.44%·마이크로소프트 +6.72%·AMD +1.02%는 각각 "상승 우세" 예측과 일치, SK하이닉스 −0.14%는 "방향성 불분명" 예측의 ±0.5% 밴드 안에 들어 적중), 빗나감 8건(코스피 +0.62%·코스닥 +1.50%·엔비디아 −3.12%·알파벳 +3.21%·테슬라 −3.31%·스페이스X −3.87%·삼성전자 −0.68%는 "방향성 불분명" 예측의 ±0.5% 밴드를 벗어났고, 애플 +5.33%는 "하락 우세" 예측과 반대), 판단 보류 0건. 美 중간선거에서 민주당이 의회를 장악하며 정치적 불확실성이 해소되자 지수·대형 기술주 대부분이 예상보다 훨씬 크게 올랐고, 국내 증시는 장중 급락 후 반등하며 예상된 밴드를 크게 벗어난 항목이 많았다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 11-05~11-06 | 상승: 美 증시가 중간선거 불확실성 해소로 크게 올라(다우 +3.19%) 글로벌 위험선호 개선이 전이될 수 있다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152))<br>하락: 데이터센터 규제 강화 우려가 국내 반도체 대형주 재평가 부담으로 여전히 남아 있다는 분석이 나왔다 ([kr.investing.com(칼럼)](https://kr.investing.com/analysis/article-200459746)) | 코스피 6,500~7,000p대와 지난 5~6월 8,000~9,000p대에 쌓인 매물을 소화하는 데 시간이 걸릴 수 있다 (같은 칼럼) | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 방향성 불분명 | 11-05~11-06 | 상승: 美 증시 랠리가 이어지면 코스닥 반도체·2차전지 관련주에도 투자심리가 전이될 수 있다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152))<br>하락: 데이터센터 규제 우려가 지속되면 코스피보다 변동성이 더 크게 나타날 수 있다 ([kr.investing.com(칼럼)](https://kr.investing.com/analysis/article-200459746)) | 코스피와 마찬가지로 상단에 쌓인 매물이 소화되는 데 시간이 걸릴 수 있다 ([kr.investing.com(칼럼)](https://kr.investing.com/analysis/article-200459746)) | 낮음 — 상승·하락 근거가 팽팽함 |
| S&P 500 | 방향성 불분명 | 11-05~11-06 | 상승: 중간선거 결과 확정으로 정치적 불확실성이 제거돼 VIX가 19.9% 급락(16.69)했다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152))<br>하락: AI 데이터센터 관련주(코어위브 −9.9%·IREN −11.2%·네비우스 −6.7%)가 규제 강화 우려로 급락해 이 흐름이 이어지면 지수 상단을 제한할 수 있다 (같은 기사) | 연준은 10/28 FOMC에서 기준금리를 3.75~4.00%로 동결했지만 2명 위원이 인상에 찬성해 긴축 리스크가 남아 있다 ([federalreserve.gov](https://www.federalreserve.gov/newsevents/pressreleases/monetary20261028a.htm)) | 낮음 — 상승·하락 근거가 팽팽함 |
| NASDAQ | 방향성 불분명 | 11-05~11-06 | 상승: AMD가 2027년 매출 성장률을 애널리스트 예상(77%)보다 높은 80%대로 제시해 AI 반도체 수요 둔화 우려를 일부 완화했다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-with-midterms-in-focus-amd-rallies-on-strong-earnings-4997029))<br>하락: 데이터센터·AI 인프라 관련주가 규제 강화 우려로 급락했고(코어위브 −9.9% 등), 엔비디아도 동반 하락했다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152)) | 애플(+5.33%)·마이크로소프트(+6.72%) 등 대형 기술주는 선거 불확실성 해소로 강하게 올라 AI 인프라주 약세를 상쇄할 수도 있다 (같은 기사) | 낮음 — 상승·하락 근거가 팽팽함 |
| 애플 (AAPL) | 방향성 불분명 | 11-05~11-06 | 상승: 중간선거 불확실성 해소와 AI 투자둔화 우려 완화 기대로 11-04 사상 최고가를 기록했다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/))<br>하락: 일부 월가 리서치는 애플의 밸류에이션이 실적 대비 과도하다고 평가했다 (같은 자료) | 애플은 연말 성수기 매출이 7~10% 성장할 것으로 전망해 펀더멘털 자체는 견조하다 (같은 자료) | 낮음 — 상승·하락 근거가 팽팽함 |
| 엔비디아 (NVDA) | 방향성 불분명 | 11-05~11-06 | 상승: AMD가 데이터센터 매출 전망을 상향하며 AI 반도체 수요 피크아웃 우려를 완화해 반도체 업종 전반에 긍정적으로 반영될 수 있다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-with-midterms-in-focus-amd-rallies-on-strong-earnings-4997029))<br>하락: 민주당의 의회 장악에 따른 데이터센터 규제 강화 우려로 11-04 다우 하락 상위권(−2.2%)에 올랐고, FT 보도에 따르면 데이터센터 파트너들에 중국 고객 비중 축소도 요청했다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152), [stockanalysis.com](https://stockanalysis.com/stocks/nvda/)) | 中 기업들의 AI 칩 주문 적체(약 700억달러 규모)·공급 부족 문제가 보도돼(2026-11-04 브리핑 참고) 중장기 수요 자체는 견조하다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 마이크로소프트 (MSFT) | 상승 우세 | 11-05~11-06 | 1. 클라우드 공급 부족으로 마이크로소프트가 가격을 올릴 여력이 있다는 분석이 나왔다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152))<br>2. 선거 불확실성 해소로 대형 기술주 전반이 강세를 보이는 흐름 속에 11-04 다우 상승 상위 종목(+7.1%)에 올랐다 (같은 기사) | 약 250억달러 투자등급 채권 발행과 약 6만명 대상 자발적 퇴직(buyout) 제안에 따른 자본지출·비용 부담 우려, 데이터센터 규제 강화 우려가 여전히 남아 있다 ([2026-11-04 브리핑](2026-11-04-NewsBriefing.md) 참고) | 보통 — 공급부족發 가격 인상 기대·업종 전반 강세라는 두 독립적 근거 |
| AMD | 상승 우세 | 11-05~11-06 | 1. 4분기 가이던스와 2027년 매출 성장률(80%대, 애널리스트 예상 77% 상회)을 시장 예상보다 높게 제시했다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-with-midterms-in-focus-amd-rallies-on-strong-earnings-4997029))<br>2. 데이터센터 매출이 전년대비 97% 증가했다고 밝혔다 ([2026-11-04 브리핑](2026-11-04-NewsBriefing.md) 참고) | OpenAI·Meta向 워런트 발행에 따른 비현금성 비용으로 3분기 이익이 타격받았고, 필라델피아반도체지수는 오히려 3.1% 하락해 반도체 업종 투자심리는 엇갈렸다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-futures-steady-with-midterms-in-focus-amd-rallies-on-strong-earnings-4997029)) | 보통 — 가이던스·데이터센터 매출 성장이라는 두 독립적 근거 |
| 알파벳 (GOOGL) | 상승 우세 | 11-05~11-06 | 1. 선거 불확실성 해소로 대형 기술주 전반이 강세를 보이는 흐름에 동반해 11-04 +3.21% 올랐다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152))<br>2. 2027~2028년 말레이시아에 150억달러를 투자해 데이터센터 등 인프라를 확충한다고 발표했다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/)) | 최근 분기보고서에서 공개된 985억달러 규모 잠재적 금융 의무 증가 우려가 여전히 남아 있다 ([2026-11-02 브리핑](2026-11-02-NewsBriefing.md) 참고) | 낮음 — 업종 전반 강세·개별 투자 발표라는 근거지만 강도가 약함 |
| 테슬라 (TSLA) | 방향성 불분명 | 11-05~11-06 | 상승: 유럽 10월 신차 등록이 이탈리아·포르투갈·스웨덴 등 여러 나라에서 두 자릿수~세 자릿수로 늘었다 ([2026-11-04 브리핑](2026-11-04-NewsBriefing.md) 참고)<br>하락: 민주당의 의회 장악에 따른 정책 리스크와 머스크의 선거 자금 지출이 기대에 못 미쳤다는 평가가 겹쳐 11-04 중간선거 랠리에도 동반 상승하지 못했다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/)) | 스페이스X와의 합병 논의가 진전되면 밸류에이션 재평가 기대로 주가가 반응할 수 있다 ([2026-11-02 브리핑](2026-11-02-NewsBriefing.md) 참고) | 낮음 — 상승·하락 근거가 팽팽함 |
| 스페이스X (SPCX) | 방향성 불분명 | 11-05~11-06 | 상승: Qualcomm과 미국 전역 5G 통신 인프라(Dragonwing) 다년 계약을 체결했다는 보도가 있었다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/))<br>하락: 민주당의 의회 장악에 따른 규제·M&A 심사 강화 우려와 머스크의 정치자금 지출 논란이 겹치며 11-04 하락했다 (같은 자료) | 고객 집중도(앤트로픽 비중)·대주주(바이낸스) 매도 우려는 여전히 남아 있다 ([2026-11-02 브리핑](2026-11-02-NewsBriefing.md) 참고) | 낮음 — 상승·하락 근거가 팽팽함 |
| 삼성전자 | 방향성 불분명 | 11-05~11-06 | 상승: 美 반도체 대형주(마이크로소프트·AMD 등) 강세가 이어지면 투자심리가 전이될 수 있다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152))<br>하락: 데이터센터 규제 강화 우려가 국내 반도체 대형주 재평가 부담으로 이어지며 11-04에도 −0.68% 내렸다는 분석이 나왔다 ([kr.investing.com(칼럼)](https://kr.investing.com/analysis/article-200459746)) | 자사주 매입·소각 규모·시점 미확정 오버행이 여전히 남아 있다 ([2026-11-04 브리핑](2026-11-04-NewsBriefing.md) 참고) | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 방향성 불분명 | 11-05~11-06 | 상승: 美 반도체 대형주 강세와 20조원 자사주 매입(10조원 소각) 등 구체적 환원 계획이 투자심리를 지지할 수 있다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152), [2026-11-04 브리핑](2026-11-04-NewsBriefing.md) 참고)<br>하락: 데이터센터 규제 강화 우려가 국내 반도체 대형주 재평가 부담으로 이어지며 11-04에도 −0.14% 내렸다 ([kr.investing.com(칼럼)](https://kr.investing.com/analysis/article-200459746)) | 삼성전자와 마찬가지로 데이터센터 규제가 구체적 입법으로 확정되면 재차 급락할 수 있다 ([kr.investing.com(칼럼)](https://kr.investing.com/analysis/article-200459746)) | 낮음 — 상승·하락 근거가 팽팽함 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
