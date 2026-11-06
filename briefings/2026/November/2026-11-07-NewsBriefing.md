# 📊 2026-11-07 (토) 주간 요약 — 11-02~11-06

> 생성 07:46 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한 줄 총평
이번 주 코스피는 美 중간선거 이후 'AI 데이터센터 규제 강화' 우려가 반도체 대형주를 덮치며 +2.24%→−3.59%→+0.62%→−5.28%→−6.02%(11-06 개장 직후 서킷브레이커 발동)로 출렁이다 주간 −11.71%(5,730.74→5,059.69)까지 밀렸고, 코스닥도 −11.06%(724.38→644.27) 동반 급락했으며, 美 증시는 11-05 나스닥이 전고점 대비 10% 넘게 빠져 조정장에 진입(주간 S&P500 −2.68%·나스닥 −3.37%)했다가 11-06엔 반등했고, 관심 종목 중에서는 알파벳(+1.73%)이 가장 많이 올랐고 SK하이닉스(−20.17%)가 가장 많이 내렸어요.

## 2. 지수·환율 주간 등락
| 항목 | 이번 주 종가 | 전주 종가 | 주간 등락 | 기준 | 출처 |
|---|---|---|---|---|---|
| KOSPI | 5,059.69 | 5,730.74 | −11.71% | 11-06 vs 10-30 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data), [kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2163468) |
| KOSDAQ | 644.27 | 724.38 | −11.06% | 11-06 vs 10-30 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data), [kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2163468) |
| S&P 500 | 7,376.86 | 7,580.07 | −2.68% | 11-06 vs 10-30 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 24,579.42 | 25,437.00 | −3.37% | 11-06 vs 10-30 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |
| 달러 인덱스 (DXY) | 102.28 | 101.88 | +0.39% | 11-06 vs 10-30 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) |
| USD/JPY | 158.33 | 157.25 | +0.69% | 11-06 vs 10-30 | [Frankfurter/ECB(11-06)](https://api.frankfurter.dev/v1/2026-11-06?from=USD&to=JPY,KRW), [(10-30)](https://api.frankfurter.dev/v1/2026-10-30?from=USD&to=JPY,KRW) |
| USD/KRW | 1,358.73 | 1,335.27 | +1.76% | 11-06 vs 10-30 | [Frankfurter/ECB(11-06)](https://api.frankfurter.dev/v1/2026-11-06?from=USD&to=JPY,KRW), [(10-30)](https://api.frankfurter.dev/v1/2026-10-30?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 858.19 | 849.13 | +1.07% | 11-06 vs 10-30 | [Frankfurter/ECB(11-06)](https://api.frankfurter.dev/v1/2026-11-06?from=JPY&to=KRW), [(10-30)](https://api.frankfurter.dev/v1/2026-10-30?from=JPY&to=KRW) |

<sub>국내·美 증시 모두 이번 주(11-02~11-06)·전주(10-26~10-30) 휴장 없이 각 5거래일 정상 개장([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/); 이번 주 일일 브리핑에서 매일 확인됨). 등락률은 모두 두 종가를 `python3 -c`로 직접 계산(검색 요약·기사 문구는 쓰지 않음). KOSPI·KOSDAQ 11-06 값(5,059.69·644.27, −6.02%·−5.03%)은 [kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2163468)(11-06 16:14) 기사 수치와 일치. 10-30 값은 [2026-10-31 주간 요약](../October/2026-10-31-NewsBriefing.md)에서 확인된 값을 그대로 사용(당시 kr.investing.com 기사 수치와 일치 확인됨). DXY는 Yahoo Finance 히스토리 표 단일 출처로 통일(10-30 101.88, 11-06 102.28); 11-06 페이지에 "Market Open" 표기가 남아 있어 시간대별로 값이 바뀔 수 있음.</sub>

## 3. 관심 종목 주간 성적표 (주간 등락률 순)
**나스닥 시총 Top 3** (11-06 조회 시각 기준, 기준일 표기 없음): 1. 애플 · 2. 엔비디아 · 3. 마이크로소프트 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))

| 순위 | 종목 | 이번 주 종가 | 주간 등락 | 기준 | 출처 |
|---|---|---|---|---|---|
| 1 | 알파벳 (GOOGL) | $284.68 | +1.73% | 11-06 vs 10-30 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) |
| 2 | 마이크로소프트 (MSFT) | $530.62 | +1.67% | 11-06 vs 10-30 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/) |
| 3 | 스페이스X (SPCX) | $134.16 | −0.42% | 11-06 vs 10-30 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) |
| 4 | 애플 (AAPL) | $342.42 | −0.64% | 11-06 vs 10-30 | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/) |
| 5 | 엔비디아 (NVDA) | $186.71 | −8.76% | 11-06 vs 10-30 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) |
| 6 | 테슬라 (TSLA) | $358.20 | −10.41% | 11-06 vs 10-30 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) |
| 7 | AMD | $449.03 | −11.05% | 11-06 vs 10-30 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/) |
| 8 | 삼성전자 | 188,700원 | −16.13% | 11-06 vs 10-30 | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data) |
| 9 | SK하이닉스 | 1,132,000원 | −20.17% | 11-06 vs 10-30 | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data) |

<sub>이번 주(11-06) 종가는 위 링크의 현재 페이지에서, 전주(10-30) 종가는 [2026-10-31 주간 요약](../October/2026-10-31-NewsBriefing.md)에서 이미 출처와 함께 확인된 값을 그대로 사용해 `python3 -c`로 등락률을 계산함. 나스닥 Top 3(애플·엔비디아·마이크로소프트)는 모두 watchlist 3·4번과 중복돼 별도 행을 추가하지 않음.</sub>

- 📈 가장 많이 오른 종목 **알파벳 (+1.73%)**: 구글이 11-06 Crusoe의 와이오밍 데이터센터 부지를 인수하고 170억달러 투자 계획을 발표하며 AI 인프라를 임대 대신 직접 소유하는 쪽으로 전환하고 있음을 보여줬어요. ([investing.com](https://www.investing.com/news/stock-market-news/google-buys-wyoming-data-center-site-as-hyperscalers-move-to-own-ai-capacity-93CH-5009109), 11-06 15:30 ET)
- 📉 가장 많이 내린 종목 **SK하이닉스 (−20.17%)**: 美 중간선거에서 민주당이 상·하원과 주요 데이터센터 입지의 주지사직까지 장악하며 AI 데이터센터 규제 강화 우려가 커졌고, 이것이 HBM·서버용 D램 수요에 부담이 될 수 있다는 분석에 외국인이 11-06 2.77조원 넘게 순매도하며 반도체 대형주 중 가장 큰 폭으로 급락했어요. ([kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2163468), 11-06 16:14)

## 4. 이번 주 주요 뉴스 (최대 5건)
1. **美 증시, AI·반도체 밸류에이션 우려로 2025년 4월 이후 최악의 하루 — 나스닥 조정장 진입** — 11-05(현지) S&P500 -4.36%·나스닥 -5.52%(전고점 대비 10% 넘게 하락)로 급락하며 2025년 4월 이후 최악의 하루를 기록했다. 코어위브·네비우스·IREN 등 데이터센터·AI인프라 관련주가 10% 넘게 급락했고 필라델피아반도체지수는 12% 넘게 밀렸다. 中 투자자들의 "기술주 매수 파업"과 민주당의 의회 장악에 따른 AI 데이터센터 규제 강화 우려가 배경으로 꼽혔다. ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-index-futures-steady-after-midterms-rally-5001919), 11-05 업데이트 16:16)
2. **美 중간선거 "블루웨이브" — 민주당 상·하원 장악, AI 데이터센터 규제 강화 우려 촉발** — 11-04(현지) 개표 결과 민주당이 상·하원을 모두 장악했고 주요 데이터센터 투자 지역인 텍사스 등의 주지사 선거에서도 승리했다. 월가는 처음엔 정치적 불확실성 해소로 랠리(다우 +3.19%)했지만, 데이터센터 건설 규제가 강화될 수 있다는 우려가 이후 반도체·AI 인프라株 전반의 매도세로 이어졌다. ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152), 11-04 15:30; [kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2163468), 11-06 16:14)
3. **코스피·코스닥, 11-06 개장 직후 서킷브레이커 발동 — 주간 두 자릿수 급락, 외국인 2.77조원 순매도** — 코스피는 11-06 개장 3분 만에 8% 넘게 빠지며 1단계 서킷브레이커가 발동돼 매매가 20분간 중단됐고, 결국 6.02% 내린 5,059.69로 마감해 주간 −11.71%를 기록했다. 코스닥도 5.03% 내린 644.27(주간 −11.06%)로 마쳤다. 유가증권시장에서 외국인은 약 2.77조원을 순매도했고, HBM·서버용 D램을 공급하는 삼성전자(주간 −16.13%)·SK하이닉스(주간 −20.17%)가 가장 크게 밀렸다. ([kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2163468), 11-06 16:14)
4. **AMD, 3분기 매출 134억달러·데이터센터 +97%YoY로 가이던스 상회 — 그러나 주간으로는 급락** — AMD는 11-03(현지) 장 마감 후 3분기 매출 134억달러(데이터센터 매출 전년대비 97% 증가)를 발표하며 8월 제시한 가이던스 상단을 웃돌았고 4분기 매출 전망도 월가 예상치보다 높게 제시했다. 시간외·정규장에서 주가가 올랐지만, 다음날(11-05) 업종 전반 밸류에이션 쇼크에 -17.55% 급락하며 주간 전체로는 -11.05%를 기록했다. ([investing.com](https://www.investing.com/news/stock-market-news/amd-forecasts-quarterly-revenue-above-estimates-as-datacenter-growth-accelerates-4996502), 11-03~04)
5. **구글, 와이오밍 데이터센터 부지 인수·170억달러 투자 — 하이퍼스케일러의 AI 인프라 "직접 소유" 전환** — 구글은 11-06 AI 인프라 개발사 Crusoe의 와이오밍 데이터센터 부지를 인수했다고 밝혔다. 전날 해당 프로젝트에 170억달러를 투자하겠다고 발표한 데 이어진 조치로, 전력 확보를 위해 10월에는 Black Hills Energy와 18억달러 규모 천연가스 발전시설(564메가와트) 건설에도 합의했다. 임대보다 직접 소유를 택하는 하이퍼스케일러의 흐름을 보여준 사례로 꼽힌다. ([investing.com](https://www.investing.com/news/stock-market-news/google-buys-wyoming-data-center-site-as-hyperscalers-move-to-own-ai-capacity-93CH-5009109), 11-06 15:30 ET)

## 5. 다음 주 전망 (자체 판단)
**직전 전망 점검:** 직전 주간 요약(2026-10-31)의 전망 13건을 10-30→11-06 종가로 확인한 결과 적중 4건(코스닥 −11.06%·나스닥 −3.37%·엔비디아 −8.76%는 각각 "하락 우세"와 일치, 스페이스X −0.42%는 "하락 우세"와 일치), 빗나감 9건(코스피 −11.71%·S&P500 −2.68%·AMD −11.05%·테슬라 −10.41%·삼성전자 −16.13%는 모두 "방향성 불분명" 예측의 ±1% 밴드를 크게 벗어났고, 애플 −0.64%는 "상승 우세"와 반대, 알파벳 +1.73%는 "하락 우세"와 반대, 마이크로소프트 +1.67%는 "하락 우세"와 반대, SK하이닉스 −20.17%는 "상승 우세"와 반대), 판단 보류 0건. 美 중간선거 후 AI 데이터센터 규제 강화 우려가 예상보다 훨씬 크게 반도체·AI 인프라株 전반을 끌어내리며, 특히 국내 반도체 대형주와 애플·알파벳·마이크로소프트처럼 방향 예측 자체가 반대로 나타난 항목이 많았다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 11-09~11-13 | 상승: NH투자증권 나정환 연구원은 데이터센터 건설·메모리 수요가 견조할 것이며 민주당도 중국과의 AI 경쟁에는 찬성하는 만큼 규제 초점이 건설 제한보다 주민 비용 부담 완화에 있을 것으로 봤다 ([kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2163468))<br>하락: 신영증권 조용구 연구원은 규제가 강화돼 한국·대만 기업 이익이 줄면 수출 둔화 요인이 될 수 있다고 평가했고, 11-06 외국인이 2.77조원을 순매도했다 (같은 기사) | 10월 CPI(11-10)·PPI(11-13) 발표 결과에 따라 美 증시·환율을 통해 변동성이 전이될 수 있다 ([BLS 일정](https://www.bls.gov/schedule/news_release/cpi.htm)) | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 방향성 불분명 | 11-09~11-13 | 상승: 11-06 기관이 코스닥에서 2,043억원을 순매수하며 저가 매수세가 유입됐다 ([kr.investing.com(인포스탁데일리)](https://kr.investing.com/news/stock-market-news/article-2163551))<br>하락: 11-06 외국인·개인이 각각 975억원·1,127억원을 순매도하며 코스피와 같은 규제 우려에 영향을 받았다 (같은 기사) | 코스피와 마찬가지로 10월 CPI·PPI 발표에 따른 변동성 전이 가능성이 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| S&P 500 | 방향성 불분명 | 11-09~11-13 | 상승: 11-06 +0.31% 반등하며 전날 패닉 셀링이 진정되는 모습을 보였고, Deutsche Bank의 Jim Reid는 1946~2022년 중간선거 이후 1년간 S&P500이 매번 상승(평균 +14.4%)했다고 평가했다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152))<br>하락: 나스닥이 조정장에 진입할 정도로 AI 인프라 밸류에이션 재평가 우려가 커졌고, 코어위브·네비우스 등 데이터센터 관련주 급락이 이어지고 있다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-index-futures-steady-after-midterms-rally-5001919)) | 10월 CPI(11-10)·PPI(11-13) 발표 결과에 따라 변동성이 커질 수 있다 ([BLS 일정](https://www.bls.gov/schedule/news_release/cpi.htm)) | 낮음 — 상승·하락 근거가 팽팽함 |
| NASDAQ | 방향성 불분명 | 11-09~11-13 | 상승: AMD가 3분기 데이터센터 매출 +97%YoY·가이던스 상회를 발표했고 11-06 엔비디아도 +2.81% 반등했다 ([investing.com](https://www.investing.com/news/stock-market-news/amd-forecasts-quarterly-revenue-above-estimates-as-datacenter-growth-accelerates-4996502), [stockanalysis.com](https://stockanalysis.com/stocks/nvda/))<br>하락: 전고점 대비 10% 넘게 하락해 조정장에 진입했고, 데이터센터 관련주(코어위브·네비우스·IREN) 급락이 이어지고 있다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-index-futures-steady-after-midterms-rally-5001919)) | 10월 CPI·PPI 발표 결과에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 애플 (AAPL) | 방향성 불분명 | 11-09~11-13 | 상승: 약 70억달러 규모 투자등급 회사채 발행을 추진하며 조달 자금 일부를 자사주 매입에 쓸 계획이다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/))<br>하락: 일부 월가 리서치는 애플의 밸류에이션이 실적 대비 과도하다고 평가했다 ([2026-11-05 브리핑](2026-11-05-NewsBriefing.md) 참고) | AI 밸류에이션 재평가 압력이 대형 기술주 전반으로 확산되면 애플도 영향을 받을 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 엔비디아 (NVDA) | 방향성 불분명 | 11-09~11-13 | 상승: 구글이 170억달러를 투자해 와이오밍 데이터센터 부지를 인수하는 등 하이퍼스케일러의 AI 인프라 투자가 지속되고 있다 ([investing.com](https://www.investing.com/news/stock-market-news/google-buys-wyoming-data-center-site-as-hyperscalers-move-to-own-ai-capacity-93CH-5009109))<br>하락: 中 수출용 H200 칩 약 60만개가 홍콩에 묶여 있고, 의회 지도부가 황 CEO에게 中 정보기관 연계 인물과의 관계를 브리핑 요청했다 ([2026-11-06 브리핑](2026-11-06-NewsBriefing.md) 참고) | 데이터센터 규제가 아직 실제 입법으로 확정된 단계는 아니다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 마이크로소프트 (MSFT) | 상승 우세 | 11-09~11-13 | 1. 클라우드 공급 부족으로 가격을 올릴 여력이 있다는 분석이 나왔다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152))<br>2. 여러 증권사가 Azure 매출 성장(+48%)에 대한 긍정적인 분석을 유지하고 있다 ([2026-10-29 브리핑](../October/2026-10-29-NewsBriefing.md) 참고) | Nebius·IREN·Nscale 등 neocloud 데이터센터 프로젝트에 대한 감독을 강화하고 Nscale과의 대규모 AI 계약 확장은 보류했다는 보도가 있었다 ([2026-11-06 브리핑](2026-11-06-NewsBriefing.md) 참고) | 보통 — 공급부족發 가격 인상 기대·Azure 성장 유지라는 두 독립적 근거 |
| AMD | 방향성 불분명 | 11-09~11-13 | 상승: 3분기 데이터센터 매출이 전년대비 97% 증가했고 2027년 매출 성장률을 애널리스트 예상(77%)보다 높은 80%대로 제시했다 ([investing.com](https://www.investing.com/news/stock-market-news/amd-forecasts-quarterly-revenue-above-estimates-as-datacenter-growth-accelerates-4996502))<br>하락: OpenAI·Meta向 워런트 발행에 따른 비현금성 비용 부담이 있는 가운데, 반도체 업종 전반의 밸류에이션 재평가 우려가 이어지고 있다 ([2026-11-06 브리핑](2026-11-06-NewsBriefing.md) 참고) | 반도체 업종 투자심리가 추가로 악화되면 11-05(−17.55%)와 같은 급락이 재연될 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 알파벳 (GOOGL) | 상승 우세 | 11-09~11-13 | 1. 11-06 Crusoe의 와이오밍 데이터센터 부지를 인수하고 170억달러 투자 계획을 발표하며 AI 인프라를 직접 소유하는 쪽으로 투자를 확대하고 있다 ([investing.com](https://www.investing.com/news/stock-market-news/google-buys-wyoming-data-center-site-as-hyperscalers-move-to-own-ai-capacity-93CH-5009109))<br>2. 전력 확보를 위해 Black Hills Energy와 18억달러 규모 천연가스 발전시설(564메가와트) 건설에 합의했다 (같은 자료) | 美 중간선거 이후 데이터센터 건설 자체에 대한 규제가 강화되면 알파벳의 대규모 인프라 투자 계획에도 부담이 될 수 있다 | 보통 — 데이터센터 부지 인수·전력 확보라는 두 독립적 근거 |
| 테슬라 (TSLA) | 방향성 불분명 | 11-09~11-13 | 상승: 유럽 10월 신차 등록이 이탈리아·포르투갈·스웨덴 등에서 두 자릿수~세 자릿수로 늘었다 ([2026-11-04 브리핑](2026-11-04-NewsBriefing.md) 참고)<br>하락: 민주당의 의회 장악에 따른 머스크 관련 기업 규제·조사 강화 우려가 이번 주 내내 "머스크 셀오프"로 이어졌다 ([2026-11-06 브리핑](2026-11-06-NewsBriefing.md) 참고) | 머스크가 정부 계약이 매출의 10% 미만일 것이라고 밝혀 정부 의존도에 대한 우려를 일부 완화했다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/)) | 낮음 — 상승·하락 근거가 팽팽함 |
| 스페이스X (SPCX) | 상승 우세 | 11-09~11-13 | 1. 머스크는 이번 분기 정부 계약이 매출의 10% 미만일 것이라며 2027년 12월 연환산 매출 약 5,000억달러를 유지한다고 밝혔다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/))<br>2. FAA가 상업 우주발사 규제를 간소화하는 방안을 제안했다 ([2026-11-06 브리핑](2026-11-06-NewsBriefing.md) 참고) | Scottish Mortgage가 SpaceX 비중을 9월 말 15%에서 11.1%로 줄였고, 스페이스X 부채의 신용부도스왑(CDS) 비용이 사상 최고치를 기록했다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/)) | 보통 — 정부 의존도 우려 완화·매출 전망 유지라는 두 독립적 근거 |
| 삼성전자 | 방향성 불분명 | 11-09~11-13 | 상승: 3분기 영업이익이 107조4,000억원으로 분기 기준 사상 최대를 기록했고 반도체(DS) 부문 영업이익률은 72%에 달했다 ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2147418))<br>하락: 신영증권은 데이터센터 규제가 강화되면 한국·대만 반도체 기업 이익이 줄 수 있다고 평가했고, 11-06 외국인이 2.77조원을 순매도했다 ([kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2163468)) | 데이터센터 규제가 아직 실제 입법으로 확정된 단계는 아니다 | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 방향성 불분명 | 11-09~11-13 | 상승: NH투자증권 나정환 연구원은 데이터센터 건설·메모리 수요가 견조할 것으로 전망했고, 2026 회계연도 기준 100조원 규모 주주환원 계획은 유효하다 ([kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2163468))<br>하락: 신영증권 조용구 연구원은 규제 강화시 한국·대만 기업 이익 감소를 전망했고, 11-06 외국인 순매도 속에 반도체 대형주 중 가장 큰 폭으로 급락했다 (같은 기사) | 美 데이터센터 규제가 실제 입법으로 구체화되는지가 다음 주 핵심 변수다 | 낮음 — 상승·하락 근거가 팽팽함 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>주간 등락은 시장별 이번 주·전주 마지막 거래일 종가 기준입니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
