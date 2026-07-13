# 와이 머신 런 (Why Machines Learn: The Elegant Math Behind Modern AI)

> **"Mathematics is the language in which machines learn, and to understand machine learning deeply, you have to understand its mathematics."**
> — 아닐 아난타스와미, 『Why Machines Learn』, Prologue (요지, 직접 번역)
> ※ 정확한 원문 문장을 대조하지 못했으므로, 위 인용은 저자의 서문 취지를 요약한 것으로 직접 인용이 아님을 밝힌다. 확인된 원문 인용은 개별 챕터 분석 시 재확인한다.

---

## 기본 정보

| 항목 | 내용 |
|------|------|
| **원제** | Why Machines Learn: The Elegant Math Behind Modern AI |
| **한국어 제목** | 『기계는 왜 학습하는가』(노승영 옮김, 까치, 2025년 2월 28일 출간) — 국내 정식 번역본 확인됨 |
| **저자** | 아닐 아난타스와미 (Anil Ananthaswamy) |
| **저자의 신분** | 인도 출신의 과학 저널리스트. 뉴사이언티스트(New Scientist)의 前 편집장을 지냈으며, MIT 나이트 과학저널리즘 펠로우십을 수료했다. 전작으로 물리학·우주론을 다룬 『The Edge of Physics』(2010), 자아와 정신질환을 다룬 『The Man Who Wasn't There』(2015), 양자역학을 다룬 『Through Two Doors at Once』(2018)가 있다 |
| **출간 경위** | 2024년 7월 미국에서 Dutton(Penguin Random House)을 통해 하드커버 초판 출간, 2025년 페이퍼백판에 트랜스포머 해설 후기(Afterword) 추가 |
| **분야** | 대중 과학서 — 머신러닝의 수학적 기초를 역사적 서사와 함께 풀어내는 책 |
| **핵심 프레임워크** | 퍼셉트론(perceptron)에서 시작해 선형대수·확률론·최적화(경사하강법)·서포트 벡터 머신·신경망·역전파·합성곱 신경망(CNN)·딥러닝의 이론적 미해결 문제(이중강하, 그로킹)에 이르는 머신러닝 발전사를, 각 단계의 핵심 수학 개념과 그것을 발견한 인물의 이야기로 함께 서술 |
| **분량** | 프롤로그(Prologue)에 이어 전 12개 장(Chapter) + 에필로그(Epilogue) + (페이퍼백판 후기(Afterword): 트랜스포머 아키텍처 해설) |

---

## 책 소개

『Why Machines Learn』은 오늘날 챗GPT 같은 대형언어모델을 가능케 한 머신러닝이 실은 오랜 수학사 위에 서 있다는 것을 보여주는 책이다. 아난타스와미는 "기계는 왜, 어떻게 배우는가"라는 질문에 기술적 설명이 아니라 **역사적 서사**로 답한다 — 각 장은 특정 수학적 발견(예: 확률론, 선형대수, 최적화 이론)과 그것을 만든 과학자·수학자의 인간적 드라마를 함께 풀어내며, 그 발견이 어떻게 현대 AI의 특정 구성 요소로 이어졌는지를 추적한다.

책은 1950\~60년대 프랭크 로젠블랫(Frank Rosenblatt)의 퍼셉트론(perceptron) — 최초의 학습하는 기계 모델 — 에서 출발한다. 이어 신경망을 벡터와 행렬로 표현하는 선형대수("There's Magic in Them Matrices"), 데이터를 최적으로 분리하는 경계를 찾는 확률론과 최적화, 마빈 민스키의 비판으로 신경망 연구가 침체되었다가("The Man Who Set Back Deep Learning (Not Really)") 다시 부활하는 과정, 서포트 벡터 머신의 "커널 트릭(kernel trick)", 물리학의 통계역학에서 영감을 얻은 홉필드 네트워크와 볼츠만 머신("With a Little Help from Physics"), 역전파(backpropagation) 알고리즘이 신경망 학습을 실용적으로 만든 결정적 전환("The Algorithm that Put Paid to a Persistent Myth"), 휴벨과 위즐의 시각피질 연구가 합성곱 신경망(CNN)으로 이어지는 과정("The Eyes of a Machine"), 그리고 이중강하(double descent)·그로킹(grokking)처럼 현재의 딥러닝 이론이 아직 설명하지 못하는 미해결 현상들("Terra Incognita")까지, 머신러닝 발전사의 결정적 순간들을 순차적으로 다룬다.

이 책의 핵심 메시지는, **딥러닝이 "블랙박스 마법"이 아니라 200년에 걸친 수학적 발견의 누적이라는 것**이다. 저자는 복잡한 수식을 완전히 생략하지 않으면서도, 각 개념이 왜 필요했고 어떤 문제를 풀었는지를 이야기 형식으로 풀어내 일반 독자도 접근할 수 있게 한다. 다만 저자는 동시에 마지막 장("Terra Incognita")에서 오늘날 딥러닝의 실제 성능(과매개변수화 모델의 일반화, 이중강하 현상 등)이 여전히 기존 통계 이론으로 완전히 설명되지 않는 "미지의 영역"에 있다는 점도 정직하게 인정한다. 페이퍼백판에 추가된 후기(Afterword)에서는 챗GPT 등 대형언어모델의 기반이 된 트랜스포머(Transformer) 아키텍처를 별도로 다룬다.

### 이 책을 관통하는 핵심 틀

```
머신러닝의 수학적 계보 (역사적 서사 + 수학 개념)

  1장 패턴을 필사적으로 찾아서 — 문제의식: 기계는 어떻게 패턴을 학습하는가
  2장 우리는 모두 숫자일 뿐이다 — 데이터를 벡터로 표현하기
  3장 그릇의 바닥 — 손실 함수와 최적화의 기하학
  4장 확률의 세계에서 — 베이지안 추론과 확률적 사고
  5장 깃털이 같은 새들끼리 — 분류(classification)와 유사성
  6장 행렬 속의 마법 — 선형대수와 신경망의 표현
  7장 위대한 커널 밧줄 마술 — 서포트 벡터 머신과 커널 트릭
  8장 물리학의 도움으로 — 홉필드 네트워크, 볼츠만 머신
  9장 딥러닝을 후퇴시킨 사람 (사실은 아니지만) — 민스키의 퍼셉트론 비판과 그 여파
  10장 끈질긴 신화를 잠재운 알고리즘 — 역전파의 재발견과 신경망의 부활
  11장 기계의 눈 — 휴벨과 위즐의 시각피질 연구, 합성곱 신경망(CNN)
  12장 미지의 땅 — 이중강하·그로킹 등 딥러닝 이론의 미해결 문제
  에필로그 — 인간의 인지·체화된 지능과 AI의 접점에 대한 성찰

  → 관통하는 전제: "딥러닝은 마법이 아니라, 200년에 걸친 수학의 누적이다."
```

---

## 목차 (Table of Contents)

『Why Machines Learn: The Elegant Math Behind Modern AI』(2024년, Dutton 하드커버 초판)는 프롤로그(Prologue)에 이어 **전 12개 장(Chapter)**, 에필로그(Epilogue), 그리고 2025년 페이퍼백판에 추가된 후기(Afterword)로 구성된다.

| 챕터 번호 | 영문 제목 | 한글 제목(의역) | 다루는 핵심 개념 |
|-----------|-----------|-----------|-------------------|
| 프롤로그 | Prologue | 프롤로그 | 문제의식 제시 |
| 1장 | Desperately Seeking Patterns | 패턴을 필사적으로 찾아서 | 학습하는 기계라는 발상, 퍼셉트론 |
| 2장 | We Are All Just Numbers Here | 우리는 모두 숫자일 뿐이다 | 데이터의 벡터 표현 |
| 3장 | The Bottom of the Bowl | 그릇의 바닥 | 손실 함수와 경사하강법 |
| 4장 | In All Probability | 확률의 세계에서 | 확률론과 베이지안 추론 |
| 5장 | Birds of a Feather | 깃털이 같은 새들끼리 | 분류와 유사성 측정 |
| 6장 | There's Magic in Them Matrices | 행렬 속의 마법 | 선형대수와 신경망 |
| 7장 | The Great Kernel Rope Trick | 위대한 커널 밧줄 마술 | 서포트 벡터 머신, 커널 트릭 |
| 8장 | With a Little Help from Physics | 물리학의 도움으로 | 홉필드 네트워크, 볼츠만 머신 |
| 9장 | The Man Who Set Back Deep Learning (Not Really) | 딥러닝을 후퇴시킨 사람 (사실은 아니지만) | 민스키의 퍼셉트론 비판 |
| 10장 | The Algorithm that Put Paid to a Persistent Myth | 끈질긴 신화를 잠재운 알고리즘 | 역전파(backpropagation) |
| 11장 | The Eyes of a Machine | 기계의 눈 | 휴벨·위즐의 시각피질 연구, 합성곱 신경망(CNN) |
| 12장 | Terra Incognita | 미지의 땅 | 과매개변수화, 이중강하(double descent), 그로킹(grokking), 자기지도학습 |
| 에필로그 | Epilogue | 에필로그 | 인간의 인지·체화된 지능과 AI의 접점에 대한 성찰 |
| 페이퍼백 후기 | Afterword | 후기 | 트랜스포머(Transformer) 아키텍처 해설 |

※ 위 표는 Penguin Random House 공식 페이지, 출판사 발췌 PDF, Shortform 요약, 2차 서평 등 복수의 자료를 상호 대조해 정리했다. 11\~12장 및 에필로그의 제목은 원서 목차로 확인했으나, 한글 제목은 국내 정식 번역본(까치, 2025)의 표현을 직접 대조하지 못해 편의상 의역한 것이며, 각 장 내부의 정확한 절 구성·인용문은 원서 또는 국내 번역본 실물로 반드시 재확인한다.

---

## 핵심 주제 요약

### 1. 딥러닝은 마법이 아니라 수학의 누적이다
현대 AI를 특정 천재의 발명이 아니라, 200년에 걸친 확률론·선형대수·최적화 이론의 누적된 발전으로 재구성한다.

### 2. 퍼셉트론에서 트랜스포머까지의 계보
프랭크 로젠블랫의 퍼셉트론이라는 단순한 모델이, 역전파·서포트 벡터 머신·신경망의 부활을 거쳐 오늘날의 트랜스포머 기반 대형언어모델로 이어지는 연속적 발전 경로를 보여준다.

### 3. 침체와 부활의 반복 (AI 겨울)
마빈 민스키의 퍼셉트론 비판으로 신경망 연구가 한동안 침체되었다가 역전파의 재발견으로 부활하는 역사는, 혁신적 기술이 종종 회의론의 시기를 거쳐 발전한다는 패턴을 보여준다.

### 4. 물리학과 머신러닝의 교차
홉필드 네트워크·볼츠만 머신처럼, 통계역학에서 빌려온 개념이 머신러닝의 핵심 도구가 된 사례는 학제간 교차의 힘을 보여준다.

---

## 이 책을 읽어야 하는 이유

1. **AI를 블랙박스가 아니라 이해 가능한 수학으로 보게 한다** — 현대 AI에 대한 막연한 경외감이나 공포 대신, 그 작동 원리를 역사적 맥락에서 이해하게 해준다.
2. **AI 겨울과 부활의 역사가 주는 교훈** — 혁신적 기술도 회의론과 침체기를 거친다는 패턴은, 기술 투자에서 단기 실망과 장기 잠재력을 구분하는 시각을 제공한다.
3. **『마스터 알고리즘』, 『Human Compatible』과 함께 읽으면 AI의 수학적·철학적 토대를 함께 파악**할 수 있다.
4. **과학 저널리스트 특유의 접근성 높은 서술** — 복잡한 수식을 인간 드라마와 결합해, 전문가가 아니어도 핵심 개념을 따라갈 수 있다.
5. **인출기 투자자에게는 "기술의 본질을 이해하고 투자하라"는 원칙의 실천 도구** — 미국 빅테크·반도체에 집중된 포트폴리오를 가진 투자자가, 자신이 투자하는 AI 산업의 기술적 실체를 얼마나 깊이 이해하고 있는지 되묻게 하는 책이다. 유행어로서의 AI가 아니라, 그 수학적 기초를 이해하는 것이 스캐틀버트(피셔의 개념)에 준하는 정성적 검증의 출발점이 될 수 있다.

---

## 참고 자료

- Ananthaswamy, Anil, *Why Machines Learn: The Elegant Math Behind Modern AI*, Dutton (Penguin Random House), 2024 (하드커버 초판); 2025 페이퍼백판(트랜스포머 해설 후기 추가)
- 아닐 아난타스와미, 『기계는 왜 학습하는가』, 노승영 옮김, 까치, 2025년 2월 28일 (국내 정식 번역본)
- [Why Machines Learn – Penguin Random House](https://www.penguinrandomhouse.com/books/677608/why-machines-learn-by-anil-ananthaswamy/)
- [Why Machines Learn – Amazon](https://www.amazon.com/Why-Machines-Learn-Elegant-Behind/dp/0593185749)
- [Why Machines Learn – Goodreads](https://www.goodreads.com/book/show/195888801-why-machines-learn)
- [Why Machines Learn 발췌 PDF – Penguin UK](https://cdn.penguin.co.uk/dam-assets/books/9780241586488/9780241586488-sample.pdf)
- [Why Machines Learn Summary – Shortform](https://www.shortform.com/pdf/why-machines-learn-pdf-anil-ananthaswamy) (11\~12장 요약 확인)
- [기계는 왜 학습하는가 – 교보문고](https://product.kyobobook.co.kr/detail/S000215849977)

※ 이 문서의 목차는 출판사 공식 페이지 및 복수의 2차 자료(Shortform 요약 등)를 상호 대조해 12장 + 에필로그 전체 구성을 확인했다. 다만 11\~12장·에필로그의 한글 제목은 국내 정식 번역본(까치, 2025)과 직접 대조하지 못한 의역이며, 각 장 내부의 절 구성·인용문은 원서 또는 국내 번역본 실물로 반드시 재확인한다.
