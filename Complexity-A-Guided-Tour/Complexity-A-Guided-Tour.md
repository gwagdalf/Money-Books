# 복잡성 (Complexity: A Guided Tour)

※ book-list.csv 225번 항목의 한글 제목("복잡성 (Complexity)")과 저자("멜라니 미첼 / Melanie Mitchell")는 정확하다. 다만 137번 항목("복잡성 / Complexity", 미첼 월드롭 / M. Mitchell Waldrop 저 — *Complexity: The Emerging Science at the Edge of Order and Chaos*, 1992)과 영문 제목이 동일해 혼동될 수 있으므로, 이 저장소에서는 폴더명·파일명을 부제를 살린 `Complexity-A-Guided-Tour`로 구분해 표기한다. 두 책은 저자도 다르고 내용도 다른 별개의 책이다.

---

## 기본 정보

| 항목 | 내용 |
|------|------|
| **원제** | Complexity: A Guided Tour |
| **한국어 제목** | 이 저장소 기준 임시 번역 "복잡성: 안내된 여행" — 국내 정식 번역본 존재 여부를 확인하지 못했으므로 직접 번역임을 밝힌다 |
| **저자** | 멜라니 미첼 (Melanie Mitchell) |
| **저자의 신분** | 포틀랜드 주립대학교(Portland State University) 컴퓨터과학 교수이자 산타페 연구소(Santa Fe Institute) 외부교수(External Professor). 1990년 미시간 대학교에서 더글러스 호프스태터(Douglas Hofstadter)와 존 홀런드(John Holland)의 지도로 박사학위를 받았으며, 유추(analogy-making)를 수행하는 인지 아키텍처 "카피캣(Copycat)"의 개발자로 알려져 있다 |
| **출간 경위** | 2009년 미국 Oxford University Press에서 초판(하드커버) 출간, 2011년 페이퍼백 출간(ISBN 9780199798100). 2010년 Phi Beta Kappa Science Book Award 수상 |
| **분야** | 대중 과학 교양서 — 복잡계 과학(complex systems science) 입문 |
| **구성** | 5부(Part) 19장(Chapter) 구성, 약 350\~370쪽 |

---

## 책 소개

『Complexity: A Guided Tour』는 저자 멜라니 미첼이 자신의 오랜 연구 이력 — 호프스태터 문하에서의 유추적 사고 연구, 존 홀런드 문하에서의 유전 알고리즘 연구, 산타페 연구소에서의 복잡계 과학 연구 — 을 바탕으로 "복잡성(complexity)이란 무엇인가"라는 질문에 답하려는 책이다. 이 책의 독특한 점은 결론에서부터 솔직하게 드러나는데, 미첼은 "복잡계 과학"이 아직 물리학처럼 통일된 이론 체계를 갖춘 단일 학문이 아니라, 서로 다른 분야(생물학·컴퓨터과학·물리학·사회과학)에서 개별적으로 발전해 온 개념과 도구들의 느슨한 집합에 가깝다는 점을 인정하고 출발한다.

책은 5부로 구성된다. 1부(배경과 역사)는 카오스 이론·정보 이론(섀넌)·계산 이론(튜링)·진화·유전학의 기초를 훑은 뒤, "복잡성을 어떻게 정의하고 측정할 것인가"라는 문제 자체를 다룬다 — 여기서 미첼은 알고리즘적 복잡성(Kolmogorov complexity), 논리적 깊이(logical depth), 통계적 복잡성 등 서로 경쟁하는 여러 척도를 소개하며, 단일한 정답이 없다는 점을 분명히 한다. 2부(컴퓨터 속의 생명과 진화)는 자기복제 프로그램과 유전 알고리즘을 다룬다. 3부(계산의 확장)는 존 폰 노이만과 스티븐 울프럼의 세포자동자(cellular automata), 콘웨이의 '생명 게임(Game of Life)', 살아있는 시스템의 정보 처리, 유추 능력(저자 자신의 카피캣 연구와 직접 연결)을 다룬다. 4부(네트워크적 사고)는 와츠·스트로가츠의 좁은 세상 네트워크(small-world network)와 바라바시의 척도 없는 네트워크(scale-free network) 등 21세기 네트워크 과학의 핵심 발견을 소개한다. 5부(결론)에서는 복잡계 과학이 하나의 통일된 학문으로 성숙할 수 있을지에 대한 저자 자신의 신중하고 균형 잡힌 전망으로 책을 마무리한다.

---

## 목차 (Table of Contents)

※ 아래 목차는 Library of Congress 서지 정보(catdir.loc.gov)와 Internet Archive 소장본(archive.org/details/complexityguided0000mitc) 두 독립 출처를 상호 대조하여 확인한 것이다. 각 장의 정확한 절 구성·인용문은 원서 실물로 재확인이 필요하다.

| Part | 챕터 번호 | 영문 제목 |
|------|-----------|-----------|
| I. Background and History | 1 | What Is Complexity? |
| I. Background and History | 2 | Dynamics, Chaos, and Prediction |
| I. Background and History | 3 | Information |
| I. Background and History | 4 | Computation |
| I. Background and History | 5 | Evolution |
| I. Background and History | 6 | Genetics, Simplified |
| I. Background and History | 7 | Defining and Measuring Complexity |
| II. Life and Evolution in Computers | 8 | Self-Reproducing Computer Programs |
| II. Life and Evolution in Computers | 9 | Genetic Algorithms |
| III. Computation Writ Large | 10 | Cellular Automata, Life, and the Universe |
| III. Computation Writ Large | 11 | Computing with Particles |
| III. Computation Writ Large | 12 | Information Processing in Living Systems |
| III. Computation Writ Large | 13 | How to Make Analogies (If You Are a Computer) |
| III. Computation Writ Large | 14 | Prospects of Computer Modeling |
| IV. Network Thinking | 15 | The Science of Networks |
| IV. Network Thinking | 16 | Applying Network Science to Real-World Networks |
| IV. Network Thinking | 17 | The Mystery of Scaling |
| IV. Network Thinking | 18 | Evolution, Complexified |
| V. Conclusion | 19 | The Past and Future of the Sciences of Complexity |

---

## 핵심 주제 요약

### 1. 복잡성의 정의를 둘러싼 논쟁
"복잡성이란 무엇인가"에 대해 학계에 합의된 단일 정의가 없다는 사실 자체를 정면으로 다룬다. 알고리즘적 복잡성·논리적 깊이·통계적 복잡성 등 서로 다른 척도들이 각기 다른 측면을 포착할 뿐, 어느 것도 완전한 답이 아니다.

### 2. 단순한 국소적 규칙에서 창발하는 전역적 패턴
세포자동자·유전 알고리즘·생명 게임 등을 통해, 매우 단순한 국소적(local) 상호작용 규칙만으로도 예측하기 어려운 복잡하고 조직화된 전역적(global) 패턴이 창발(emergence)할 수 있음을 보여준다.

### 3. 정보와 계산이라는 공통 언어
섀넌의 정보 이론과 튜링의 계산 이론을 복잡계를 이해하는 공통의 수학적 언어로 제시하며, 생물학적 시스템(유전자·세포·면역계·개미 군집)의 정보 처리 방식을 계산의 관점에서 재해석한다.

### 4. 네트워크 과학 — 좁은 세상과 척도 없는 네트워크
와츠·스트로가츠의 좁은 세상(small-world) 네트워크와 바라바시의 척도 없는(scale-free) 네트워크 이론을 통해, 소수의 고연결 허브(hub)에 집중된 네트워크 구조가 어떻게 견고함과 취약함을 동시에 만들어내는지 설명한다.

### 5. 통일된 이론에 대한 신중한 회의
저자는 결론부에서 "복잡계 과학"이 물리학의 통일장 이론과 같은 단일한 수학적 틀을 아직 갖추지 못했다는 점을 솔직하게 인정하며, 성급한 통합 서사보다 각 도구의 한계를 정직하게 직시할 것을 권한다.

---

## 이 책을 읽어야 하는 이유

1. **카오스·엔트로피·스케일과 이어지는 STEM 시리즈의 방법론적 뿌리** — 제임스 글릭의 『카오스』, 제레미 리프킨의 『엔트로피』, 제프리 웨스트의 『Scale』이 다룬 개별 현상들이 어떤 공통의 과학적 도구(정보·계산·네트워크)에서 파생되었는지 이 책이 그 뿌리를 정리해 준다.
2. **환원주의적 인과 서사에 대한 경계** — 시장의 등락을 "하나의 명확한 원인"으로 설명하려는 유혹은, 이 책이 반복해서 경고하는 "국소적 규칙에서 창발하는 전역적 패턴을 단일 원인으로 오독하는 오류"와 정확히 같은 구조를 갖는다.
3. **네트워크 집중도에 대한 정량적 사고 도구** — 척도 없는 네트워크의 허브 집중 이론은, 한국·미국 빅테크·반도체라는 소수 허브에 자산이 집중된 포트폴리오 구조를 "얼마나 견고하고 얼마나 취약한가"라는 질문으로 재조명하게 한다.
4. **통일된 정답에 대한 회의 — 인출기 의사결정에 주는 겸손** — 저자가 "복잡성의 단일한 정의는 없다"고 정직하게 인정하듯, 시장을 완벽하게 예측하는 단일 모델도 없다는 지적 겸손을 투자 판단에 적용할 수 있다.

---

## 참고 자료

- Mitchell, Melanie, *Complexity: A Guided Tour*, Oxford University Press, 2009 (hardcover); 2011 (paperback, ISBN 9780199798100)
- [Complexity: A Guided Tour – Table of Contents, Library of Congress](https://catdir.loc.gov/catdir/toc/ecip0819/2008023794.html)
- [Complexity: A Guided Tour – Internet Archive](https://archive.org/details/complexityguided0000mitc)
- [Complexity: A Guided Tour – Oxford University Press (paperback)](https://global.oup.com/academic/product/complexity-9780199798100)
- [Complexity: A Guided Tour – Oxford University Press (hardcover)](https://global.oup.com/academic/product/complexity-9780195124415)
- [Complexity: A Guided Tour – Goodreads](https://www.goodreads.com/book/show/5597902-complexity)
- [Complexity: A Guided Tour – Amazon](https://www.amazon.com/Complexity-Guided-Tour-Melanie-Mitchell/dp/0199798109)

※ 이 문서의 목차는 두 독립 출처(LOC 서지정보, Internet Archive 소장본)를 상호 대조해 확인했으나, 각 장 내부의 절 구성과 인용문은 원서 실물로 재확인이 필요하다는 한계를 밝힌다.
