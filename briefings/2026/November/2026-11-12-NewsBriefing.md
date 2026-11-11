# 📈 2026-11-12 (목) 아침 브리핑

> 생성 07:53 KST · 정보 요약용이며 투자 권유가 아닙니다.

## 1. 한눈에 (3줄)
- 美 증시는 11-11(현지) 코어위브의 깜짝 실적(매출 전망 상향·고객 선수금 확보)에 반도체·데이터센터주가 급등해 나스닥 +1.60%·S&P500 +1.31%·다우 +0.48%로 마감했고, 마이크론(+11.89%)·AMD(+7.32%)·인텔(+7.52%)이 특히 강세였어요. 다만 엔비디아는 정규장 +2.87%로 마감한 뒤 CEO 젠슨 황의 두 번째 혼외관계 의혹(NYT)과 이사회의 해임 추진설(WSJ)이 겹치며 시간외 거래에서 −8%대로 급락했어요.
- 국내 증시는 AI 호재(코어위브 실적·앤트로픽 IPO 로드쇼 흥행)와 반도체 수출 급증(11월 1~10일 전년대비 +331%)에 코스피 +2.60%·코스닥 +5.62%로 이틀 연속 급등했고, 관심 종목 중에서는 AMD(+7.30%)가 가장 많이 올랐고 스페이스X(−2.38%)가 가장 많이 내렸어요.
- 오늘(KST)은 국내 11월물 옵션만기일로 수급 변동성이 주목되고, 엔비디아는 이사회가 젠슨 황 CEO의 거취를 결정할 것으로 보도돼 추가 변동성이 예상돼요. 다음 美 지표는 10월 PPI(11-13 발표 예정)예요.

## 2. 지수
| 지수 | 종가 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| KOSPI | 5,375.36 | +2.60% | 11-11 종가 | [kr.investing.com](https://kr.investing.com/indices/kospi-historical-data) |
| KOSDAQ | 705.10 | +5.62% | 11-11 종가 | [kr.investing.com](https://kr.investing.com/indices/kosdaq-historical-data) |
| S&P 500 | 7,619.38 | +1.31% | 11-11 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EGSPC/history/) |
| NASDAQ | 25,466.19 | +1.60% | 11-11 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/%5EIXIC/history/) |

<sub>국내·미국 모두 전 거래일은 11-11(수). 11-11·11-12 국내·미국 증시 휴장 없음([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/)). 등락률은 11-10 종가(KOSPI 5,239.13·KOSDAQ 667.61·S&P500 7,520.93·NASDAQ 25,065.88, [2026-11-11 브리핑](2026-11-11-NewsBriefing.md) 참고)와 위 11-11 종가를 `python3 -c`로 직접 계산. KOSPI·KOSDAQ 등락률(+2.60%·+5.62%)은 [머니투데이](https://www.mt.co.kr/stock/2026/11/11/2026111115584690277) 기사 수치와 일치하고, S&P500·나스닥 등락률(+1.31%·+1.60%)은 [investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-048-5019892) 기사 수치와 일치.</sub>

## 2-1. 현금·환율
| 항목 | 값 | 등락 | 기준 | 출처 |
|---|---|---|---|---|
| 달러 인덱스 (DXY) | 102.91 | +0.67% | 11-11 종가 (ET) | [Yahoo Finance](https://finance.yahoo.com/quote/DX-Y.NYB/history/) |
| USD/JPY | 159.23 | +0.66% | 11-11 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-11?from=USD&to=JPY,KRW) |
| USD/KRW | 1,336.90 | −0.16% | 11-11 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-11?from=USD&to=JPY,KRW) |
| JPY/KRW (100엔) | 839.58 | −0.82% | 11-11 ECB 기준환율 | [Frankfurter/ECB](https://api.frankfurter.dev/v1/2026-11-11?from=JPY&to=KRW) |

<sub>등락은 11-10 ECB 기준환율([Frankfurter 11-10](https://api.frankfurter.dev/v1/2026-11-10?from=USD&to=JPY,KRW), [JPY 기준](https://api.frankfurter.dev/v1/2026-11-10?from=JPY&to=KRW))과 비교해 `python3 -c`로 계산. DXY는 Yahoo Finance 히스토리 표 11-10 종가(102.23)와 11-11 종가(102.91)를 비교. 국내 증시 급등에도 원화는 소폭 강세(USD/KRW −0.16%)에 그쳤음.</sub>

## 3. 관심 종목
**나스닥 시총 Top 3** (조회 시각 기준, 기준일 표기 없음): 1. 애플 · 2. 엔비디아 · 3. 마이크로소프트 ([stockanalysis.com](https://stockanalysis.com/list/nasdaq-stocks/))

| 종목 | 종가 | 등락 | 기준 | 한 줄 메모 | 출처 |
|---|---|---|---|---|---|
| 애플 (AAPL) | $355.63 | +2.04% | 11-11 종가 | 전반적 반도체·기술주 랠리에 동반 상승. UBS는 폴더블 아이폰 Duo 공급이 부족해 배송이 1월 말로 밀린다고 봤음 | [stockanalysis.com](https://stockanalysis.com/stocks/aapl/) |
| 엔비디아 (NVDA) | $173.73 | +2.87% | 11-11 종가 | 정규장은 반도체주 전반 반등에 상승 마감했으나, 마감 후 CEO 젠슨 황의 두 번째 혼외관계 의혹(NYT)과 이사회의 해임 추진설(WSJ)이 겹쳐 시간외 거래에서 약 −8% 급락했음 | [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) |
| 마이크로소프트 (MSFT) | $521.13 | −2.26% | 11-11 종가 | 전반적 시장 반등 속에서도 이틀째 하락. Anthropic의 엑셀 경쟁 기능(Claude Sheets)과 OpenAI의 대규모 영업손실 보도로 AI 경쟁 구도 변화가 부각됐음 | [stockanalysis.com](https://stockanalysis.com/stocks/msft/) |
| AMD | $552.90 | +7.30% | 11-11 종가 | 코어위브 실적 호조에 따른 반도체주 전반 급등 속 슈퍼마이크로의 AMD 기반 AI 서버 출하 소식(SMCI +11%)이 겹쳐 관심 종목 중 가장 큰 폭으로 상승했음 | [stockanalysis.com](https://stockanalysis.com/stocks/amd/) |
| 알파벳 (GOOGL) | $293.45 | +2.09% | 11-11 종가 | 신규 AI 모델 'AlphaGenome 2' 발표와 테슬라 로보택시의 텍사스 등록 차량 수가 구글 자회사 웨이모를 앞질렀다는 소식이 함께 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/googl/) |
| 테슬라 (TSLA) | $390.84 | +2.93% | 11-11 종가 | 머스크가 텍사스 공장의 사이버트럭 생산을 2027년 여름 말까지 연장한다고 밝히며 장중 주가가 추가로 올랐고, 로보택시의 텍사스 등록 차량 수가 웨이모를 앞섰다는 소식도 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/tsla/) |
| 스페이스X (SPCX) | $139.75 | −2.38% | 11-11 종가 | AI 인프라 투자 지속 가능성에 대한 우려와 다음 스타십 시험비행을 앞둔 경계감에 약세였으나, 'Grok Voice 3.0' 공개와 FCC의 스펙트럼 라이선스 인수 신청 접수 소식도 있었음 | [stockanalysis.com](https://stockanalysis.com/stocks/spcx/) |
| 삼성전자 | 206,000원 | +3.57% | 11-11 종가 | 반도체 수출 급증(11월 1~10일 전년대비 +331%)과 美 코어위브 실적발 AI 호재에 이틀 연속 상승했음 | [kr.investing.com](https://kr.investing.com/equities/samsung-electronics-co-ltd-historical-data) |
| SK하이닉스 | 1,277,000원 | +5.36% | 11-11 종가 | 마이크론 실적 호조(+11.89%)·SK하이닉스 ADR(+9.71%) 급등 등 메모리 반도체주 전반 강세에 이틀 연속 상승했음 | [kr.investing.com](https://kr.investing.com/equities/sk-hynix-inc-historical-data) |

<sub>개별 종목 등락률은 [2026-11-11 브리핑](2026-11-11-NewsBriefing.md)에서 확인된 11-10 종가(애플 $348.53·엔비디아 $168.78·MS $533.20·AMD $515.30·알파벳 $287.44·테슬라 $379.73·스페이스X $143.16·삼성전자 198,900원·SK하이닉스 1,212,000원)와 위 11-11 종가를 `python3 -c`로 직접 계산. 엔비디아의 시간외 거래 하락(−8%대, [kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488) 11-12 07:40 KST 입력; $159.45 부근, [stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 17:47 ET 기준)는 정규장 종가(173.73달러)에는 반영되지 않았음.</sub>

## 4. 주요 뉴스 (최대 5건)
1. **엔비디아 CEO 젠슨 황, 이사회 해임 추진 보도 — 두 번째 혼외관계 의혹 겹쳐 시간외 급락** — 뉴욕타임스는 11-11(현지) 황 CEO가 자신에게 직접 보고하는 헬스케어 담당 부사장 킴벌리 파월과 혼외 관계를 맺어왔다고 직원 5명의 진술을 인용해 보도했다(앞서 지난 주말에는 중국 스파이 의혹 인물 앨리스 황과의 관계를 인정한 바 있음). 이어 월스트리트저널은 엔비디아 이사회가 황 CEO 해임을 준비하고 있으며 이르면 가까운 시일 내 회의를 열어 거취를 결정할 것으로 보인다고 보도했다. 엔비디아 주가는 이 보도들이 겹치며 수요일 시간외 거래에서 약 8% 급락했다. ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488), 11-12 07:40 입력)
2. **코어위브 실적 호조에 반도체·데이터센터주 급등 — 나스닥 1.6%↑** — 코어위브가 3분기 매출 전망을 상향하고 향후 3개월 고객 선수금·예치금이 약 90억달러에 이를 것이라고 밝히며 주가가 24.71% 폭등했다. AI 인프라 투자 지속 가능성에 대한 우려가 완화되며 11-11(현지) 다우존스(+0.48%)·S&P500(+1.31%)·나스닥종합(+1.60%)이 모두 올랐고, 기술·석유가스·산업재 업종이 상승을 이끌었다. ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-048-5019892), 11-11 16:30 입력)
3. **마이크론·SK하이닉스 ADR·인텔 등 반도체주 동반 급등 — 뉴욕증시 특징주** — 코어위브 실적을 계기로 AI 인프라 투자 둔화 우려가 완화되며 11-11(현지) 마이크론(+11.89%)·SK하이닉스 ADR(+9.71%)·인텔(+7.52%)·AMD(+7.32%)가 급등했고, 필라델피아반도체지수는 구성 종목 전부 상승하며 +5.66%를 기록했다. 엔비디아도 장중 +2.87% 반등했다. ([kr.investing.com(뉴욕증시 특징주)](https://kr.investing.com/news/assorted/article-2171476), 11-12 07:39 입력)
4. **코스피·코스닥 동반 급등 — AI 호재·반도체 수출 331%↑·코스닥 빚투 정리 겹쳐** — 11-11 코스피는 2.60% 오른 5,375.36, 코스닥은 5.62% 오른 705.10으로 마감해 이틀 연속 급등(2거래일 코스피 +7.10%·코스닥 +10.35%)했다. 코어위브 실적과 앤트로픽 IPO 로드쇼 흥행이 AI 투자심리를 자극했고, 11월 1~10일 반도체 수출이 전년대비 331% 늘었다는 지표도 투자심리를 개선했다. 코스닥에서는 신용거래융자 잔고가 하루 만에 약 1조5,200억원 줄며 매물 부담이 완화된 점도 반등에 기여했다. ([머니투데이](https://www.mt.co.kr/stock/2026/11/11/2026111115584690277), [머니투데이](https://www.mt.co.kr/stock/2026/11/11/2026111117172525579), 11-11 17:30·17:37 입력)
5. **앤트로픽 IPO 로드쇼 흥행 — 기업가치 1조5,000억달러 이상 상향 검토** — 로드쇼 첫날 투자 수요가 강하게 확인되며 앤트로픽이 기업공개(IPO) 기업가치를 1조5,000억달러 이상으로 상향하는 방안을 검토하고 있다는 보도가 나왔다. 국내에서는 이 소식이 반도체·AI 관련주 투자심리를 자극한 요인으로 꼽혔다. ([머니투데이](https://www.mt.co.kr/stock/2026/11/11/2026111115584690277), 11-11 17:30 입력)

## 5. 오늘 일정
- 국내 11월물 옵션만기일 — 수급 변동성 주목 ([머니투데이](https://www.mt.co.kr/stock/2026/11/11/2026111115584690277), 11-11 17:30 입력)
- 엔비디아 이사회가 CEO 젠슨 황의 거취를 결정할 회의를 열 것으로 보도됨(정확한 시점 확인 필요) ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488), 11-12 07:40 입력)
- 다음 美 지표는 10월 PPI(생산자물가지수), 11-13(금) 08:30 ET(22:30 KST) 발표 예정 ([BLS 일정](https://www.bls.gov/schedule/news_release/ppi.htm))
- 국내·미국 증시 휴장 없음 ([kr.investing.com 휴장일 캘린더](https://kr.investing.com/holiday-calendar/), [investing.com 휴장일 캘린더](https://www.investing.com/holiday-calendar/))
- 관심 종목(애플·엔비디아·MS·AMD·알파벳·테슬라·스페이스X·삼성전자·SK하이닉스) 모두 3분기 실적 발표를 이미 마쳤고, 엔비디아의 다음(4분기) 실적 발표는 11-17로 예정돼 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/nvda/) 관련 투자자 일정, [2026-11-08 다음 주 미리보기](2026-11-08-NewsBriefing.md) 참고)

## 6. 전망 (자체 판단)
**직전 전망 점검:** 직전 일일 브리핑([2026-11-11](2026-11-11-NewsBriefing.md))의 전망 13건(판단 보류 1건[애플] 제외, 방향성 불분명 11건·하락 우세 1건[엔비디아], 일일 밴드 ±0.5%)을 11-10→11-11 종가로 확인한 결과 적중 0건, 빗나감 12건(KOSPI +2.60%·KOSDAQ +5.62%·S&P500 +1.31%·NASDAQ +1.60%·엔비디아 +2.87%[하락 우세 예측과 반대]·MS −2.26%·AMD +7.30%·알파벳 +2.09%·테슬라 +2.93%·스페이스X −2.38%·삼성전자 +3.57%·SK하이닉스 +5.36%는 모두 ±0.5% 밴드를 벗어나거나 예측 방향과 반대), 판단 보류 1건(애플, 집계 제외). 코어위브 실적을 계기로 AI 인프라 투자심리가 예상보다 훨씬 강하게 되살아나며 美·국내 지수와 반도체주 전반이 큰 폭으로 올라, 전일 "방향성 불분명"·"하락 우세" 예측을 모두 벗어난 하루였다.

| 대상 | 방향 | 기간 | 판단 근거 (출처) | 반대 요인 | 확신도 |
|---|---|---|---|---|---|
| KOSPI | 방향성 불분명 | 11-12~11-13 | 상승: 11월 1~10일 반도체 수출이 전년대비 331% 늘었고, 코어위브 실적·앤트로픽 IPO 로드쇼 흥행이 AI 투자심리를 자극했다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/11/2026111115584690277))<br>하락: 엔비디아 CEO 해임 추진 보도로 글로벌 반도체·AI 투자심리가 다시 흔들릴 수 있다 ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488)) | 이틀간 코스피가 +7.10% 오른 뒤라 단기 과열에 따른 되돌림 매물이 나올 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| KOSDAQ | 방향성 불분명 | 11-12~11-13 | 상승: 신용거래융자 잔고가 하루 만에 약 1조5,200억원 줄며 매물 부담이 완화됐고, 반도체 수출 증가도 투자심리를 개선했다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/11/2026111117172525579))<br>하락: 코스피와 마찬가지로 엔비디아 CEO 해임 추진 보도가 투자심리에 부담을 줄 수 있다 ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488)) | 이틀간 코스닥이 +10.35% 오른 뒤라 단기 과열에 따른 되돌림 매물이 나올 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| S&P 500 | 방향성 불분명 | 11-12~11-13 | 상승: 코어위브의 실적 호조와 고객 선수금 확보 소식에 AI 인프라 투자 지속 가능성에 대한 우려가 완화됐다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-048-5019892))<br>하락: 시가총액 최상위 엔비디아의 CEO 해임이 추진되고 있다는 보도로 시간외 거래에서 주가가 약 8% 급락했다 ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488)) | 10월 PPI(11-13) 결과에 따라 변동성이 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| NASDAQ | 방향성 불분명 | 11-12~11-13 | 상승: 마이크론(+11.89%)·AMD(+7.32%)·인텔(+7.52%) 등 반도체주가 코어위브 실적을 계기로 동반 급등했다 ([kr.investing.com(뉴욕증시 특징주)](https://kr.investing.com/news/assorted/article-2171476))<br>하락: 나스닥 시총 2위 엔비디아가 CEO 해임 추진 보도로 시간외 거래에서 약 8% 급락해 지수 비중이 큰 종목에 큰 불확실성이 생겼다 ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488)) | 10월 PPI(11-13) 결과에 따라 변동성이 더 커질 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| 애플 (AAPL) | 하락 우세 | 11-12~11-13 | 1. UBS는 폴더블 아이폰 Duo의 공급 부족으로 배송이 1월 말로 밀린다고 평가했다 ([stockanalysis.com](https://stockanalysis.com/stocks/aapl/) 관련 TipRanks 기사, 11-11)<br>2. 2027년을 앞두고 애플 주가가 고평가된 것으로 보인다는 분석이 나왔다 (같은 출처, 다른 TipRanks 기사, 11-11) | 반도체·AI 투자심리 회복에 따른 시장 전반 랠리에 동반 상승할 수 있다 ([investing.com](https://www.investing.com/news/stock-market-news/us-stocks-higher-at-close-of-trade-dow-jones-industrial-average-up-048-5019892)) | 낮음 — 근거 2건 모두 애널리스트 코멘터리 수준 |
| 엔비디아 (NVDA) | 하락 우세 | 11-12~11-13 | 1. 뉴욕타임스가 직원 5명의 진술을 인용해 황 CEO가 직속 부하인 킴벌리 파월 부사장과 혼외 관계를 맺어왔다고 보도했다 ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488) 관련 NYT 보도)<br>2. 월스트리트저널은 이사회가 황 CEO 해임을 준비하고 있다고 보도했고, 주가는 이 보도들이 겹치며 시간외 거래에서 약 8% 급락했다 ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488)) | 엔비디아 측이 아직 공식 입장을 밝히지 않았고, 11-08 이사회는 국가안보·기업비밀 유출 증거가 없다며 황 CEO에 대한 신뢰를 표명한 바 있어 해임 보도가 뒤집힐 가능성도 남아 있다 ([2026-11-09 브리핑](2026-11-09-NewsBriefing.md) 참고) | 보통 — 독립적 하락 근거 2개(2차 혼외관계 의혹, 해임 추진 보도)가 있으나 회사의 공식 확인은 없음 |
| 마이크로소프트 (MSFT) | 방향성 불분명 | 11-12~11-13 | 상승: AI 데이터센터 수요와 기관 자금 유입으로 7월 저점 대비 51.4% 상승했다는 분석이 유지되고 있다 ([stockanalysis.com](https://stockanalysis.com/stocks/msft/) 관련 FXEmpire 기사, 11-11)<br>하락: Anthropic의 엑셀 경쟁 기능(Claude Sheets)과 OpenAI의 대규모 영업손실 보도로 AI 경쟁 구도 변화가 부각되며 전반적 시장 반등 속에서도 이틀째 하락했다 (같은 출처, Invezz 기사, 11-11) | 10월 PPI(11-13) 등 시장 전반 변동성에 영향받을 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| AMD | 방향성 불분명 | 11-12~11-13 | 상승: 코어위브 실적 호조에 반도체주 전반이 급등했고, 슈퍼마이크로의 AMD 기반 AI 서버 출하 소식(SMCI +11%)이 겹쳤다 ([stockanalysis.com](https://stockanalysis.com/stocks/amd/) 관련 Invezz 기사, 11-11)<br>하락: Theotrade의 한 트레이더는 AMD에 대해 약세 견해를 밝혔고, 단기간 급등을 거친 뒤라 되돌림 리스크가 남아 있다 (같은 출처, Schwab Network 기사, 11-11) | 반도체 업종에 새로운 불확실성(엔비디아 CEO 해임 추진)이 번지면 투자심리가 다시 악화될 수 있다 ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488)) | 낮음 — 상승·하락 근거가 팽팽함 |
| 알파벳 (GOOGL) | 방향성 불분명 | 11-12~11-13 | 상승: 신규 AI 모델 'AlphaGenome 2'를 발표했고, 회계 업무 AI 벤치마크에서 상위권에 오른 Gemini 4 Carbon 모델 소식도 있었다 ([stockanalysis.com](https://stockanalysis.com/stocks/googl/), 11-11)<br>하락: 테슬라 로보택시의 텍사스 등록 차량 수가 구글 자회사 웨이모를 앞질렀다는 보도가 나왔다 (같은 출처, TipRanks 기사, 11-11) | 2026-05-19~07-16 공시 누락 의혹을 다루는 증권 사기 집단소송(원고 대표 신청 마감 12-01)은 여전히 남아 있다 ([2026-11-10 브리핑](2026-11-10-NewsBriefing.md) 참고) | 낮음 — 상승·하락 근거가 팽팽함 |
| 테슬라 (TSLA) | 상승 우세 | 11-12~11-13 | 1. 머스크가 텍사스 공장의 사이버트럭 생산을 2027년 여름 말까지 연장한다고 밝히자 장중 주가가 약 4% 올라 $394 부근까지 상승했다 ([stockanalysis.com](https://stockanalysis.com/stocks/tsla/) 관련 TipRanks 기사, 11-11)<br>2. 로보택시의 텍사스 등록 차량 수가 구글 자회사 웨이모를 앞질렀다는 보도가 나왔다 (같은 출처, TipRanks 기사, 11-11) | 반도체·AI 투자심리가 엔비디아 CEO 해임 추진 보도로 다시 흔들리면 기술주 전반이 동반 하락할 수 있다 ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488)) | 보통 — 독립적 상승 근거 2개(사이버트럭 생산 연장, 로보택시 확대)가 있고 시장이 즉각 반응함 |
| 스페이스X (SPCX) | 방향성 불분명 | 11-12~11-13 | 상승: 음성 대화형 AI 모델 'Grok Voice 3.0'을 공개했고, FCC가 Grain Management 계열 라이선스 회사 인수 신청을 접수했다 ([stockanalysis.com](https://stockanalysis.com/stocks/spcx/), 11-11)<br>하락: AI 인프라 투자 지속 가능성에 대한 우려와 다음 스타십 시험비행을 앞둔 경계감이 겹쳐 11-11 주가가 밀렸다 (같은 출처, Invezz 기사, 11-11) | 엔비디아 CEO 해임 추진 보도로 AI 섹터 전반 투자심리가 흔들리면 추가 하락 압력이 될 수 있다 ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488)) | 낮음 — 상승·하락 근거가 팽팽함 |
| 삼성전자 | 방향성 불분명 | 11-12~11-13 | 상승: 11월 1~10일 반도체 수출이 전년대비 331% 늘었고, 코어위브 실적발 AI 인프라 수요 확인이 투자심리를 개선했다 ([머니투데이](https://www.mt.co.kr/stock/2026/11/11/2026111115584690277))<br>하락: 엔비디아 CEO 해임 추진 보도로 반도체 공급망 전반의 투자심리가 흔들릴 수 있다 ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488)) | 이틀간 +8.5%대 급등한 뒤라 단기 과열에 따른 되돌림 매물이 나올 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |
| SK하이닉스 | 방향성 불분명 | 11-12~11-13 | 상승: 마이크론 실적 호조(+11.89%)·SK하이닉스 ADR(+9.71%) 급등 등 메모리 반도체주 전반에 매수세가 유입됐다 ([kr.investing.com(뉴욕증시 특징주)](https://kr.investing.com/news/assorted/article-2171476))<br>하락: 삼성전자와 같은 이유로 엔비디아 CEO 해임 추진 보도가 반도체 공급망 전반에 부담을 줄 수 있다 ([kr.investing.com(WSJ 인용)](https://kr.investing.com/news/stock-market-news/article-2171488)) | 이틀간 +12.4%대 급등한 뒤라 단기 과열에 따른 되돌림 매물이 나올 수 있다 | 낮음 — 상승·하락 근거가 팽팽함 |

<sub>전망은 위 출처의 공개된 사실에 근거한 자체 판단이며 틀릴 수 있습니다. 가격 목표·확률·매매 의견이 아니며 투자 권유가 아닙니다.</sub>

---
<sub>수치는 각 출처의 기준 시각 값이며 실시간이 아닙니다. 확인되지 않은 항목은 "확인 필요"로 표시합니다. 매수·매도 의견과 목표가는 제공하지 않습니다.</sub>
