# 🗓 2026-10-31 10월 월간 브리핑 (Monthly Briefing)

> 생성 07:50 KST · 대상 기간 10월 · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한 달 총평 (3줄)
- 10월은 美 CPI 쇼크發 "검은 목요일"(10-15) 폭락과 SK하이닉스의 역대 실적·100조원 주주환원(10-28~29)에 이은 알파벳 실적쇼크·인텔 가이던스발 반도체 재급락(10-29~30)까지 겹치며 등락이 극심했고, 코스피 −16.19%·코스닥 −15.37%로 국내 지수가 S&P500 −0.93%·나스닥 −5.30%보다 훨씬 크게 밀렸어요.
- 관심 종목 중 테슬라가 +12.68%로 가장 많이 올랐고, SK하이닉스가 −20.16%로 가장 많이 내렸어요.
- 11월에는 애플(11-02)·AMD(11-03)·엔비디아(11-17) 실적과 美 10월 고용보고서(11-06)·CPI(11-10)가 먼저 예정돼 있어요.

## 2. 지수·환율 월간 등락
| 항목 | 월말 종가 | 전월말 종가 | 월간 등락 | 기준 | 출처 |
|---|---|---|---|---|---|
| KOSPI | 5,730.74 | 6,838.04 | −16.19% | 10-30 vs 09-30 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data), [kr.investing.com 기사](https://kr.investing.com/news/stock-market-news/article-2150642) |
| KOSDAQ | 724.38 | 855.91 | −15.37% | 10-30 vs 09-30 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data), [kr.investing.com 기사](https://kr.investing.com/news/stock-market-news/article-2150642) |
| S&P 500 | 7,580.07 | 7,651.54 | −0.93% | 10-30 vs 09-30 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 25,437.00 | 26,861.06 | −5.30% | 10-30 vs 09-30 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |
| 달러 인덱스 (DXY) | 101.96 | 101.45 | +0.50% | 10-30 vs 09-30 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) |
| USD/JPY | 157.25 | 157.00 | +0.16% | 10-30 vs 09-30 ECB 기준환율 | [Frankfurter/ECB(10-30)](https://api.frankfurter.dev/v1/2026-10-30?from=USD&to=JPY,KRW), [(09-30)](https://api.frankfurter.dev/v1/2026-09-30?from=USD&to=JPY,KRW) |
| USD/KRW | 1,335.27 | 1,355.40 | −1.49% | 10-30 vs 09-30 ECB 기준환율 | [Frankfurter/ECB(10-30)](https://api.frankfurter.dev/v1/2026-10-30?from=USD&to=JPY,KRW), [(09-30)](https://api.frankfurter.dev/v1/2026-09-30?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 849.13 | 863.33 | −1.64% | 10-30 vs 09-30 ECB 기준환율 (JPY→KRW ×100) | [Frankfurter/ECB(10-30)](https://api.frankfurter.dev/v1/2026-10-30?from=JPY&to=KRW), [(09-30)](https://api.frankfurter.dev/v1/2026-09-30?from=JPY&to=KRW) |

<sub>월간 등락률은 두 종가로 직접 계산(`python3 -c`). KOSPI·KOSDAQ 10-30 값(5,730.74·724.38)은 [kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2150642)(10-30 16:29) 기사 수치와 일치. 09-30 값(6,838.04·855.91 등)은 [2026-09-30 월간 브리핑](../September/2026-09-30-NewsBriefing-Monthly.md)에서 확인된 값을 그대로 사용(당시 머니투데이 기사 수치와 일치 확인됨).</sub>

## 3. 관심 종목 월간 성적표
월간 등락률 내림차순. 나스닥 시총 Top 3(10-30 조회 기준: 애플·엔비디아·마이크로소프트, [stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))와 `watchlist.md` 3·4번 종목(중복인 마이크로소프트는 한 번만 표기).

| 종목 | 월말 종가 | 전월말 종가 | 월간 등락 | 기준 | 출처 |
|---|---|---|---|---|---|
| 테슬라 (TSLA) | $399.81 | $354.81 | +12.68% | 10-30 vs 09-30 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/), [Yahoo Finance(09-30)](https://finance.yahoo.com/quote/TSLA/history/) |
| 애플 (AAPL) | $344.63 | $333.02 | +3.49% | 10-30 vs 09-30 | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/), [Yahoo Finance(09-30)](https://finance.yahoo.com/quote/AAPL/history/) |
| 마이크로소프트 (MSFT) | $521.91 | $512.90 | +1.76% | 10-30 vs 09-30 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/), [Yahoo Finance(09-30)](https://finance.yahoo.com/quote/MSFT/history/) |
| 엔비디아 (NVDA) | $204.64 | $228.38 | −10.39% | 10-30 vs 09-30 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/), [Yahoo Finance(09-30)](https://finance.yahoo.com/quote/NVDA/history/) |
| 스페이스X (SPCX) | $134.72 | $150.86 | −10.70% | 10-30 vs 09-30 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/), [Yahoo Finance(09-30)](https://finance.yahoo.com/quote/SPCX/history/) |
| AMD | $504.80 | $611.76 | −17.48% | 10-30 vs 09-30 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/), [Yahoo Finance(09-30)](https://finance.yahoo.com/quote/AMD/history/) |
| 삼성전자 | 225,000원 | 268,500원 | −16.20% | 10-30 vs 09-30 | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data), [Yahoo Finance(09-30)](https://finance.yahoo.com/quote/005930.KS/history/) |
| 알파벳 (GOOGL) | $279.84 | $344.08 | −18.67% | 10-30 vs 09-30 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/), [Yahoo Finance(09-30)](https://finance.yahoo.com/quote/GOOGL/history/) |
| SK하이닉스 | 1,418,000원 | 1,776,000원 | −20.16% | 10-30 vs 09-30 | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data), [Yahoo Finance(09-30)](https://finance.yahoo.com/quote/000660.KS/history/) |

<sub>엔비디아는 `watchlist.md` 고정 종목이 아니라 나스닥 시총 2위(10-30 기준)로 포함했다. 09-30 값은 [2026-09-30 월간 브리핑](../September/2026-09-30-NewsBriefing-Monthly.md)의 값을 그대로 사용.</sub>

- **상위 테슬라 (+12.68%):** 바클레이즈 애널리스트의 평가 상향과 스페이스X 합병 기대감, 3분기 실적 개선(FSD 구독자 +67%)이 겹치며 10월 중후반 급등했어요. ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 Investopedia·TipRanks 기사, 10-21~26)
- **하위 SK하이닉스 (−20.16%):** 10-15 "검은 목요일" 급락(−11.06%)과 10-30 인텔발 반도체 업종 재평가(−7.08%)의 충격이 10-28~29 역대 실적·100조원 주주환원 발표에 따른 반등분을 넘어서며 월간 기준으로는 가장 많이 내렸어요. ([2026-10-16 브리핑](2026-10-16-NewsBriefing.md), [2026-10-30 브리핑](2026-10-30-NewsBriefing.md) 참고)

## 4. 이달의 주요 이슈 (최대 5건)
1. **美 CPI 쇼크發 "검은 목요일"(10-15), 코스피·코스닥 동반 폭락·사이드카·서킷브레이커 발동** — 美 9월 CPI가 예상(3.6%)을 웃돈 3.7%(YoY)로 나오며 반도체주가 일제히 급락(필라델피아 반도체지수 −4.30%)했고, AI 투자 수익성 논란(코어위브 채권가 하락)과 美 10년물 국채수익률 5.3%대까지 겹치며 10-15 코스피 −7.57%(5,554.22)·코스닥 −7.65%(760.82)로 동반 폭락, 양 시장에 매도 사이드카·서킷브레이커가 발동됐다. SK하이닉스(−11.06%)·삼성전자(−9.48%)는 3분기 역대급 실적에도 두 자릿수대로 급락했다. ([2026-10-16 브리핑](2026-10-16-NewsBriefing.md) 참고)
2. **한국은행, 기준금리 연 3.00% 만장일치 동결(10-22) — "통화긴축 기조 유지"** — 금융통화위원 7명 전원이 동결에 찬성했다. 7·8월 두 차례 연속 인상 이후 효과를 점검하기 위한 "숨고르기"로 풀이됐고, 신현송 총재는 성장·물가 흐름이 8월 전망보다 강한 만큼 통화긴축 기조는 이어가겠다고 밝혔다. ([머니투데이](https://www.mt.co.kr/economy/2026/10/22/2026102209323421102), 10-22 09:32)
3. **SK하이닉스, 3분기 역대 실적에 "100조원" 주주환원 발표(10-28) — 코스피 10거래일 만에 6000선 회복** — SK하이닉스는 3분기 영업이익이 시장 컨센서스(77조원)를 웃도는 역대 최대(83조3,338억원)를 기록했고, 20조원 자사주 매입(10조원 소각) 등 60조원 추가 환원을 포함해 올해 총 100조원 규모 주주환원 계획을 내놓았다. 반도체 대형주로 매수세가 몰리며 10-28 코스피는 10거래일 만에 6000선을 회복했다. ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2144989), 10-28 22:21)
4. **삼성전자, 3분기 영업이익 107조원 역대 최대지만 자사주 계획 미확정에 급락(10-29)** — 삼성전자는 3분기 매출 195조2,532억원, 영업이익 107조4,405억원(4개 분기 연속 사상 최대)을 발표했다. 총주주환원 목표(90조~110조원)는 재확인했지만 자사주 매입·소각 규모·시점은 밝히지 않아(최종안은 내년 1월 말 이사회 결정) 실망 매물이 쏟아지며 하루 −4.13% 급락했다. ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2147515), 10-29 13:54)
5. **알파벳 3분기 실적쇼크·인텔 약한 가이던스 겹치며 월말 반도체·빅테크 재급락 — 애플, 엔비디아 제치고 시총 1위 복귀** — 알파벳은 10-28(현지) 3분기 EPS가 컨센서스를 크게 밑돌고 FCF가 적자 전환했다고 밝혀 10-29 하루 12.64% 폭락(시총 약 5,000억달러 증발)했고, 10-30에는 인텔의 약한 4분기 가이던스로 AMD(−10.88%)·엔비디아(−4.22%)가 동반 급락했다. 그 결과 애플이 시총 약 5.03조달러로 엔비디아를 제치고 세계 최고 시가총액 기업에 다시 올랐다. 이에 앞서 10-28 FOMC는 기준금리를 3.75~4.00%로 동결했다(10대2). ([kr.investing.com](https://kr.investing.com/news/assorted/article-2150194), 10-30 07:23; [kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2152161), 10-31 06:17; [Federal Reserve](https://www.federalreserve.gov/newsevents/pressreleases/monetary20261028a.htm), 10-28)

## 5. 다음 달(11월) 일정·주목 포인트
| 날짜 (KST) | 일정 | 출처 |
|---|---|---|
| 11-02 (월) | 애플(AAPL) FY2026 4분기 실적 발표 (현지 장 마감 후) | [stockanalysis.com AAPL](https://stockanalysis.com/stocks/aapl/) |
| 11-03 (화) 24:00 | 美 9월 JOLTS(구인·이직보고서) (10:00 ET) | [BLS](https://www.bls.gov/schedule/news_release/) |
| 11-03 (화) | AMD 3분기 실적 발표 (현지 장 마감 후) | [2026-10-29 브리핑](2026-10-29-NewsBriefing.md), [2026-10-30 브리핑](2026-10-30-NewsBriefing.md) 참고 |
| 11-05 (목) 22:30 | 美 3분기 생산성·단위노동비용 잠정치 (8:30 ET) | [BLS](https://www.bls.gov/schedule/news_release/) |
| 11-06 (금) 22:30 | 美 10월 고용보고서(비농업고용·실업률) (8:30 ET) | [BLS](https://www.bls.gov/schedule/news_release/) |
| 11-10 (화) 22:30 | 美 10월 CPI (8:30 ET) | [BLS](https://www.bls.gov/schedule/news_release/) |
| 11-11 (수) | 美 베테랑스데이 — 증시는 정상 개장 | [BLS 일정](https://www.bls.gov/schedule/news_release/) (발표 없음) |
| 11-13 (금) 22:30 | 美 10월 PPI (8:30 ET) | [BLS](https://www.bls.gov/schedule/news_release/) |
| 11-17 (화) | 엔비디아(NVDA) 3분기 실적 발표 (현지 장 마감 후) | [2026-10-29 브리핑](2026-10-29-NewsBriefing.md) 참고 (GlobeNewswire 보도자료, 10-28) |
| 11월 | FOMC 회의 없음 — 다음 정례회의 12-08~09 | [Federal Reserve](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) |
| 11-26 (목) | 美 추수감사절 — NYSE·NASDAQ 휴장 | [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/) |
| 11-27 (금) | 美 증시 조기 폐장 (13:00 ET) | [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/) |
| 11월 | 국내(KRX) 휴장일 없음 | [kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/) |
| 11월 | 한국은행 금통위 일정 — 확인 필요 | 확인 필요 |
| 11월 | ISM 11월 제조업·서비스업 PMI 발표일 — 확인 필요(사이트 접근 제한으로 미확인) | 확인 필요 |

**시장에서 주목하는 변수 (최대 3개)**
- 시장에서는 11-03 AMD, 11-17 엔비디아의 3분기 실적이 인텔발 반도체 재평가 우려를 해소할 수 있을지에 주목하고 있다. ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 TipRanks·MarketWatch 기사, 10-30)
- 시장에서는 11-02 애플 4분기 실적이 엔비디아를 제치고 되찾은 시총 세계 1위 지위를 지지할 수 있을지에 주목하고 있다. ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2152161), 10-31)
- 시장에서는 11-06 美 10월 고용보고서와 11-10 CPI가 12-08~09 FOMC의 통화정책 경로에 어떤 영향을 줄지에 주목하고 있다. ([Federal Reserve](https://www.federalreserve.gov/newsevents/pressreleases/monetary20261028a.htm))

<sub>5번 섹션은 확인된 일정과 출처가 있는 제3자 예상치만 담았으며, 자체 전망은 6번 섹션에만 있습니다.</sub>

## 6. 다음 달(11월) 전망 (자체 판단)
**직전 전망 점검:** 직전 월간 브리핑(2026-09-30)의 전망 13건을 09-30→10-30 종가로 확인한 결과 적중 1건(S&P500 −0.93%는 "방향성 불분명" 예측의 ±2% 밴드 안), 빗나감 6건(코스피 −16.19%·코스닥 −15.37%는 모두 "방향성 불분명" 예측의 ±2% 밴드를 크게 벗어났고, 나스닥 −5.30%·엔비디아 −10.39%·삼성전자 −16.20%·SK하이닉스 −20.16%는 모두 "상승 우세" 예측과 반대), 판단 보류 6건(애플·알파벳·마이크로소프트·테슬라·AMD·스페이스X, 집계 제외). 10-15 "검은 목요일" 폭락이 예상 범위를 완전히 벗어난 규모였고, 메모리 공급 호재로 상승을 예상했던 반도체 대형주들이 CPI 쇼크·자금조달 우려로 오히려 가장 크게 하락해 예측이 크게 빗나갔다.

| 대상 | 방향 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 1. 10-30 개인·기관이 코스피에서 순매수하며 외국인 순매도를 일부 상쇄했고, SK하이닉스는 구체적 환원 계획을 이미 발표했다 ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2150642))<br>2. 반면 외국인 순매도가 10월 내내 반복됐고 삼성전자의 자사주 계획 미확정 불확실성이 내년 1월 말까지 이어진다 (4번 섹션, [kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2147515)) | 인텔발 글로벌 반도체 재평가가 11월에도 이어지면 코스피 반도체 대형주에 추가 부담이 전이될 수 있다 (5번 섹션) | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 하락 우세 | 1. 10월 내내 코스피보다 더 큰 폭으로 출렁이는 디커플링이 반복됐다(10-15 −7.65%, 10-30 −3.83% 등 다수 세션에서 확인, 본문 2번 섹션)<br>2. 10-30 외국인·기관이 코스닥에서 동반 순매도했다 ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2150642)) | 개인 투자자의 저가매수세가 반복적으로 유입되고 있어 반등 재료가 될 수 있다 (같은 기사) | 보통 — 반복된 디커플링·수급 악화라는 두 독립적 근거 |
| S&P 500 | 방향성 불분명 | 1. 美 3분기 GDP가 +3.4%로 가속됐고, 애플이 시총 세계 1위로 복귀하며 비기술 대형주·러셀2000으로 로테이션 매수가 유입되고 있다 ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2152161))<br>2. 인텔의 약한 4분기 가이던스로 반도체·AI 투자 수익성 우려가 재부각됐고, 9월 PCE 물가가 여전히 높아(3.6%) Fed 긴축 장기화 우려가 남아있다 ([BEA](https://www.bea.gov/news/2026/personal-income-and-outlays-september-2026)) | 11-02·11-03·11-17 애플·AMD·엔비디아의 실적 발표 결과에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| NASDAQ | 하락 우세 | 1. 인텔의 약한 4분기 가이던스로 AMD(−10.88%)·엔비디아(−4.22%) 등 반도체 대형주 전반의 재평가 우려가 10월 말 커졌다 (5번 섹션)<br>2. 알파벳 실적쇼크 여진과 아마존의 12개월 누적 FCF 적자(424억달러)가 겹치며 AI 투자 수익성 논란이 이어지고 있다 ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2152161)) | 애플이 시총 세계 1위로 복귀하며 안전자산 선호 자금이 대형 기술주 내에서도 쏠릴 수 있고, 11월 AMD·엔비디아 실적이 우려를 해소하면 반등할 수 있다 | 보통 — 반도체 재평가·빅테크 캐시번 우려라는 두 독립적 근거 |
| 엔비디아 (NVDA) | 하락 우세 | 1. 美 법무부(DOJ)가 129억달러 규모 허깅페이스 인수 건을 반독점 심사 중이다 ([2026-10-30 브리핑](2026-10-30-NewsBriefing.md) 참고)<br>2. 인텔의 약한 4분기 가이던스로 반도체 업종 전반 재평가 우려가 커지며 10월 말 −4.22% 내렸고, 10월 한 달로는 −10.39%를 기록했다 (본문 3번 섹션) | 엔비디아는 DOJ 조사·NYT의 중국 정보기관 연계 보도 모두를 반박했고, 11-17 실적 발표에서 네오클라우드 수요 견조함이 확인되면 반등할 수 있다 ([2026-10-26 브리핑](2026-10-26-NewsBriefing.md) 참고) | 보통 — DOJ 심사·업종 재평가 우려라는 두 독립적 근거 |
| 애플 (AAPL) | 상승 우세 | 1. 기술주 매도 속 로테이션 수혜주로 꼽히며 시가총액 세계 1위(약 5.03조달러)로 엔비디아를 제쳤다 (5번 섹션, [kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2152161))<br>2. WSJ는 AI 수요 확대로 애플의 칩 공급업체 대비 협상력이 오히려 높아지고 있다고 분석했다 (같은 기사) | 11-02 예정된 4분기 실적 발표 결과에 따라 변동성이 커질 수 있다 | 보통 — 로테이션 수혜·협상력 개선이라는 두 독립적 근거 |
| 마이크로소프트 (MSFT) | 하락 우세 | 1. 약 250억달러 규모 투자등급 채권(9년여 만의 첫 발행) 발행 계획과 AI 지출 전망을 1,700억달러로 상향했다는 보도에 자본지출 부담 우려가 부각됐다 ([2026-10-30 브리핑](2026-10-30-NewsBriefing.md) 참고)<br>2. Griffin Securities는 투자의견을 매수에서 중립으로 낮췄다 (같은 자료) | 여러 증권사가 Azure 매출 성장(+48%)에 대한 긍정적인 분석을 유지하고 있다 ([2026-10-29 브리핑](2026-10-29-NewsBriefing.md) 참고) | 보통 — 자본지출 부담·투자의견 하향이라는 두 독립적 근거 |
| 알파벳 (GOOGL) | 하락 우세 | 1. 3분기 EPS가 컨센서스를 크게 밑돌았고 FCF가 적자 전환했으며, 최근 분기보고서에서 잠재적 금융 의무가 985억달러로 석 달 전보다 약 230억달러 늘어난 것으로 공개됐다 (본문 3·4번 섹션)<br>2. 10월 한 달 −18.67%로 관심 종목 중 가장 크게 내렸다 (본문 3번 섹션) | Scotiabank는 매수 의견을 유지했고 2027년 자본지출 계획을 상향했으며, 구글클라우드 매출은 전년대비 103% 성장했다 ([2026-10-30 브리핑](2026-10-30-NewsBriefing.md) 참고) | 보통 — 실적쇼크·재무 부담 증가라는 두 독립적 근거 |
| AMD | 방향성 불분명 | 상승: Bernstein 애널리스트가 Outperform 등급을 유지했다 ([2026-10-30 브리핑](2026-10-30-NewsBriefing.md) 참고)<br>하락: 인텔의 약한 4분기 가이던스로 10-30 −10.88% 폭락했고, 10월 한 달로는 −17.48% 내렸다 (본문 3번 섹션) | 11-03 AMD 자체의 3분기 실적 발표 결과에 따라 변동성이 매우 커질 수 있다 | 낮음 — 상승 근거가 약하고(의견 유지 수준), 하락 근거가 더 뚜렷함 |
| 테슬라 (TSLA) | 방향성 불분명 | 상승: 바클레이즈 애널리스트의 평가 상향과 스페이스X 합병 기대감, 3분기 실적 개선이 겹치며 10월 한 달 +12.68%로 가장 많이 올랐다 (본문 3번 섹션)<br>하락: 재설계된 로드스터의 스러스터 시연이 다소 실망스러웠다는 평가가 있었고, 기술주 전반 매도 여파로 10월 말 소폭 내렸다 ([2026-10-29 브리핑](2026-10-29-NewsBriefing.md) 참고) | 스페이스X와의 합병 논의가 11월에 진전되면 밸류에이션 재평가 기대로 주가가 반응할 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 스페이스X (SPCX) | 하락 우세 | 1. Barron's는 최근 기술주 실적이 AI 트레이드를 흔들고 있으며 다른 어떤 기업도 머스크의 높은 기준을 충족하지 못한다고 평가했다 ([2026-10-30 브리핑](2026-10-30-NewsBriefing.md) 참고)<br>2. 바이낸스가 약 10억달러 규모 스페이스X 지분을 보유한 사실이 공개돼 대량 매도 우려가 제기됐다 (같은 자료, 로이터는 매도 필요성이 없다고 반박) | 여러 항공사가 기내 와이파이에 스타링크 도입을 검토 중이라는 긍정적 소식이 있다 (같은 자료) | 보통 — 실적 실망·대주주 매도 우려라는 두 독립적 근거 |
| 삼성전자 | 방향성 불분명 | 상승: 반도체(DS) 부문 영업이익률이 72%, 메모리 매출이 전년대비 427% 늘며 펀더멘털 자체는 역대 최대 실적으로 유효하다 (4번 섹션, [kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2147515))<br>하락: 자사주 매입·소각 규모·시점을 밝히지 않아 시장 기대에 못 미쳤고, 최종 환원안은 내년 1월 말 이사회로 넘겨져 불확실성이 11월에도 이어진다 (같은 자료) | SK하이닉스와의 투자심리 격차가 좁혀지는 추가 환원 관련 소식이 나오면 주가가 반응할 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 상승 우세 | 1. 20조원 자사주 매입(10조원 소각) 등 구체적인 환원 계획을 이미 발표해 삼성전자와 투자심리가 대조되고 있다 (3번 섹션)<br>2. 3분기 영업이익이 컨센서스를 웃도는 역대 최대를 기록하며 펀더멘털이 뒷받침되고 있다 (같은 자료) | 10월 한 달 −20.16%로 가장 크게 내린 데다, 10-30 반도체 업종 전반 매도에 −7.08% 급락한 점은 추가 되돌림 가능성을 보여준다 (본문 3번 섹션) | 보통 — 구체적 환원 계획·실적 서프라이즈라는 두 독립적 근거 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
