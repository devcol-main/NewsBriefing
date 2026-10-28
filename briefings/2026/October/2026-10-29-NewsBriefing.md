# 📈 2026-10-29 (목) 아침 브리핑

> 생성 07:50 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한눈에 (3줄)
- 코스피는 SK하이닉스가 3분기 영업이익이 시장 예상(77조원)을 웃도는 역대급 실적을 내고 자사주 매입·소각과 배당 확대 등으로 100조원 규모 주주환원 계획까지 내놓자 반도체 대형주로 매수세가 몰리며 +6.63%(6,012.44)로 10거래일 만에 6000선을 회복했고, 코스닥도 +3.69%(771.28) 올랐어요.
- 관심 종목 중에서는 SK하이닉스(+10.89%)·삼성전자(+9.01%)가 반도체 랠리를 주도했고 AMD(+3.24%)도 올랐는데, 美 증시에서는 마이크로소프트가 FY2027 1분기 매출·Azure 성장률(+48%)이 컨센서스를 상회했다고 밝히며 시간외 급등한 반면 알파벳은 3분기 주당순이익이 컨센서스를 크게 밑돌고 잉여현금흐름이 적자로 전환되며 시간외 급락했어요.
- 오늘(KST)은 삼성전자의 3분기 확정 실적 발표가 예정돼 있고, 밤에는 美 3분기 GDP 속보치·9월 PCE 물가지수·신규 실업수당 청구건수가 함께 발표될 예정이에요.

## 2. 지수
| 지수 | 종가 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| KOSPI | 6,012.44 | +6.63% | 10-28 종가 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 771.28 | +3.69% | 10-28 종가 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 7,743.98 | +0.28% | 10-28 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 26,549.85 | +0.27% | 10-28 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |

<sub>국내·미국 모두 전 거래일은 10-27(화). 10-27·28 모두 휴장 없음([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/)). 등락률은 10-27 종가와 `python3 -c`로 직접 계산(예: (6012.44−5638.34)/5638.34=+6.63%). 코스피 등락(+6.63%, 6,012.44, +374.10포인트)은 [kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2144989)(10-28 22:21)·[머니투데이](https://www.mt.co.kr/stock/2026/10/28/2026102815421930994)(10-28 15:53) 기사 수치와 일치.</sub>

## 2-1. 현금·환율
| 항목 | 값 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| 달러 인덱스 (DXY) | 102.15 | −0.17% | 10-28 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) |
| USD/JPY | 157.96 | +0.09% | 10-28 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-10-28?from=USD&to=JPY,KRW) |
| USD/KRW | 1,340.47 | +0.96% | 10-28 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-10-28?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 848.60 | +0.87% | 10-28 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-10-28?from=JPY&to=KRW) |

<sub>등락은 직전 고시일 10-27 대비([USD](https://api.frankfurter.dev/v1/2026-10-27?from=USD&to=JPY,KRW), [JPY→KRW](https://api.frankfurter.dev/v1/2026-10-27?from=JPY&to=KRW)). DXY는 Yahoo Finance 히스토리 표의 10-28 확정 종가 기준이며, 전일(10-27) 종가는 102.32로 확인됨(직전 브리핑에 적힌 102.36과는 소폭 차이가 있음 — 참고용 기록).</sub>

## 3. 관심 종목
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 엔비디아 · 2. 애플 · 3. 알파벳 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))

| 종목 | 종가 | 등락 | 기준 | 한 줄 메모 | 출처 |
|---|---|---|---|---|---|
| 엔비디아 (NVDA) | $215.38 | −1.17% | 10-28 종가 | 美 법무부(DOJ)가 129억달러 규모 Hugging Face 인수 건을 반독점 심사 중이라는 보도가 나오며 내렸음. AI 칩주 전반은 신규 AI 거래 소식에 강세를 보였음 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 CNBC·TheFly 기사, 10-28 |
| 애플 (AAPL) | $343.83 | −0.94% | 10-28 종가 | 터치스크린 탑재 신형 맥북프로(M5 칩)를 공개했지만 'iPhone Duo' 화면 파손 불만이 이어지고 11-02 예정된 4분기 실적을 앞두고 위험 평가가 나오며 내렸음 | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/) 관련 Reuters·TechCrunch·TipRanks 기사, 10-28 |
| 알파벳 (GOOGL) | $324.89 | +1.34% | 10-28 종가 | 정규장 마감 후 발표한 3분기 실적에서 주당순이익(2.12달러)이 컨센서스(3.01달러)를 크게 밑돌고 잉여현금흐름이 −90.65억달러로 적자 전환했다고 밝히며 시간외 급락했음(구글클라우드 매출은 전년대비 103% 성장) | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 CNBC·WSJ·Reuters 기사, 10-28 |
| AMD | $578.44 | +3.24% | 10-28 종가 | 서스케한나가 긍정적인 평가를 상향했고, 신규 AI 거래 소식에 AI 칩주 전반이 올랐음 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 TheFly·TipRanks 기사, 10-28 |
| 마이크로소프트 (MSFT) | $531.01 | −0.06% | 10-28 종가 | 정규장은 소폭 내렸지만 장 마감 후 발표한 FY2027 1분기 실적에서 매출(922억8,000만달러, +19%)·Azure 매출(332억달러, +48%)이 모두 컨센서스를 상회해 시간외 급등했음 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/) 관련 Bloomberg·WSJ 기사, 10-28 |
| 테슬라 (TSLA) | $404.22 | −0.80% | 10-28 종가 | 재설계된 로드스터의 스러스터 시연 결과가 다소 실망스럽다는 평가가 나왔고, 국내에서는 FSD 불법 활성화로 운전자 80명이 검찰에 송치됐다는 보도도 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 TipRanks 기사, 10-28 |
| 스페이스X (SPCX) | $145.23 | −2.25% | 10-28 종가 | 한 주요 투자자가 "한계점(breaking point)에 다다랐다"며 밸류에이션 우려를 제기했다고 보도됐음 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) 관련 TipRanks 기사, 10-28 |
| 삼성전자 | 242,000원 | +9.01% | 10-28 종가 | SK하이닉스의 역대급 실적·주주환원 발표에 따른 반도체 대형주 재평가 기대 속 외국인·기관 매수세가 몰리며 급등했음(3분기 확정 실적은 10-29 발표 예정) | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data), [kr.investing.com 기사](https://kr.investing.com/news/stock-market-news/article-2144989) |
| SK하이닉스 | 1,487,000원 | +10.89% | 10-28 종가 | 3분기 영업이익이 시장 컨센서스(77조원)를 웃도는 83조3,338억원(kr.investing.com 기준, 분기 역대 최대)을 기록했고, 20조원 자사주 매입(10조원 소각)·배당 확대 등 60조원 추가 환원(8월 40조원 포함 총 100조원 규모)을 발표했음 | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data), [kr.investing.com 기사](https://kr.investing.com/news/stock-market-news/article-2144989) |

## 4. 주요 뉴스 (최대 5건)
1. **코스피·코스닥, SK하이닉스 역대급 실적·주주환원에 반도체 랠리로 6.63%·3.69% 급등 — 코스피 10거래일 만에 6000선 회복** — 코스피는 전 거래일보다 374.10포인트(6.63%) 오른 6,012.44에, 코스닥은 27.45포인트(3.69%) 오른 771.28에 마감했다. SK하이닉스가 3분기 영업이익이 시장 예상(77조원)을 웃도는 역대급 실적을 내고 100조원 규모 주주환원 계획을 내놓자 반도체 대형주로 매수세가 몰렸고, 美 필라델피아 반도체지수가 전날 3.60% 오른 점도 투자심리를 지지했다. 코스피에서는 기관(9,608억원)·외국인(8,229억원)이 동반 순매수했고 개인은 1조8,016억원 순매도했다. ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2144989), 10-28 22:21; [머니투데이](https://www.mt.co.kr/stock/2026/10/28/2026102815421930994), 10-28 15:53)
2. **SK하이닉스, 3분기 역대 최대 실적에 "100조원" 주주환원 발표** — SK하이닉스는 3분기 영업이익이 시장 컨센서스(77조원)를 웃돌며 분기 기준 역대 최대를 기록했다고 밝혔다(kr.investing.com 기준 83조3,338억원). 20조원 규모 자사주 매입(이 중 10조원 소각)과 3분기 배당(주당 2만원, 총 14조원) 등 60조원 추가 환원 계획을 내놓았고, 8월 발표한 40조원을 더하면 올해 주주환원 총액은 약 100조원에 이른다. 황민성 디렉터는 D램 시장이 2,000억달러를 처음 돌파한 점에 주목했다. ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2144989), 10-28 22:21; [news1.kr](https://www.news1.kr/industry/general-industry/6335446), 10-28 18:40)
3. **FOMC, 기준금리 3.75~4.00% 동결 — 10대2, 2명은 인상 주장** — 연준은 FOMC 정례회의에서 기준금리를 3.75~4.00%로 유지하기로 결정했다. 위원회는 경제 성장세가 강하고 생산성·설비투자도 활발하다고 평가했지만 인플레이션은 여전히 높다고 진단했다. 리사 쿡·베스 해맥 위원은 0.25%포인트 인상을 주장하며 반대표를 던졌다. ([Federal Reserve](https://www.federalreserve.gov/newsevents/pressreleases/monetary20261028a.htm), 10-28)
4. **알파벳, 3분기 EPS 컨센서스 크게 하회·FCF 적자전환에 시간외 급락** — 알파벳은 3분기 매출이 1,276억달러(전년대비 25% 증가)로 컨센서스(1,279억1,000만달러)에 소폭 못 미쳤고, 주당순이익은 2.12달러로 컨센서스(3.01달러)를 크게 밑돌았다. AI 인프라 투자 확대로 잉여현금흐름은 −90.65억달러로 적자 전환했다. 다만 구글클라우드 매출은 307억1,000만달러로 전년대비 103% 성장했다. ([stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 CNBC·WSJ·Reuters 기사, 10-28)
5. **마이크로소프트, FY2027 1분기 매출·Azure 성장률 컨센서스 상회에 시간외 급등** — 마이크로소프트는 FY2027 1분기 매출이 922억8,000만달러(전년대비 약 19% 증가, 사상 최대)로 컨센서스(907억4,000만달러)를 넘어섰고 조정 EPS도 4.89달러로 컨센서스(4.72달러)를 상회했다. Azure 매출은 332억달러로 전년대비 48% 성장했다고 처음으로 달러 금액을 공개했다. ([stockanalysis.com](https://stockanalysis.com/stocks/msft/) 관련 Bloomberg·WSJ 기사, 10-28)

## 5. 오늘 일정
- 美 3분기 GDP 속보치, 9월 개인소득·지출(PCE 물가지수 포함), 신규 실업수당 청구건수(10/24 마감주, 컨센서스 19.9만건·직전치 19.4만건) 발표 (21:30 KST) ([BEA](https://www.bea.gov/news/schedule), [Trading Economics](https://tradingeconomics.com/united-states/jobless-claims))
- 삼성전자, 3분기 확정 실적 발표·컨퍼런스콜 예정 (시각 확인 필요; 3분기 잠정실적은 매출 195조원·영업이익 107.4조원으로 10-08 기발표) ([news1.kr](https://www.news1.kr/industry/general-industry/6335470))
- (참고) 美 FOMC는 10-29 새벽 03:00 KST 기준금리를 3.75~4.00%로 동결 발표함 — 본문 4번 섹션 참고 ([Federal Reserve](https://www.federalreserve.gov/newsevents/pressreleases/monetary20261028a.htm))
- 국내·미국 증시 휴장 없음 ([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/))

## 6. 전망 (자체 판단)
**직전 전망 점검:** 직전 일일 브리핑(2026-10-28)의 전망 13건을 10-27→10-28 종가로 확인한 결과 적중 7건(코스피 +6.63%·코스닥 +3.69%·S&P500 +0.28%·나스닥 +0.27%·AMD +3.24%·삼성전자 +9.01%·SK하이닉스 +10.89%는 모두 "상승 우세"와 일치), 빗나감 5건(엔비디아 −1.17%·애플 −0.94%·알파벳 +1.34%는 모두 "방향성 불분명" 예측의 ±0.5% 밴드를 벗어났고, 테슬라 −0.80%·스페이스X −2.25%는 "상승 우세" 예측과 반대), 판단 보류 1건(마이크로소프트, 집계에서 제외). SK하이닉스의 3분기 실적이 시장 컨센서스(77조원)를 웃돌고 100조원 규모 주주환원 계획까지 발표되며 지수·반도체 대형주의 상승이 예상보다도 더 크게 나타났다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 10-29~10-30 | 상승: 기관(9,608억원)·외국인(8,229억원)이 코스피에서 동반 순매수하며 반도체 대형주 재평가 기대가 이어지고 있다 (본문 4번 섹션, [kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2144989))<br>하락: 하루 만에 +6.63% 급등한 데 따른 차익실현 매물이 나올 수 있고(10-21 급등 후 10-22 차익매물로 급락했던 전례, [2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고), 알파벳의 3분기 실적 쇼크로 글로벌 빅테크 투자심리가 위축될 수 있다 (본문 4번 섹션) | FOMC가 인플레이션이 여전히 높다고 진단했고 2명 위원이 추가 인상을 주장해 통화정책 불확실성이 남아있다 ([Federal Reserve](https://www.federalreserve.gov/newsevents/pressreleases/monetary20261028a.htm)) | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 방향성 불분명 | 10-29~10-30 | 상승: 반도체 대형주 랠리 속에 코스닥에서도 기관이 2,239억원 순매수하며 동반 급등(+3.69%)했다 ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2144989), 10-28 22:21)<br>하락: 같은 날 외국인(1,835억원)·개인(307억원)은 코스닥에서 순매도했고, 코스닥은 최근 코스피보다 더 큰 폭의 등락(디커플링)을 반복해 반등 탄력이 꺾일 수 있다 ([2026-10-27 브리핑](2026-10-27-NewsBriefing.md) 참고) | 레인보우로보틱스 등 로봇·AI 관련주로 매수세가 확산되고 있다는 점은 추가 상승 재료가 될 수 있다 ([kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2144989), 10-28 22:21) | 낮음 — 상승·하락 근거가 팽팽함 |
| S&P 500 | 방향성 불분명 | 10-29~10-30 | 상승: 마이크로소프트가 FY2027 1분기 매출·Azure 성장률(+48%)이 컨센서스를 상회했다고 밝히며 시간외 급등했다 (본문 4번 섹션)<br>하락: 알파벳은 3분기 주당순이익이 컨센서스를 크게 밑돌고 잉여현금흐름이 적자로 전환됐다고 밝히며 시간외 급락했다 (본문 4번 섹션) | FOMC가 인플레이션이 여전히 높다고 진단했고 2명 위원이 추가 인상을 주장해 통화정책 불확실성이 남아있다 ([Federal Reserve](https://www.federalreserve.gov/newsevents/pressreleases/monetary20261028a.htm)) | 낮음 — 대형 빅테크의 실적 호재·악재가 팽팽함 |
| NASDAQ | 방향성 불분명 | 10-29~10-30 | 상승: AMD(+3.24%) 등 AI 칩주가 신규 AI 거래 소식에 올랐고 마이크로소프트의 Azure 고성장이 확인됐다 (본문 3·4번 섹션)<br>하락: 엔비디아는 DOJ의 Hugging Face 인수 반독점 심사 소식에 내렸고, 알파벳의 3분기 실적 쇼크가 시간외 반영되고 있다 (본문 3·4번 섹션) | FOMC가 인플레이션이 여전히 높다고 진단했고 2명 위원이 추가 인상을 주장해 통화정책 불확실성이 남아있다 ([Federal Reserve](https://www.federalreserve.gov/newsevents/pressreleases/monetary20261028a.htm)) | 낮음 — 상승·하락 근거가 팽팽함 |
| 엔비디아 (NVDA) | 방향성 불분명 | 10-29~10-30 | 상승: AI 칩주 전반이 신규 AI 거래 소식에 강세를 보였다(AMD +3.24%, 본문 3번 섹션)<br>하락: DOJ가 129억달러 규모 Hugging Face 인수 건을 반독점 심사 중이라는 보도가 나왔다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 CNBC 기사, 10-28) | 11-17로 예정된 3분기 실적 발표 컨퍼런스콜 결과에 따라 변동성이 커질 수 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 GlobeNewswire 보도자료, 10-28) | 낮음 — 상승·하락 근거가 팽팽함 |
| 애플 (AAPL) | 방향성 불분명 | 10-29~10-30 | 상승: 터치스크린 탑재 신형 맥북프로(M5 칩)를 공개하며 제품 모멘텀을 이어갔다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/) 관련 Reuters·TechCrunch 기사, 10-28)<br>하락: 'iPhone Duo' 화면 파손 불만이 지속되고 있고 TipRanks는 4분기 실적 발표를 앞두고 주가가 위험하다고 평가했다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/) 관련 TipRanks 기사, 10-28) | 11-02 예정된 4분기 실적 발표 결과에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 알파벳 (GOOGL) | 하락 우세 | 10-29~10-30 | 1. 3분기 주당순이익(2.12달러)이 컨센서스(3.01달러)를 크게 밑돌았고 잉여현금흐름이 −90.65억달러로 적자 전환했다 (본문 4번 섹션)<br>2. 실적 발표 후 시간외 거래에서 주가가 약 7~10% 급락했다고 보도됐다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 CNBC·WSJ 기사, 10-28) | 구글클라우드 매출이 전년대비 103% 성장했고 제미나이 앱 사용자가 10억명을 돌파해 구조적 성장 스토리는 유지되고 있다 (본문 4번 섹션) | 보통 — 실적 쇼크·시간외 급락이라는 두 독립적 근거, 클라우드 고성장이 반대요인 |
| AMD | 상승 우세 | 10-29~10-30 | 1. 서스케한나가 AMD에 대한 긍정적인 평가를 상향했다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 TheFly 기사, 10-28)<br>2. 신규 AI 거래 소식에 AI 칩주 전반(인텔·엔비디아 포함)이 올랐다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 TipRanks 기사, 10-28) | ARK Invest(캐시 우드)가 AMD 보유 지분을 계속 매도하고 있다는 보도가 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 TipRanks 기사, 10-28) | 보통 — 개별 평가 상향·업종 전반 강세라는 두 독립적 근거 |
| 마이크로소프트 (MSFT) | 상승 우세 | 10-29~10-30 | 1. FY2027 1분기 매출(922억8,000만달러, +19%)·조정 EPS(4.89달러)가 모두 컨센서스를 상회했고 Azure 매출(332억달러, +48%)을 처음 달러 금액으로 공개했다 (본문 4번 섹션)<br>2. 실적 발표 후 시간외 거래에서 주가가 장중 한때 568달러대까지 오르는 등 강세를 보였다고 보도됐다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/) 관련 Invezz·TheFly 기사, 10-28) | 전직원 약 4분의1 대상 희망퇴직 프로그램이 진행 중인 점은 조직 변화 우려로 남아있다 ([2026-10-26 브리핑](2026-10-26-NewsBriefing.md) 참고) | 높음 — 매출·EPS·Azure 성장률이 모두 컨센서스를 상회한 독립적 근거가 다수이고 반대요인은 약함 |
| 테슬라 (TSLA) | 방향성 불분명 | 10-29~10-30 | 상승: Barron's는 테슬라 주가가 사흘째 상승세를 이어가고 있으며 스페이스X 관련 기대 이상의 동력이 있다고 평가했다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 Barron's 기사, 10-28)<br>하락: 재설계된 로드스터의 스러스터 시연 결과가 기대에 못 미쳤다는 평가가 나왔고, 국내에서는 FSD 불법 활성화로 운전자 80명이 검찰에 송치됐다는 보도도 있었다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 TipRanks 기사, 10-28) | 스페이스X와의 합병 논의가 진전되면 밸류에이션 재평가 기대로 주가가 반응할 수 있다 ([2026-10-24 브리핑](2026-10-24-NewsBriefing.md) 참고) | 낮음 — 상승·하락 근거가 팽팽함 |
| 스페이스X (SPCX) | 하락 우세 | 10-29~10-30 | 1. 한 주요 투자자가 "한계점(breaking point)에 다다랐다"며 밸류에이션 우려를 제기했다고 보도됐다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/) 관련 TipRanks 기사, 10-28)<br>2. 최근 Apollo와 체결한 약 400억달러 규모의 리스 금융 계약 등으로 레버리지 부담이 커지고 있다는 평가가 있다 ([2026-10-27 브리핑](2026-10-27-NewsBriefing.md) 참고) | 일론 머스크는 2~3년 내 무선통신사업자(와이어리스 캐리어)를 구축할 수 있다고 밝혀 신사업 기대가 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/) 관련 MarketWatch 기사, 10-28) | 보통 — 밸류에이션 경고·레버리지 부담이라는 두 독립적 근거 |
| 삼성전자 | 방향성 불분명 | 10-29~10-30 | 상승: SK하이닉스의 역대급 실적·100조원 주주환원 발표로 반도체 대형주 재평가 기대가 커졌고 D램 시장이 2,000억달러를 처음 돌파했다는 평가도 나왔다 (본문 4번 섹션, [news1.kr](https://www.news1.kr/industry/general-industry/6335446))<br>하락: 하루 만에 +9.01% 급등한 데 따른 차익실현 매물이 나올 수 있다(10-21 급등 후 10-22 차익매물로 급락했던 전례, [2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고) | 오늘(10-29) 발표되는 3분기 확정 실적 결과에 따라 변동성이 커질 수 있다 | 보통 — 업종 재평가 기대·차익실현 리스크라는 두 독립적 근거 |
| SK하이닉스 | 상승 우세 | 10-29~10-30 | 1. 3분기 영업이익이 시장 컨센서스(77조원)를 웃돌며 분기 역대 최대를 기록했다 (본문 4번 섹션, [news1.kr](https://www.news1.kr/industry/general-industry/6335446))<br>2. 20조원 자사주 매입(10조원 소각)·배당 확대 등 60조원 추가 환원을 포함해 올해 총 100조원 규모 주주환원 계획을 내놓았다 (본문 4번 섹션, [kr.investing.com](https://kr.investing.com/news/stock-market-news/article-2144989)) | 하루 만에 +10.89% 급등한 데 따른 차익실현 매물이 나올 수 있다 ([2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고) | 보통 — 실적 서프라이즈·대규모 주주환원이라는 두 독립적 근거 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
