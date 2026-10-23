# 📊 2026-10-24 (토) 주간 요약 — 10-19~10-23

> 생성 07:48 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한 줄 총평
이번 주 코스피·코스닥은 한국은행 통화정책과 반도체 수급을 둘러싸고 하루 2~4%대 등락을 반복하며(10-19 +1.76%→10-20 −3.73%→10-21 +3.29%→10-22 −3.52%→10-23 +0.30%) 주간 각각 −2.08%(5,668.05→5,550.30)·−5.42%(794.78→751.69)로 밀렸고, 美 증시는 AI 인프라 자금조달 우려 속에서도 상대적으로 완만하게 S&P500 −0.47%·나스닥 −0.71%로 내렸으며, 관심 종목 중에서는 테슬라(+4.93%)가 3분기 실적 호조에 가장 많이 올랐고 알파벳(−5.98%)은 규제·소송 리스크에 가장 많이 내렸어요.

## 2. 지수·환율 주간 등락
| 항목 | 이번 주 종가 | 전주 종가 | 주간 등락 | 기준 | 출처 |
|---|---|---|---|---|---|
| KOSPI | 5,550.30 | 5,668.05 | −2.08% | 10-23 vs 10-16 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 751.69 | 794.78 | −5.42% | 10-23 vs 10-16 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 7,623.68 | 7,659.44 | −0.47% | 10-23 vs 10-16 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 25,955.34 | 26,140.03 | −0.71% | 10-23 vs 10-16 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |
| 달러 인덱스 (DXY) | 101.75 | 101.84 | −0.09% | 10-23 vs 10-16 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) |
| USD/JPY | 156.80 | 158.02 | −0.77% | 10-23 vs 10-16 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-10-23?from=USD&to=JPY,KRW), [10-16](https://api.frankfurter.dev/v1/2026-10-16?from=USD&to=JPY,KRW) |
| USD/KRW | 1,324.45 | 1,332.10 | −0.57% | 10-23 vs 10-16 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-10-23?from=USD&to=JPY,KRW), [10-16](https://api.frankfurter.dev/v1/2026-10-16?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 844.66 | 842.99 | +0.20% | 10-23 vs 10-16 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-10-23?from=JPY&to=KRW), [10-16](https://api.frankfurter.dev/v1/2026-10-16?from=JPY&to=KRW) |

<sub>국내·美 증시 모두 이번 주(10-19~10-23)·전주(10-12~10-16) 휴장 없이 각 5거래일 정상 개장([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/)). 등락률은 모두 두 종가를 `python3 -c`로 직접 계산(검색 요약·기사 문구는 쓰지 않음). KOSPI·KOSDAQ 10-23 값(5550.30·751.69)은 [뉴스1](https://www.news1.kr/finance/general-stock/6330135)(10-23 15:49)·[머니투데이](https://www.mt.co.kr/stock/2026/10/23/2026102315265178425)(10-23 15:33) 기사 수치와, 10-16 값(5668.05·794.78)은 [머니투데이](https://www.mt.co.kr/stock/2026/10/16/2026101615331353587)(10-16 15:33)·[뉴스1](https://www.news1.kr/finance/general-stock/6322658)(10-16 15:36) 기사 수치와 각각 일치.</sub>

## 3. 관심 종목 주간 성적표 (주간 등락률 순)
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 엔비디아 · 2. 애플 · 3. 알파벳 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))

| 순위 | 종목 | 이번 주 종가 | 주간 등락 | 기준 | 출처 |
|---|---|---|---|---|---|
| 1 | 테슬라 (TSLA) | $372.22 | +4.93% | 10-23 vs 10-16 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) |
| 2 | 애플 (AAPL) | $347.73 | +1.24% | 10-23 vs 10-16 | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/) |
| 3 | 스페이스X (SPCX) | $147.49 | +1.00% | 10-23 vs 10-16 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) |
| 4 | SK하이닉스 | 1,277,000원 | +0.39% | 10-23 vs 10-16 | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data) |
| 5 | 삼성전자 | 215,500원 | +0.00% | 10-23 vs 10-16 | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data) |
| 6 | 마이크로소프트 (MSFT) | $524.51 | −0.86% | 10-23 vs 10-16 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/) |
| 7 | 엔비디아 (NVDA) | $210.96 | −1.48% | 10-23 vs 10-16 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) |
| 8 | AMD | $516.79 | −2.26% | 10-23 vs 10-16 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/) |
| 9 | 알파벳 (GOOGL) | $320.21 | −5.98% | 10-23 vs 10-16 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) |

- 📈 가장 많이 오른 종목 **테슬라 (TSLA, +4.93%)**: 10-21 발표한 3분기 실적에서 주당순이익이 예상을 웃돌았고 FSD 유료 구독자가 전년 대비 67% 늘었으며, 실적 발표 콜에서 머스크가 스페이스X와의 합병을 "좋은 생각"이라고 언급하며 주가가 올랐어요. ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 CNBC·TipRanks 기사, 10-22~10-23)
- 📉 가장 많이 내린 종목 **알파벳 (−5.98%)**: 상원의원들이 AI 교육 도입을 둘러싸고 CEO에 서한을 보내 조사에 착수했고, 유럽 금융당국은 은행권에 영향을 준 클라우드 장애에 대한 해명을 요구했으며, 5~7월 공시 관련 증권 소송 제기 소식도 겹치며 관심 종목 중 가장 큰 폭으로 밀렸어요. ([stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 Reuters·New York Post 기사, 10-21~10-23)

## 4. 이번 주 주요 뉴스 (최대 5건)
1. **코스피·코스닥, 통화정책·반도체 수급 둘러싸고 하루 2~4%대 등락 반복** — 코스피는 10-19 +1.76%(5,768.01)→10-20 −3.73%(5,552.74, 외국인·기관 순매도)→10-21 +3.29%(5,735.66, 외국인 순매수 전환·삼성전자 +5.67%·SK하이닉스 +5.81%에 매수 사이드카 발동)→10-22 −3.52%(5,533.77)→10-23 +0.30%(5,550.30)로 출렁였고, 주간으로는 −2.08% 하락했다. ([뉴스1](https://www.news1.kr/finance/market-exr/6324736), 10-19 15:34 · [서울신문](https://www.seoul.co.kr/news/economy/securities/2026/10/20/20261020500235), 10-20 16:04 · [서울신문](https://www.seoul.co.kr/news/economy/securities/2026/10/21/20261021500220), 10-21 15:44 · [뉴스1](https://www.news1.kr/finance/general-stock/6330135), 10-23 15:49)
2. **한국은행, 기준금리 연 3.00% 만장일치 동결 — 신현송 총재 "긴축 기조 유지"** — 금융통화위원 7명 전원이 동결에 찬성했다. 7·8월 두 차례 연속 인상 이후 효과를 점검하기 위한 "숨고르기"로 풀이됐고, 신 총재는 성장·물가 흐름이 8월 전망보다 강한 만큼 통화긴축 기조는 이어가겠다고 밝혀 11월 추가 인상 가능성이 거론된다. ([머니투데이](https://www.mt.co.kr/economy/2026/10/22/2026102209323421102), 10-22 09:32)
3. **美 AI 인프라 자금조달 지속가능성 우려 재부각, 반도체·빅테크 동반 약세** — 테슬라가 2026년 지출 계획을 약 200억달러 수준으로 낮췄고 Lam Research가 예상보다 약한 전망을 내놓으며 반도체주가 밀렸다. 메타는 3분기 잉여현금흐름이 적자로 돌아섰다고 보도돼 빅테크의 AI 투자 수익성 논란이 다시 커졌다. ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 MarketWatch·Bloomberg 기사, 10-22~10-23)
4. **테슬라 3분기 실적 발표(10-21), 합병 논의 속 머스크는 이해상충으로 특별위원회에 빠져** — 주당순이익이 예상을 웃돌았고 FSD 유료 구독자는 67% 늘었지만 차량 인도량은 전년 대비 줄었다(다만 월가 전망치는 상회). 테슬라·스페이스X는 합병 검토를 위한 특별위원회를 각각 구성했고, 머스크는 이해상충을 이유로 협상에서 빠졌다. ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 CNBC·TechXplore 기사, 10-22~10-23)
5. **알파벳, 규제·소송 리스크 집중 — 상원 AI 교육 조사·EU 클라우드 장애 해명 요구** — 상원의원 리처드 블루먼솔·조시 홀리가 구글의 학교 내 AI 도입을 문제삼아 CEO에게 서한을 보내고 조사에 착수했다. 유럽 금융당국은 은행권에 영향을 준 구글 클라우드 장애에 대한 해명을 요구했고, 5~7월 공시와 관련한 증권 소송 제기 소식도 이어졌다. ([stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 Reuters·New York Post 기사, 10-21~10-23)

## 5. 다음 주 전망 (자체 판단)
**직전 전망 점검:** 직전 주간 요약(2026-10-10)의 전망 13건을 10-09→10-16 종가로 확인한 결과 적중 5건(KOSPI −14.46%는 "하락 우세"와 일치, AMD −13.05%도 "하락 우세"와 일치, AAPL +2.03%는 "상승 우세"와 일치, 삼성전자 −17.75%·SK하이닉스 −24.33%는 모두 "하락 우세"와 일치), 빗나감 7건(S&P500 −1.95%·NASDAQ −4.48%·NVDA −6.61%는 모두 "방향성 불분명" 예측의 ±1% 밴드를 벗어났고, GOOGL −3.15%·MSFT −1.13%·TSLA −7.31%·SPCX −10.17%는 모두 "상승 우세" 예측과 반대), 판단 보류 1건(KOSDAQ, 집계 제외). 10월 15일 "검은 목요일" 급락이 예상보다 훨씬 커 지수·반도체·개별 성장주 대부분에서 하락 방향이 예측보다 과소평가됐다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 10-26~10-30 | 상승: 10-21 외국인이 코스피에서 약 6,600억원을 순매수로 전환하며 9거래일 만에 매수 우위로 돌아섰고 삼성전자(+5.67%)·SK하이닉스(+5.81%)가 급등을 주도했다 (4번 섹션, [서울신문](https://www.seoul.co.kr/news/economy/securities/2026/10/21/20261021500220))<br>하락: 한국은행이 기준금리를 동결했지만 신현송 총재가 통화긴축 기조를 유지하겠다고 밝혀 11월 추가 인상 가능성이 거론된다 (4번 섹션, [머니투데이](https://www.mt.co.kr/economy/2026/10/22/2026102209323421102)) | 10-20·10-22 두 차례 외국인·기관의 대규모 순매도가 재발하며 수급이 다시 악화될 수 있다 (4번 섹션, [서울신문](https://www.seoul.co.kr/news/economy/securities/2026/10/20/20261020500235)) | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 하락 우세 | 10-26~10-30 | 1. 10-22 외국인(1,200억원)·기관(1,002억원)이 코스닥에서 동반 순매도했다 ([2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고, [서울신문](https://www.seoul.co.kr/news/economy/securities/2026/10/22/20261022500245))<br>2. 에코프로비엠·주성엔지니어링·원익IPS 등 반도체 소부장·2차전지 대형주가 10-22 동반 급락했다 (같은 기사) | 개인이 10-22 2,209억원을 순매수하며 저가 매수세를 이어가고 있다 (같은 기사) | 보통 — 외국인·기관 동반 매도, 업종 전반 약세라는 두 독립적 근거 |
| S&P 500 | 방향성 불분명 | 10-26~10-30 | 상승: 애플 'iPhone Duo' 온라인 주문이 빠르게 매진되고 매장 재고가 제한되는 등 강한 신제품 수요가 확인됐다 ([2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고)<br>하락: 테슬라가 2026년 지출 계획을 축소했고 메타의 3분기 잉여현금흐름이 적자로 전환되며 AI 투자 수익성 우려가 재부각됐다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 Bloomberg 기사) | Lam Research의 부진한 전망이 반도체 업종 전반에 추가 부담을 줄 수 있다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 MarketWatch 기사) | 낮음 — 상승·하락 근거가 팽팽함 |
| NASDAQ | 하락 우세 | 10-26~10-30 | 1. 테슬라의 지출 계획 축소와 메타의 3분기 잉여현금흐름 적자 전환으로 빅테크 AI 투자 수익성 우려가 커졌다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 Bloomberg 기사)<br>2. Lam Research의 부진한 전망 속 AMD(−2.26%)·엔비디아(−1.48%) 등 반도체 대형주가 이번 주 약세를 보였다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/amd/)) | 애플이 iPhone Duo 흥행에 힘입어 이번 주 +1.24% 올라 대형 기술주의 버팀목 역할을 했다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/aapl/)) | 보통 — AI 지출 우려·반도체 약세라는 두 독립적 근거 |
| 엔비디아 (NVDA) | 하락 우세 | 10-26~10-30 | 1. AI 인프라 자금조달 지속가능성에 대한 우려가 테슬라 지출 축소·메타 FCF 적자 전환으로 다시 커졌다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 Bloomberg 기사)<br>2. Lam Research가 예상보다 약한 전망을 내놓으며 반도체 장비·칩 업종 전반에 부담을 줬다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 MarketWatch 기사) | 젠슨 황 CEO는 네오클라우드 수요가 매우 강하고 2029년까지 메모리 공급과잉 징후는 보이지 않는다고 밝혔다 ([2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고) | 보통 — AI 지출 우려·동종 업계 약세라는 두 독립적 근거 |
| 애플 (AAPL) | 상승 우세 | 10-26~10-30 | 1. 폴더블 아이폰 'iPhone Duo' 온라인 주문이 빠르게 매진되고 매장 재고가 제한되는 등 강한 수요가 확인됐다 ([2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고)<br>2. 반도체·AI 지출 우려로 동종 대형 기술주가 약세였던 이번 주에도 유일하게 +1.24% 올랐다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/aapl/)) | 모건스탠리는 애플의 단기 전망을 다소 어려운 국면으로 평가해 신제품 효과가 제한적일 수 있다 ([2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고) | 보통 — 신제품 수요·개별 강세라는 두 독립적 근거 |
| 알파벳 (GOOGL) | 하락 우세 | 10-26~10-30 | 1. 상원의원들이 구글의 AI 교육 도입을 문제삼아 CEO에 서한을 보내고 조사에 착수했다 (3·4번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 Reuters 기사)<br>2. 유럽 금융당국이 은행권에 영향을 준 구글 클라우드 장애에 대한 해명을 요구했고, 5~7월 공시 관련 증권 소송 제기 소식도 겹쳤다 (같은 기사) | OpenAI의 프런티어 모델과 코덱스 코딩 에이전트가 구글 클라우드에서 제공될 예정이라는 사업 제휴 소식이 있었다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/googl/) 관련 Reuters·CNBC 기사) | 보통 — 규제 조사·소송이라는 두 독립적 근거 |
| AMD | 하락 우세 | 10-26~10-30 | 1. AI 인프라 자금조달 우려 속 테슬라 지출 축소·메타 FCF 적자 전환 소식이 반도체주 전반에 부담을 줬다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 Bloomberg 기사)<br>2. Lam Research의 부진한 전망이 반도체 장비·칩 업종 투자심리를 눌렀다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 MarketWatch 기사) | 젠슨 황 CEO가 네오클라우드 수요가 매우 강하다고 언급해 반도체 수요 자체는 견조하다는 평가가 있다 ([2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고) | 낮음 — 두 근거가 모두 같은 AI 지출 우려 축에서 나와 독립적이지 않음 |
| 마이크로소프트 (MSFT) | 판단 보류 | 10-26~10-30 | 빌 게이츠의 AI 격변 발언과 Xbox 클라우드 게임 스트리밍 유료화에 대한 반발이 10-22 하락과 함께 보도됐으나 ([2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고), 이들이 매출·이익과 직접 연결되는 근거인지는 확인하지 못했다. 이번 주 전반의 AI 지출 우려 확산 외에 MSFT 고유의 방향 근거는 추가로 찾지 못했다 | Xbox·PlayStation 콘솔 가격 인상 가능성이 보도되며 관련 매출 기대가 주가를 지지할 수 있다 ([2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고) | 해당없음 — 판단 보류 |
| 테슬라 (TSLA) | 상승 우세 | 10-26~10-30 | 1. 10-21 발표한 3분기 실적에서 주당순이익이 예상을 웃돌았고 FSD 유료 구독자가 전년 대비 67% 늘었다 (3·4번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 TipRanks 기사)<br>2. 실적 발표 콜에서 머스크가 스페이스X와의 합병을 "좋은 생각"이라고 언급했고, 양사가 합병 검토를 위한 특별위원회를 구성했다 (같은 기사, CNBC·TechXplore) | 테슬라가 2026년 지출 계획을 약 200억달러 수준으로 낮춰 AI·로봇공학 목표에 대한 의구심이 제기될 수 있다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 Bloomberg 기사) | 보통 — 실적·FSD 성장과 합병 기대라는 두 독립적 근거 |
| 스페이스X (SPCX) | 방향성 불분명 | 10-26~10-30 | 상승: 테슬라와 합병 검토를 위한 특별위원회를 구성했다는 보도로 밸류에이션 재평가 기대가 있다 (3·4번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) 관련 TechXplore 기사)<br>하락: Fort Bend County의 "Project Crystal Sun" 세제 혜택 승인 소식 이후에도 주가가 밀렸다고 보도됐다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) 관련 TipRanks 기사) | 우크라이나 군사용 Starlink(Starshield) 사용 제한을 둘러싼 정치적 리스크가 남아있다 ([2026-10-23 브리핑](2026-10-23-NewsBriefing.md) 참고) | 낮음 — 상승·하락 근거가 팽팽함 |
| 삼성전자 | 방향성 불분명 | 10-26~10-30 | 상승: 10-21 외국인이 코스피에서 순매수로 전환했고 삼성전자가 +5.67% 급등을 주도했다 (4번 섹션, [서울신문](https://www.seoul.co.kr/news/economy/securities/2026/10/21/20261021500220))<br>하락: 한국은행이 통화긴축 기조를 유지하겠다고 밝혀 11월 추가 인상 가능성이 거론되며 대형주 밸류에이션 부담이 커질 수 있다 (4번 섹션, [머니투데이](https://www.mt.co.kr/economy/2026/10/22/2026102209323421102)) | 美 반도체 대형주(엔비디아·AMD)가 AI 인프라 자금조달 우려로 동반 약세를 보여 업종 전반에 부담을 줄 수 있다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/nvda/)) | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 방향성 불분명 | 10-26~10-30 | 상승: 10-21 외국인 순매수 전환 속 SK하이닉스가 +5.81% 급등을 주도했다 (4번 섹션, [서울신문](https://www.seoul.co.kr/news/economy/securities/2026/10/21/20261021500220))<br>하락: 美 반도체 대형주가 Lam Research의 부진한 전망·AI 지출 우려로 이번 주 동반 약세를 보였다 (3번 섹션, [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 MarketWatch 기사) | 한국은행이 통화긴축 기조를 유지하겠다고 밝혀 대형주 밸류에이션 부담이 추가로 커질 수 있다 (4번 섹션, [머니투데이](https://www.mt.co.kr/economy/2026/10/22/2026102209323421102)) | 낮음 — 상승·하락 근거가 팽팽함 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>주간 등락은 시장별 이번 주·전주 마지막 거래일 종가 기준입니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
