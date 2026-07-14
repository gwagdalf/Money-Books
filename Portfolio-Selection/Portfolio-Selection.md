# 포트폴리오 셀렉션 (Portfolio Selection: Efficient Diversification of Investments)

> **"Diversification is both observed and sensible; a rule of behavior which does not imply the superiority of diversification must be rejected both as a hypothesis and as a maxim."**
> — 해리 마코위츠, 『Portfolio Selection』
> *(분산투자는 실제로 관찰되며 또한 합리적이다. 분산투자의 우월성을 함의하지 않는 행동 규칙은 가설로서도 격언으로서도 기각되어야 한다.)*
> ※ 위 문장은 마코위츠의 1952년 논문 "Portfolio Selection"(Journal of Finance)에서 널리 인용되는 문장으로, 이 책(1959년 단행본)에도 같은 논지가 이어진다. 확인된 국내 정식 번역본이 없으므로 직접 번역했음을 밝힌다.

---

## 기본 정보

| 항목 | 내용 |
|------|------|
| **원제** | Portfolio Selection: Efficient Diversification of Investments |
| **한국어 제목** | 확인된 국내 정식 번역본 없음 (원제 직접 번역: 포트폴리오 셀렉션: 효율적인 투자 분산) |
| **저자** | 해리 M. 마코위츠(Harry M. Markowitz, 1927\~2023) |
| **저자의 신분** | 미국의 경제학자. 1952년 「저널 오브 파이낸스(Journal of Finance)」에 발표한 논문 "Portfolio Selection"에서 평균-분산 최적화(mean-variance optimization)에 기반한 현대 포트폴리오 이론(Modern Portfolio Theory, MPT)을 최초로 제시했다. 이 책은 그 논문을 카울스 재단(Cowles Foundation)의 지원을 받아 단행본 분량으로 확장한 것이다. 마코위츠는 이 업적으로 1990년 노벨 경제학상을 윌리엄 샤프(William Sharpe), 머턴 밀러(Merton Miller)와 공동 수상했다 |
| **출간 경위** | 1959년 미국에서 John Wiley & Sons를 통해 초판 출간 (Cowles Foundation Monograph No. 16, ISBN 978-0-300-01372-6). 이후 예일대학교 출판부(Yale University Press) 등에서 재출간되었다 |
| **분야** | 금융경제학·수리금융 학술서 — 분산투자의 수학적 기초를 정식화한 현대 포트폴리오 이론의 원전 |
| **핵심 개념** | 평균-분산 분석(Mean-Variance Analysis), 효율적 프론티어(Efficient Frontier), 분산과 공분산(Variance and Covariance), 기대효용 극대화(Expected Utility Maxim), 준분산(Semi-Variance) |
| **분량** | 전 4부(Part), 13개 장(Chapter)에 부록(Appendix) 3편으로 구성 |
| **영향력** | 이 책에서 정식화된 평균-분산 최적화는 이후 자본자산가격결정모형(CAPM), 효율적 시장 가설과 함께 현대 금융경제학의 이론적 토대가 되었으며, 오늘날 대부분의 자산배분·인덱스 펀드 이론의 수학적 뿌리다 |
| **성격** | 대중 투자서가 아니라, 확률론과 통계학을 이용해 "분산투자가 왜 합리적인가"를 수학적으로 증명하는 학술 논문에 가까운 단행본이다 |

---

## 책 소개

『포트폴리오 셀렉션』은 "계란을 한 바구니에 담지 마라"는 오래된 격언을, **평균(기대수익률)과 분산(위험)이라는 두 통계량만으로 포트폴리오를 수학적으로 최적화할 수 있다는 이론(평균-분산 분석)**으로 정식화한 책이다. 마코위츠 이전까지 "분산투자가 좋다"는 것은 경험적 직관이었지만, 그는 개별 자산들의 수익률 간 상관관계(공분산)를 고려하면, 서로 상관관계가 낮은 자산을 조합함으로써 동일한 기대수익률에서 위험을 줄이거나, 동일한 위험 수준에서 기대수익률을 높일 수 있다는 것을 수학적으로 증명했다. 이렇게 "주어진 위험 수준에서 최대 기대수익률을 내는" 포트폴리오들의 집합을 **효율적 프론티어(Efficient Frontier)**라 부른다.

책의 1부(1\~2장)는 문제의식과 예시적 포트폴리오 분석을 소개하고, 2부(3\~6장)는 평균·분산·공분산 등 이 이론을 뒷받침하는 통계적 기초를 다진다. 3부(7\~9장, 부(Part) 제목 자체가 "Efficient Portfolios")는 이 책의 핵심으로, 효율적 프론티어를 기하학적·대수적으로 도출하는 방법과 그 변형(준분산 등)을 다룬다. 4부(10\~13장)는 불확실성 하에서의 합리적 선택 이론(기대효용 극대화, 확률적 신념 등)이라는 더 깊은 이론적 토대를 다지고, 이를 포트폴리오 선택 문제에 실제로 적용하는 것으로 마무리된다. 부록은 효율적 집합의 계산법, 심플렉스법을 이용한 포트폴리오 최적화 알고리즘 등 실무적·수학적 세부 사항을 다룬다.

이 책의 역사적 의의는 단순한 실용적 조언을 넘어, **투자를 "감(感)"이 아니라 확률론에 기반한 정량적 최적화 문제로 재정의**했다는 데 있다. 다만 마코위츠 자신도 후속 연구자들도 지적했듯, 이 이론은 자산 수익률의 정규분포 가정, 안정적인 상관관계 추정치 등 현실에서는 완벽히 성립하지 않는 여러 전제 위에 서 있으며, 이후 행동재무학·꼬리위험(tail risk) 연구 등에서 이 전제들에 대한 비판이 이어졌다.

### 이 책을 관통하는 핵심 틀

```
Part I: 서론과 예시 (1\~2장)
  → 문제의식의 제시와 예시적 포트폴리오 분석

Part II: 증권과 포트폴리오 사이의 관계 (3\~6장)
  → 평균과 기댓값, 표준편차와 분산, 다수 증권에 대한 투자,
    장기적 수익률의 통계적 성질

Part III: 효율적 포트폴리오 (부 제목, 7\~9장)
  → 효율적 프론티어의 기하학적 분석과 대수적 도출 →
    준분산(Semi-Variance)이라는 위험 측정의 대안

Part IV: 불확실성 하의 합리적 선택 (10\~13장)
  → 기대효용 극대화 원리 → 시간에 걸친 효용 분석 →
    확률적 신념 → 포트폴리오 선택 문제에의 적용

부록 A\~C
  → 효율적 집합의 계산법, 심플렉스법을 이용한 포트폴리오 최적화,
    기대효용에 대한 대안적 공리 체계
```

---

## 목차 (Table of Contents)

『Portfolio Selection: Efficient Diversification of Investments』(1959년, John Wiley & Sons 초판, Cowles Foundation Monograph No. 16)는 **전 4부(Part), 13개 장(Chapter)**에 부록(Appendix) 3편으로 구성된다.

| 챕터 번호 | 영문 제목 | 한글 제목(의역) |
|-----------|-----------|------------------|
| **Part I: Introduction and Illustrations** | | |
| 1장 | Introduction | 서론 |
| 2장 | Illustrative Portfolio Analyses | 예시적 포트폴리오 분석 |
| **Part II: Relationships Between Securities and Portfolios** | | |
| 3장 | Averages and Expected Values | 평균과 기댓값 |
| 4장 | Standard Deviations and Variances | 표준편차와 분산 |
| 5장 | Investment in Large Numbers of Securities | 다수 증권에 대한 투자 |
| 6장 | Return in the Long Run | 장기적 수익률 |
| **Part III: Efficient Portfolios** (부 제목 — 별도 장이 아님) | | |
| 7장 | Geometric Analysis of Efficient Sets | 효율적 집합의 기하학적 분석 |
| 8장 | Derivation of E, V Efficient Portfolios | 기대값-분산 효율적 포트폴리오의 도출 |
| 9장 | The Semi-Variance | 준분산 |
| **Part IV: Rational Choice Under Uncertainty** | | |
| 10장 | The Expected Utility Maxim | 기대효용 극대화 원리 |
| 11장 | Utility Analysis over Time | 시간에 걸친 효용 분석 |
| 12장 | Probability Beliefs | 확률적 신념 |
| 13장 | Applications to Portfolio Selection | 포트폴리오 선택에의 적용 |
| 부록 A | The Computation of Efficient Sets | 효율적 집합의 계산 |
| 부록 B | A Simplex Method for the Portfolio Selection Problem | 포트폴리오 선택 문제를 위한 심플렉스법 |
| 부록 C | Alternative Axiom Systems for Expected Utility | 기대효용에 대한 대안적 공리 체계 |

※ 위 표는 원서(John Wiley & Sons, 1959, Cowles Foundation Monograph No. 16) 목차 및 Cowles Foundation 공식 페이지·복수의 서지 정보(JSTOR, 서평)를 상호 대조해 정리했다. 이전 버전에서는 Part III의 부(Part) 제목 "Efficient Portfolios"를 별도의 7장으로 잘못 기재해 이후 장 번호가 한 칸씩 밀려 있었으나(원서는 4부 13개 장이며, 3부는 부 제목만 "Efficient Portfolios"이고 실제 7장은 "Geometric Analysis of Efficient Sets"), 이번에 원서 목차 기준으로 바로잡았다. 이 책은 확인된 국내 정식 번역본이 없는 고도로 수리적인 학술서이므로, 각 장 내부의 정확한 절 구성·수식 전개는 원서 실물로 반드시 재확인한다.

---

## 핵심 주제 요약

### 1. 평균-분산 분석 (Mean-Variance Analysis)
포트폴리오의 기대수익률(평균)과 위험(분산)이라는 두 통계량만으로 투자 결정을 정식화하는, 이 책의 가장 핵심적인 분석틀.

### 2. 효율적 프론티어 (Efficient Frontier)
주어진 위험 수준에서 최대 기대수익률을 내는, 혹은 주어진 기대수익률에서 최소 위험을 내는 포트폴리오들의 집합.

### 3. 분산투자의 수학적 근거
개별 자산 간 상관관계(공분산)가 낮을수록 분산투자를 통한 위험 감소 효과가 커진다는 것을 수학적으로 증명 — "계란을 한 바구니에 담지 마라"는 격언의 정량적 근거.

### 4. 기대효용 극대화 (Expected Utility Maxim)
불확실성 하에서 합리적 투자자가 무엇을 극대화해야 하는지에 대한 이론적 기초 — 폰 노이만-모겐슈테른의 기대효용 이론을 포트폴리오 선택 문제에 접목한다.

### 5. 이론의 한계 — 정규분포 가정과 현실
자산 수익률이 정규분포를 따른다는 가정, 안정적인 상관관계 추정치에 의존한다는 점에서, 이 이론은 극단적 사건(꼬리위험)이나 상관관계가 급변하는 위기 상황을 충분히 반영하지 못한다는 이후의 비판적 논의도 함께 고려해야 한다.

---

## 이 책을 읽어야 하는 이유

1. **현대 포트폴리오 이론의 원전** — 오늘날 거의 모든 자산배분 이론(효율적 프론티어, 샤프 비율, 인덱스 투자의 이론적 근거 등)이 이 책에서 출발한다.
2. **분산투자를 감이 아닌 수학으로 이해** — "왜 분산투자가 합리적인가"를 직관이 아니라 엄밀한 수리적 증명으로 이해할 수 있다.
3. **노벨 경제학상 수상 이론의 원본** — 이후 파생된 여러 대중적 투자서보다, 이론이 실제로 어떻게 전개되는지 원전에서 직접 확인할 수 있다.
4. **이론의 한계를 이해하는 출발점** — 이 책의 가정(정규분포, 안정적 상관관계)을 명확히 이해해야, 왜 2008년 금융위기 같은 사건에서 전통적 분산투자가 예상만큼 작동하지 않았는지도 더 잘 이해할 수 있다.
5. **인출기 투자자에게는 "은퇴 포트폴리오 설계"의 이론적 재점검 자료** — 2버킷 구조·국가·산업 집중도라는 나의 실제 자산배분이, 이 책이 제시하는 평균-분산 최적화의 논리로 볼 때 얼마나 "효율적 프론티어"에 가까운지, 혹은 감(感)에 의존한 배분인지 재점검하게 하는 텍스트다.

---

## 참고 자료

- Markowitz, Harry M., *Portfolio Selection: Efficient Diversification of Investments*, John Wiley & Sons, 1959년 초판 (Cowles Foundation Monograph No. 16, ISBN 978-0-300-01372-6)
- Markowitz, Harry M., "Portfolio Selection," *The Journal of Finance*, Vol. 7, No. 1, 1952 (이 책의 토대가 된 원 논문)
- [Portfolio Selection – JSTOR 서지정보](https://www.jstor.org/stable/j.ctt1bh4c8h)
- [해리 마코위츠 – 위키백과](https://ko.wikipedia.org/wiki/%ED%95%B4%EB%A6%AC_%EB%A7%88%EC%BD%94%EC%9C%84%EC%B8%A0)

※ 이 책은 확인된 국내 정식 번역본이 없으므로, 모든 한국어 표현은 직접 번역이다. 목차는 원서(John Wiley & Sons, 1959) 목차를 기준으로 정리했으며, 향후 개별 챕터 분석 파일을 작성할 때는 원서 실물(또는 예일대학교 출판부 재출간판)로 각 장의 수식·증명을 재확인한다.
