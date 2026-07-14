# AI를 위한 필수 수학 (Essential Math for AI)

※ 동명의 책이 여러 권 존재하므로 주의가 필요하다. book-list.csv의 저자 "할라 넬슨(Hala Nelson)"은 O'Reilly Media에서 2023년 출간한 정식 기술서의 저자와 일치한다. 이와 별개로 "Andrew Hinton"이라는 이름으로 출간된 동명의 책도 검색되었으나, 이는 이 저장소가 다루는 책이 아니다 — 반드시 Hala Nelson 저, O'Reilly 출간본을 기준으로 삼는다.

---

## 기본 정보

| 항목 | 내용 |
|------|------|
| **원제** | Essential Math for AI: Next-Level Mathematics for Efficient and Successful AI Systems |
| **한국어 제목** | 국내 정식 번역본 존재 여부를 확인하지 못했으므로, 확인 시 갱신 필요 |
| **저자** | 할라 넬슨 (Hala Nelson) |
| **저자의 신분** | 응용수학자, 제임스 매디슨 대학교(James Madison University) 수학과 부교수. 데이터 과학·AI 시스템에 응용수학을 접목하는 연구와 컨설팅을 수행 |
| **출간 경위** | 2023년 미국 O'Reilly Media에서 출간 |
| **분야** | 기술 교양서 — AI/머신러닝을 위한 수학 개론 |
| **구성** | 전 14개 장(chapter), 약 500쪽(원서 기준) |

---

## 책 소개

『Essential Math for AI』는 머신러닝·딥러닝 알고리즘을 실제로 이해하고 다루는 데 필요한 수학 — 선형대수, 확률과 통계, 최적화, 미적분, 그래프 이론 — 을 추상적 정리가 아니라 실제 AI 응용 사례(추천 시스템, 신경망, 자연어 처리, 컴퓨터 비전, 그래프 신경망 등)에 곧바로 연결해 설명하는 것이 특징이다. 저자 할라 넬슨은 순수 수학 이론을 나열하는 대신, "이 수학 개념이 실제로 어떤 AI 모델의 어느 부분에서 쓰이는가"를 항상 함께 보여주는 응용 중심 접근을 취한다.

책의 구성에 따르면, 1장은 "왜 AI의 수학을 배워야 하는가"라는 동기 부여로 시작하고, 2장은 데이터의 확률분포·전처리를 다룬다. 이후 회귀분석(3장)·신경망 최적화(4장)·합성곱 신경망과 컴퓨터 비전(5장)·특이값분해(6장)·자연어·금융 AI의 벡터화와 시계열(7장)·확률적 생성 모델(8장)·그래프 모델(9장)·오퍼레이션 리서치(10장)·확률(마르코프 과정·인과 모델링 등, 11장)·수리 논리학(12장)·편미분방정식(13장)을 거쳐, 마지막 14장은 AI 윤리·법·정책이라는 사회적 함의로 마무리된다. 각 장은 이론 설명 후 파이썬 코드 예제로 실제 구현을 보여주는 실습 중심 구성을 취한다.

---

## 목차 (Table of Contents)

『Essential Math for AI』(O'Reilly Media, 2023년판)는 **전 14개 장(Chapter)**으로 구성된다.

| 챕터 번호 | 영문 제목 | 한글 제목(의역) | 다루는 핵심 개념 |
|-----------|-----------|------------------|-------------------|
| 1 | Why Learn the Mathematics of AI? | AI 수학을 배워야 하는 이유 | 책의 동기 부여, AI 수학 학습의 필요성 |
| 2 | Data, Data, Data | 데이터, 데이터, 데이터 | 데이터의 확률분포, 전처리 |
| 3 | Fitting Functions to Data | 데이터에 함수 적합시키기 | 회귀분석 |
| 4 | Optimization for Neural Networks | 신경망을 위한 최적화 | 경사하강법, 역전파 |
| 5 | Convolutional Neural Networks and Computer Vision | 합성곱 신경망과 컴퓨터 비전 | 합성곱, CNN, Gabor 필터 |
| 6 | Singular Value Decomposition: Image Processing, Natural Language Processing, and Social Media | 특이값분해: 이미지 처리, 자연어 처리, 소셜 미디어 | SVD와 그 응용 |
| 7 | Natural Language and Finance AI: Vectorization and Time Series | 자연어와 금융 AI: 벡터화와 시계열 | 텍스트·시계열 데이터의 벡터화 |
| 8 | Probabilistic Generative Models | 확률적 생성 모델 | 이미지 생성 모델 등 |
| 9 | Graph Models | 그래프 모델 | 페이지랭크, 그래프 신경망 |
| 10 | Operations Research | 오퍼레이션 리서치(운용 과학) | 최적화 기반 의사결정 |
| 11 | Probability | 확률 | 확률의 역설, 베이지안 네트워크, 확률 과정(마르코프 체인 등), 인과 모델링과 do-계산법, 마르코프 결정 과정과 강화학습 |
| 12 | Mathematical Logic | 수리 논리학 | AI와 형식 논리 |
| 13 | Artificial Intelligence and Partial Differential Equations | 인공지능과 편미분방정식 | PDE 기반 AI 응용 |
| 14 | Artificial Intelligence, Ethics, Mathematics, Law, and Policy | 인공지능, 윤리, 수학, 법, 정책 | AI 윤리·정책의 수학적·사회적 함의 |

※ 위 표는 O'Reilly 공식 목차 페이지(각 장 URL, 예: `.../ch01.html`, `.../ch04.html`, `.../ch09.html`, `.../ch11.html`, `.../ch12.html`, `.../ch14.html`)에서 직접 확인한 장 제목과, 저자 공식 GitHub 부속자료(3\~6장 노트북 파일명) 및 Shroff Publishers(인도 현지 출판사)가 공개한 목차 자료를 상호 대조해 완성한 것이다. 종전에는 1·2·5장만 확인되고 나머지는 미확인 상태였으나, 이번 확인으로 전체 14개 장 제목이 모두 확정되었다.

---

## 핵심 주제 요약

### 1. 이론과 응용의 즉각적 연결
모든 수학 개념을 추상적으로 다루지 않고, 실제 AI 모델(추천 시스템, CNN, 그래프 신경망 등)의 구체적 부분과 즉시 연결해 설명하는 응용 중심 접근.

### 2. 선형대수와 확률의 이중 기둥
신경망의 가중치 행렬 연산(선형대수)과 데이터의 불확실성 모델링(확률·통계)이라는 AI 수학의 두 핵심 기둥을 균형 있게 다룬다.

### 3. 그래프 이론과 네트워크 알고리즘
페이지랭크 알고리즘, 그래프 신경망 등 관계형 데이터를 다루는 수학적 도구 — 추천 시스템·신약 개발·질병 확산 모델링 등 실제 응용과 연결된다.

### 4. 최적화와 역전파
신경망 학습의 핵심 메커니즘인 경사하강법·역전파를 수학적으로 뒷받침하는 최적화 이론.

---

## 이 책을 읽어야 하는 이유

1. **『마스터 알고리즘』·『인간과 호환되는 AI』의 수학적 기초 보완** — 이 저장소의 다른 AI 서적들이 개념적·정책적 논의를 다룬다면, 이 책은 그 개념들이 실제로 어떤 수학에 기반하는지 이해하게 해준다.
2. **AI 도구를 블랙박스가 아닌 이해된 도구로 활용** — AI 기반 투자 도구를 사용할 때, 내부 작동 원리(확률·최적화)를 이해하고 있으면 그 한계와 오류 가능성을 더 정확히 판단할 수 있다.
3. **그래프 이론 — 포트폴리오 네트워크 사고에 대한 수학적 도구** — 페이지랭크·그래프 신경망 같은 관계형 데이터 분석 도구는, 포트폴리오 내 자산 간 상관관계나 시장 참여자 네트워크를 정량적으로 사고하는 틀을 제공한다.
4. **평생 학습의 지적 도전 — 은퇴 후 새로운 기술 언어 습득** — 은퇴 후에도 AI 시대의 기초 언어(수학)를 직접 이해하려는 시도는, 새로운 기술에 대한 수동적 소비자가 아닌 능동적 이해자로 남기 위한 실천이다.

---

## 참고 자료

- Nelson, Hala, *Essential Math for AI: Next-Level Mathematics for Efficient and Successful AI Systems*, O'Reilly Media, 2023
- [Essential Math for AI – O'Reilly](https://www.oreilly.com/library/view/essential-math-for/9781098107628/)
- [Essential Math for AI – 저자 공식 GitHub 부속자료](https://github.com/halanelson/Essential-Math-For-AI)
- [Essential Math for AI – Amazon](https://www.amazon.com/Essential-Math-Next-Level-Mathematics-Successful/dp/1098107632)

※ 이 문서의 전체 14개 장 목차는 O'Reilly 공식 챕터 페이지·저자 GitHub 부속자료·Shroff Publishers 공개 자료를 상호 대조해 확정했다. 각 장 내부의 정확한 절 구성·수식·코드 예제는 원서 실물 또는 O'Reilly 플랫폼으로 반드시 재확인한다.
