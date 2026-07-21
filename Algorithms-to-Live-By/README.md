# 알고리즘, 인생을 계산하다 (Algorithms to Live By)

브라이언 크리스천(Brian Christian) & 톰 그리피스(Tom Griffiths)의 『알고리즘, 인생을 계산하다 Algorithms to Live By』를 장(章)별로 분석하고, 1976년생·2026년 50세에 경제적 자유를 달성해 인출기(decumulation phase)에 접어든 자산가의 실제 투자 철학(2버킷 구조, 연 2\~3% 인출, 6개월 현금 버퍼, 국가·산업 집중도)에 대입해 정리한 개인 독서 저장소입니다.

---

## 📖 책 전체 개관

| 문서 | 내용 |
|---|---|
| [Algorithms-to-Live-By.md](Algorithms-to-Live-By.md) | 저자 소개, 집필 배경, 전체 목차, 장별 핵심 내용, 이 책을 관통하는 틀 |
| [Template61.md](Template61.md) | 챕터별 분석에 사용하는 출력 형식·글쓰기 원칙 프롬프트/템플릿 |

---

## 📚 챕터별 상세 분석 (전 11장 + 결론)

| 장 | English Title | 한글 제목 | 다루는 핵심 알고리즘/개념 | 링크 |
|---|---|---|---|---|
| 01 | Optimal Stopping | 최적 정지 — 언제 찾기를 멈출 것인가 | 비서 문제(Secretary Problem), 37% 규칙 | [열기](chapter01-Optimal-Stopping.md) |
| 02 | Explore/Exploit | 탐색과 활용 — 최신 것과 최고의 것 사이 | 다중 슬롯머신 문제, 깃킨스 지수, 상한신뢰구간(UCB) | [열기](chapter02-Explore-Exploit.md) |
| 03 | Sorting | 정렬 — 질서를 만드는 법 | 정렬 알고리즘, 빅오 표기법 | [열기](chapter03-Sorting.md) |
| 04 | Caching | 캐싱 — 무엇을 잊을 것인가 | LRU, 벨라디의 알고리즘 | [열기](chapter04-Caching.md) |
| 05 | Scheduling | 스케줄링 — 무엇을 먼저 할 것인가 | 최단처리시간우선(SPT), 마감시한우선(EDF) | [열기](chapter05-Scheduling.md) |
| 06 | Bayes's Rule | 베이즈 법칙 — 미래를 예측하는 법 | 사전확률, 코페르니쿠스 원리, 라플라스의 계승 법칙 | [열기](chapter06-Bayess-Rule.md) |
| 07 | Overfitting | 과적합 — 덜 생각해야 할 때 | 정규화, 조기 종료, 편향-분산 트레이드오프 | [열기](chapter07-Overfitting.md) |
| 08 | Relaxation | 이완 — 제약을 느슨하게 하기 | 제약 완화, 라그랑주 이완 | [열기](chapter08-Relaxation.md) |
| 09 | Randomness | 무작위성 — 운에 맡겨야 할 때 | 몬테카를로 방법, 무작위 알고리즘 | [열기](chapter09-Randomness.md) |
| 10 | Networking | 네트워킹 — 우리가 연결되는 방식 | TCP 흐름 제어, 지수 백오프 | [열기](chapter10-Networking.md) |
| 11 | Game Theory | 게임 이론 — 타인의 마음 | 내시균형, 경매 이론, 정보 폭포 | [열기](chapter11-Game-Theory.md) |
| 결론 | Conclusion: Computational Kindness | 계산적 친절함 | 상대방의 계산 비용을 줄여주는 배려 | [열기](chapter12-Computational-Kindness.md) |

각 챕터 파일은 `Template61.md` 기준 다음 섹션으로 구성됩니다.

1. 핵심 메시지
2. 인상적인 문장
3. 주요 개념 정리
4. 상세 설명 (논증 흐름 재구성 / 전산학적·역사적 배경 / 실제 삶·자산관리 메커니즘 / 뉘앙스와 한계 / 나의 삶과 자산관리 계획으로의 연결)
5. 더 생각해볼 질문
6. 나에게 적용하기
7. 실행 원칙
8. 한 문장으로 정리
9. ETC (영어·전산학 용어 정리)

> ⚠️ `chapter12-Computational-Kindness.md`는 원서의 본문 11개 장에는 포함되지 않는 결론(Conclusion) 챕터입니다. 별도의 번호가 매겨진 장은 아니지만, 인간관계·소통이라는 주제가 자산관리 분석과 유의미하게 연결되어 선택적으로 정리했습니다.

---

## 🧭 분석 기준이 된 개인 프로필

- 1976년생, 2026년 50세에 경제적 자유 달성 및 은퇴, 순자산 약 000억 원
- 포트폴리오를 2개로 분리: 고수익 추구형 / 자본 보존형
- 연 2\~3% 인출 (전년 수익금의 1/3 이내)
- 6개월 생활비는 현금성·안전자산으로 보유
- 특정 국가(한국)·산업(미국 빅테크, 반도체) 집중을 점진적으로 분산
- 돈은 목적이 아니라 수단이며, 건강·가족·배움·경험·사회 기여를 중시

## 🔑 분석의 핵심 축

이 책의 핵심 발견 — 탐색(explore)과 활용(exploit) 사이의 최적 균형은 고정된 규칙이 아니라 **남은 시간(time horizon)의 함수**이며(2장), 과거 데이터에 지나치게 정교하게 맞추려는 시도는 오히려 미래에 대한 일반화 능력을 해친다는 **과적합(overfitting, 7장)** — 을 축적기(accumulation phase)를 끝내고 인출기(decumulation phase)에 접어든 자신의 실제 포트폴리오와 정직하게 대조하는 것이 모든 챕터 분석의 공통된 축입니다. 특히 한국·미국 빅테크·반도체 집중이 "남은 시간에 맞는 정당한 활용"인지, 아니면 "과거 성공 데이터에 대한 과적합"인지를 회피하지 않고 다룹니다.

※ 저본: Brian Christian & Tom Griffiths, *Algorithms to Live By: The Computer Science of Human Decisions*, Henry Holt and Co. (2016). 국내 번역본은 『알고리즘, 인생을 계산하다』(이한음 옮김, 청림출판, 2018)입니다. 각 챕터 파일의 인용문은 원서 및 공식 발췌 페이지([algorithmstoliveby.com/excerpt](https://algorithmstoliveby.com/excerpt.html))를 참고했으며, 국내 정식 번역본 문구를 직접 대조하지 못한 경우 필자의 직접 번역임을 각 파일에서 밝히고 있습니다.
