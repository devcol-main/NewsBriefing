# 📈 2026-11-06 (금) 아침 브리핑

> 생성 07:49 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한눈에 (3줄)
- 美 중간선거 이후 AI 데이터센터 규제 강화 우려가 커지며 11-05 미국 증시가 2025년 4월 이후 최악의 하루를 기록했어요. S&P500 -4.36%(7,353.73)·나스닥 -5.52%(24,315.00, 전고점 대비 10% 넘게 빠져 조정장 진입)·다우 -3.4%로 급락했고, 코어위브·엔비디아(-9.14%)·AMD(-17.55%) 등 반도체·AI인프라株가 특히 크게 흔들렸어요. 같은 이유로 코스피(-5.28%, 5,383.80)·코스닥(-5.11%, 678.41)도 외국인 3조3,928억원 순매도 속에 동반 급락했어요.
- 관심 종목 중에서는 AMD가 전날 호실적을 발표했음에도 반도체 업종 전반 매도세에 가장 크게 밀려 -17.55% 내렸고, 테슬라(-10.78%)·스페이스X(-9.22%)는 "머스크 셀오프"로 불리는 동반 매도에 이틀간 시가총액 450억달러가 줄었어요. 삼성전자(-7.57%)·SK하이닉스(-9.46%)도 반도체 대형주 재평가 부담으로 크게 내렸고, 애플(-1.39%)은 그중 하락폭이 가장 작았어요.
- 오늘(KST) 밤에는 美 10월 고용지표(비농업고용)가 발표되고, 전날 급락의 후속 보도와 반도체·AI 인프라株 관련 규제 뉴스가 이어질지 지켜볼 예정이에요.

## 2. 지수
| 지수 | 종가 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| KOSPI | 5,383.80 | −5.28% | 11-05 종가 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 678.41 | −5.11% | 11-05 종가 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 7,353.73 | −4.36% | 11-05 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 24,315.00 | −5.52% | 11-05 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |

<sub>국내·미국 모두 전 거래일은 11-05(목). 11-05~11-06 한국·미국 증시 휴장 없음([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/)). 등락률은 11-04 종가와 `python3 -c`로 직접 계산. S&P500·나스닥은 [investing.com 지수 히스토리](https://www.investing.com/indices/us-spx-500-historical-data)(7,353.79/−4.35%, [나스닥](https://www.investing.com/indices/nasdaq-composite-historical-data) 24,315.00/−5.52%)로 교차 확인했고 Yahoo Finance 값과 실질적으로 일치함.</sub>

## 2-1. 현금·환율
| 항목 | 값 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| 달러 인덱스 (DXY) | 101.59 / 101.475 (불일치) | +0.08% / +0.05% | 11-05 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) / [investing.com](https://www.investing.com/currencies/us-dollar-index-historical-data) |
| USD/JPY | 158.46 | +0.13% | 11-05 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-05?from=USD&to=JPY,KRW) |
| USD/KRW | 1,344.69 | +0.46% | 11-05 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-05?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 848.63 | +0.33% | 11-05 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-05?from=JPY&to=KRW) |

<sub>DXY는 Yahoo Finance 히스토리 표(101.59, 지수)와 investing.com 히스토리 표(101.475, 12월물 선물)가 서로 달라 "불일치"로 표시, 전일 종가는 각각 101.51(Yahoo)·101.425(investing.com). 환율 등락은 직전 고시일 11-04 값(USD/JPY 158.25, USD/KRW 1,338.58, JPY/KRW 845.87)과 비교해 `python3 -c`로 계산([USD](https://api.frankfurter.dev/v1/2026-11-04?from=USD&to=JPY,KRW), [JPY→KRW](https://api.frankfurter.dev/v1/2026-11-04?from=JPY&to=KRW)).</sub>

## 3. 관심 종목
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 애플 · 2. 엔비디아 · 3. 마이크로소프트 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))

| 종목 | 종가 | 등락 | 기준 | 한 줄 메모 | 출처 |
|---|---|---|---|---|---|
| 애플 (AAPL) | $344.65 | −1.39% | 11-05 종가 | 美 중간선거 이후 기술주 전반 매도세 속에서도 관심 종목 중 하락폭이 가장 작았음. 약 70억달러 규모 투자등급 회사채 발행을 추진한다는 보도가 있었음(1년여 만의 첫 채권 발행, 조달금 일부 자사주 매입 활용 예정) | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/) |
| 엔비디아 (NVDA) | $181.84 | −9.14% | 11-05 종가 | 데이터센터 규제 강화 우려와 AI 인프라 투자 지속성 의문 속에 반도체주 매도세에 동참했음. 中 수출용 H200 칩 약 60만개가 홍콩에 묶여 있다는 보도와, 의회 지도부가 황 CEO에게 中 정보기관 연계 인물과의 관계를 브리핑 요청했다는 보도도 부담이었음 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) |
| 마이크로소프트 (MSFT) | $536.21 | −3.52% | 11-05 종가 | Nebius·IREN·Nscale 등 neocloud 데이터센터 프로젝트에 대한 감독을 강화하고, Nscale과의 대규모 AI 계약 확장은 보류했다는 보도가 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/) |
| AMD | $402.99 | −17.55% | 11-05 종가 | 전날 2027년 매출 80%대 성장 전망 등 호실적을 발표했음에도, 반도체 업종 전반(필라델피아반도체지수 −12%대)에 매도세가 확산되며 관심 종목 중 가장 크게 하락했음 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/) |
| 알파벳 (GOOGL) | $282.60 | −2.19% | 11-05 종가 | 구글·메타·틱톡이 캘리포니아 청소년 소셜미디어 규제법에 소송을 냈고, AI 투자 확대 속 비용 절감을 위해 5개국에서 자발적 퇴직 프로그램을 확대했다는 보도가 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) |
| 테슬라 (TSLA) | $343.65 | −10.78% | 11-05 종가 | 민주당의 의회 장악에 따른 머스크 관련 기업 규제·조사 강화 우려로 "머스크 셀오프"가 발생해 테슬라·스페이스X의 이틀간 시가총액이 450억달러 넘게 줄었음 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) |
| 스페이스X (SPCX) | $123.39 | −9.22% | 11-05 종가 | 머스크 관련 규제 우려로 테슬라와 동반 하락했고, 스페이스X 부채에 대한 신용부도스왑(CDS) 비용이 사상 최고치를 기록했다는 보도가 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) |
| 삼성전자 | 201,500원 | −7.57% | 11-05 종가 | 美 데이터센터 규제 우려가 HBM 등 반도체 수요에 영향을 줄 수 있다는 분석과 외국인 대량 매도가 겹쳐 하락했음 | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data) |
| SK하이닉스 | 1,264,000원 | −9.46% | 11-05 종가 | 같은 이유로 관심 종목 중 가장 큰 폭으로 하락했음 | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data) |

## 4. 주요 뉴스 (최대 5건)
1. **美 증시, AI·반도체 밸류에이션 우려로 2025년 4월 이후 최악의 하루 — 나스닥 조정장 진입** — S&P500 -4.3%(7,358.13)·나스닥 -5.5%(24,315.00, 전고점 대비 10% 넘게 하락)·다우 -3.4%(51,521.28)로 마감했다. 코어위브·네비우스·IREN 등 데이터센터·AI인프라 관련주가 10% 넘게 급락했고, 엔비디아(-8.9%)·AMD(17%대)·인텔(10%대)도 하락하며 필라델피아반도체지수는 12% 넘게 밀렸다. 中 투자자들의 "기술주 매수 파업" 상태와 민주당의 의회 장악에 따른 AI 데이터센터 규제 강화 우려가 배경으로 꼽혔다. ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-index-futures-steady-after-midterms-rally-5001919), 11-05(현지) 업데이트 16:16)
2. **코스피·코스닥, 반도체주 급락에 5%대 동반 하락 — 외국인 3조3,928억원 순매도** — 코스피는 전 거래일보다 300p(5.28%) 내린 5,383.80에, 코스닥은 36.54p(5.11%) 내린 678.41에 마감했다. 삼성전자(-7.57%)·SK하이닉스(-9.46%) 등 반도체 대형주가 지수를 끌어내렸고, 데이터센터 규제 강화가 HBM 등 반도체 수요에 악영향을 줄 수 있다는 우려가 배경으로 지목됐다. 장중에는 코스피200 선물 급락으로 매도 사이드카가 발동됐다. 개인·기관은 각각 2조2,722억원·8,457억원을 순매수해 물량을 받아냈다. ([kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2160976), 11-05 22:57)
3. **엔비디아, 中 수출 칩 적체·의회 브리핑 요청 속 -9.14%** — 中 수출용 H200 칩 약 60만개가 홍콩에 묶여 있다는 보도가 나왔고, 의회 지도부는 젠슨 황 CEO에게 中 정보기관과 연관된 것으로 알려진 기술 업계 임원과의 관계에 대한 브리핑을 요청했다. 반도체 규제 강화 우려와 함께 기술주 전반 매도세를 압박했다. ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/), 11-05)
4. **"머스크 셀오프" — 테슬라·스페이스X 동반 급락, 이틀간 시총 450억달러 감소** — 민주당의 의회 장악으로 머스크 관련 기업에 대한 규제·조사 강화 우려가 커지며 테슬라(-10.78%)·스페이스X(-9.22%)가 동반 하락했다. GLJ리서치는 두 회사의 합병 가능성이 더 느리고 비싸지고 낮아졌다고 평가했고, 스페이스X 부채의 신용부도스왑(CDS) 비용은 사상 최고치를 기록했다. ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/), [stockanalysis.com](https://stockanalysis.com/stocks/spcx/), 11-05)
5. **애플, 투자등급 회사채 약 70억달러 발행 추진 — 1년여 만의 첫 채권 발행** — 로이터·블룸버그에 따르면 애플이 약 70억달러 규모 달러 회사채 발행을 추진하고 있으며, 조달 자금 일부를 자사주 매입에 쓸 계획이다. 같은 날 애플 주가는 -1.39%로 관심 종목 중 하락폭이 가장 작았다. ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/), 11-05)

## 5. 오늘 일정
- 美 10월 고용지표(비농업고용, Employment Situation), 현지 11-06 오전 8:30 ET(한국시간 11-06 밤 10시 30분경) 발표 예정 ([BLS 11월 일정](https://www.bls.gov/schedule/2026/11_sched_list.htm))
- 전날(11-05) AI·반도체 밸류에이션 쇼크의 후속 보도와 데이터센터 규제 관련 뉴스가 이어질 수 있음 ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-index-futures-steady-after-midterms-rally-5001919))
- 국내·미국 증시 휴장 없음 ([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/))

## 6. 전망 (자체 판단)
**직전 전망 점검:** 직전 일일 브리핑(2026-11-05)의 전망 13건을 11-04→11-05 종가로 확인한 결과 적중 0건, 빗나감 13건(전부), 판단 보류 0건. KOSPI·KOSDAQ·S&P500·NASDAQ·애플·엔비디아·테슬라·스페이스X·삼성전자·SK하이닉스의 "방향성 불분명"(±0.5% 밴드) 예측은 실제 −1.39%~−10.78%의 큰 하락폭에 모두 밴드를 벗어났고, 마이크로소프트·AMD·알파벳의 "상승 우세" 예측도 실제로는 모두 하락해 반대로 빗나갔다. 美 중간선거 후 AI 데이터센터 규제 강화 우려가 예상보다 훨씬 크게 반도체·AI 인프라株 전반을 끌어내리며 거의 모든 항목이 예측 범위를 크게 벗어났다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 11-06~11-09 | 상승: 11-05 급락 당일 개인이 2조2,722억원, 기관이 8,457억원을 순매수하며 물량을 받아내는 수급 완충이 있었다 ([kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2160976))<br>하락: 외국인이 3조3,928억원을 순매도하며 하락을 주도했고, 데이터센터 규제 우려에 따른 반도체 대형주 재평가 부담이 이어지고 있다 (같은 기사) | 美 10월 고용지표가 이날 밤(KST) 발표돼 그 결과에 따라 변동성이 커질 수 있다 ([BLS 일정](https://www.bls.gov/schedule/2026/11_sched_list.htm)) | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 방향성 불분명 | 11-06~11-09 | 상승: 개인이 1,720억원을 순매수하며 저가 매수세가 유입됐다 ([kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2160976))<br>하락: 외국인·기관이 각각 734억원·1,026억원을 순매도하며 매도 압력이 이어졌다 (같은 기사) | 美 고용지표 결과에 따라 밤사이 변동성이 커질 수 있다 ([BLS 일정](https://www.bls.gov/schedule/2026/11_sched_list.htm)) | 낮음 — 상승·하락 근거가 팽팽함 |
| S&P 500 | 방향성 불분명 | 11-06~11-09 | 상승: AMD가 2027년 매출 성장률 전망을 애널리스트 예상(77%)보다 높은 80%대로 제시하고 데이터센터 매출이 전년대비 97% 증가했다고 밝혀, AI 반도체 수요 자체의 펀더멘털은 아직 견조하다는 근거가 남아 있다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-index-futures-steady-after-midterms-rally-5001919))<br>하락: 나스닥이 전고점 대비 10% 넘게 하락해 조정장에 진입했고, 코어위브·네비우스·IREN 등 AI 인프라株가 10% 넘게 급락하며 필라델피아반도체지수도 12% 넘게 밀렸다 (같은 기사) | 美 10월 고용지표 결과에 따라 변동성이 커질 수 있다 ([BLS 일정](https://www.bls.gov/schedule/2026/11_sched_list.htm)) | 낮음 — 상승·하락 근거가 팽팽함 |
| NASDAQ | 방향성 불분명 | 11-06~11-09 | 상승: AMD의 2027년 매출 성장률 전망 상향(80%대)과 데이터센터 매출 97% 증가는 AI 반도체 수요의 펀더멘털이 유지되고 있음을 보여준다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-index-futures-steady-after-midterms-rally-5001919))<br>하락: 나스닥이 조정장(전고점 대비 -10%+)에 진입했고, AI 인프라·반도체株 전반(필라델피아반도체지수 -12%+)에 매도세가 확산되고 있다 (같은 기사) | 美 10월 고용지표 결과에 따라 변동성이 커질 수 있다 ([BLS 일정](https://www.bls.gov/schedule/2026/11_sched_list.htm)) | 낮음 — 상승·하락 근거가 팽팽함 |
| 애플 (AAPL) | 방향성 불분명 | 11-06~11-09 | 상승: 약 70억달러 규모 투자등급 회사채 발행을 추진한다는 보도가 있었고, 조달 자금 일부를 자사주 매입에 활용할 계획이다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/))<br>하락: 나스닥 전반의 AI 밸류에이션 재평가 매도세가 지속되고 있고, 일부 엔지니어의 AI 사용 지출 한도를 낮췄다는 보도로 AI 투자 효율에 대한 의문도 제기됐다 (같은 자료) | 美 고용지표 결과에 따른 시장 전반 변동성 | 낮음 — 상승·하락 근거가 팽팽함 |
| 엔비디아 (NVDA) | 방향성 불분명 | 11-06~11-09 | 상승: Box와 AI 검색·워크플로 도구 파트너십을 확대한다고 발표했다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/))<br>하락: 中 수출용 H200 칩 약 60만개가 홍콩에 묶여 있다는 보도와, 의회 지도부가 황 CEO에게 中 정보기관 연계 인물과의 관계를 브리핑 요청했다는 보도가 겹치며 규제 불확실성이 커졌다 (같은 자료) | 데이터센터 규제가 아직 실제 입법으로 확정된 단계는 아니며, 고용지표 결과도 변수다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 마이크로소프트 (MSFT) | 방향성 불분명 | 11-06~11-09 | 상승: 클라우드 공급 부족으로 가격을 올릴 여력이 있다는 분석이 나왔다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-319-5001152))<br>하락: Nebius·IREN·Nscale 등 neocloud 데이터센터 프로젝트에 대한 감독을 강화하고, Nscale과의 대규모 AI 계약 확장은 보류했다는 보도가 있었다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/)) | 美 고용지표 결과에 따른 시장 전반 변동성 | 낮음 — 상승·하락 근거가 팽팽함 |
| AMD | 방향성 불분명 | 11-06~11-09 | 상승: 2027년 매출 성장률 전망을 애널리스트 예상(77%)보다 높은 80%대로 제시했고 데이터센터 매출은 전년대비 97% 증가했다고 밝혔다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stock-index-futures-steady-after-midterms-rally-5001919))<br>하락: OpenAI·Meta向 워런트 발행에 따른 비현금성 비용 부담이 있는 가운데, 반도체 업종 전반(필라델피아반도체지수 -12%대)에 매도세가 확산되고 있다 (같은 기사) | 美 고용지표 결과에 따른 시장 전반 변동성 | 낮음 — 상승·하락 근거가 팽팽함 |
| 알파벳 (GOOGL) | 방향성 불분명 | 11-06~11-09 | 상승: 2027~2028년 말레이시아에 150억달러를 투자해 데이터센터 등 인프라를 확충한다고 발표했다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/))<br>하락: 구글·메타·틱톡이 캘리포니아 청소년 소셜미디어 규제법에 소송을 냈고, AI 투자 확대 속 비용 절감을 위해 5개국에서 자발적 퇴직 프로그램을 확대했다는 보도가 있었다 (같은 자료) | 美 고용지표 결과에 따른 시장 전반 변동성 | 낮음 — 상승·하락 근거가 팽팽함 |
| 테슬라 (TSLA) | 방향성 불분명 | 11-06~11-09 | 상승: 유럽 10월 신차 등록이 이탈리아·포르투갈·스웨덴 등에서 두 자릿수~세 자릿수로 늘었다는 집계가 있었다 ([2026-11-04 브리핑](2026-11-04-NewsBriefing.md) 참고)<br>하락: 민주당의 의회 장악에 따른 머스크 관련 기업 규제·조사 강화 우려로 "머스크 셀오프"가 발생해 테슬라·스페이스X의 이틀간 시가총액이 450억달러 넘게 줄었고, 한국에서는 FSD(감독형 완전자율주행) 소프트웨어를 오해 소지 있게 판매했다는 소비자단체의 고발 계획도 보도됐다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/)) | 테슬라-스페이스X 합병 논의가 재개되면 밸류에이션 재평가 기대가 되살아날 수 있으나, GLJ리서치는 합병 가능성이 더 낮아졌다고 평가했다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 스페이스X (SPCX) | 방향성 불분명 | 11-06~11-09 | 상승: FAA가 상업 우주발사 규제를 간소화하는 방안을 제안했고, 퀄컴과 미국 전역 5G 통신 인프라(Dragonwing) 다년 계약을 체결했다는 보도가 있었다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/))<br>하락: 머스크 관련 기업 규제 우려로 테슬라와 동반 하락했고, 스페이스X 부채에 대한 신용부도스왑(CDS) 비용이 사상 최고치를 기록했다는 보도가 있었다 (같은 자료) | 테슬라-스페이스X 합병 가능성이 낮아졌다는 평가가 추가 부담 요인이 될 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 삼성전자 | 방향성 불분명 | 11-06~11-09 | 상승: 3분기 영업이익이 107조4,000억원으로 전년 동기 대비 782.5% 늘어 분기 기준 사상 최대를 기록했다 ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2147418))<br>하락: 美 데이터센터 규제 강화 우려가 HBM 등 반도체 수요에 영향을 줄 수 있다는 분석과 외국인 대량 매도가 이어지고 있다 ([kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2160976)) | 美 고용지표 결과에 따른 시장 전반 변동성 | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 방향성 불분명 | 11-06~11-09 | 상승: 2026 회계연도 기준 현금배당 30조원 이상·자사주 매입소각 60조원 이상 등 총 100조원 규모 주주환원 계획을 발표했다 ([mt.co.kr](https://www.mt.co.kr/industry/2026/10/28/2026102807433474996))<br>하락: 같은 데이터센터 규제 우려 속 외국인·기관 매도가 이어지며 관심 종목 중 가장 큰 폭(-9.46%)으로 하락했다 ([kr.investing.com(EBN)](https://kr.investing.com/news/stock-market-news/article-2160976)) | 美 고용지표 결과에 따른 시장 전반 변동성 | 낮음 — 상승·하락 근거가 팽팽함 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
