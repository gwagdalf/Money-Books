# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This is **not a software project** — there is no build, lint, or test tooling. It is a personal reading-notes repository (in Korean) where the owner works through retirement/money-philosophy books chapter by chapter, always analyzed through the lens of one specific financial profile:

- Born 1976, retired in 2026 at age 50, net worth "000억원" (redacted placeholder, kept literally as `000억원` in every file).
- Portfolio split into two buckets: one for high returns, one for capital preservation.
- Withdraws 2–3%/year of total assets (capped at 1/3 of last year's gains).
- Keeps 6 months of living expenses in cash/safe assets.
- Gradually diversifying away from concentrated Korea/US-tech and semiconductor exposure.
- Views money as a means, not an end — health, family, learning, experience, and social contribution take priority.

Every chapter analysis file re-derives its conclusions by connecting the book's content back to this specific profile, not generic book-report content. When writing or editing any chapter file, preserve this framing.

## Repository structure

Each book gets its own top-level directory, following the same pattern:

```
<Book-Name>/
  README.md          # index: chapter table (English/Korean titles, keywords), links to chapter files
  Template.md / Template2.md   # the prompt/output-spec used to generate each chapter file
  chapterNN-<English-Chapter-Title-With-Hyphens>.md   # one file per chapter
```

- **Same-as-Ever/** — Morgan Housel, *Same as Ever*. Template: `Template2.md`. 23 chapters, grouped into 5 parts in the README (Uncertainty & Risk / Time & Compounding / Limits of Ideas & Strategy / Human Nature & Psychology / Systems & Balance). Each chapter file is long-form (~4,000–5,000 Korean characters) and uses a **9-section** template: 핵심 메시지 → 인상적인 문장(최대 5개) → 주요 개념 정리 → 상세 설명(5개 하위 항목: 논증의 흐름/사례의 맥락/변하지 않는 인간 본성/뉘앙스와 한계/투자 자산관리 연결) → 더 생각해볼 질문 → 나에게 적용하기 → 실행 원칙 → 한 문장으로 정리. Chapter files also often end with an `## ETC` vocabulary glossary for English terms.
- **The-Psychology-of-Money/** — Morgan Housel, *The Psychology of Money*. Template: `Template.md`. 20 chapters, shorter format (~2,000–3,000 characters), **7-section** structure (no "상세 설명" deep-dive section): 핵심 메시지 → 인상적인 문장(최대 3개) → 주요 개념 정리 → 더 생각해볼 질문 → 나에게 적용하기 → 실행 원칙 → 한 문장으로 정리. `chapter02-Luck-and-Risk.md` predates the "더 생각해볼 질문" section being added to the template, so it intentionally has only 6 sections — don't "fix" it to match unless asked. `My-Application--Psychology-of-Money.md` is a separate cross-chapter synthesis scoring all 20 chapters against the owner's real financial situation. The `chatGpt/`, `gemini/`, `grok/`, `qwen/`, `claude/` subdirectories hold parallel takes on this same book produced by other AI assistants for comparison — treat them as reference material, not something to keep in sync with the main chapter files.
- **The-Art-of-Spending-Money/** — Morgan Housel, *The Art of Spending Money* (2025). Only has a single overview file (`The-Art-of-Spending-Money.md`) with a full 21-chapter summary; per-chapter deep-dive files, a `Template.md`, and a `README.md` haven't been created yet for this book.
- **retirement-finance/** — Not a book; a set of parallel "recommend books for my retirement situation" answers from different AI models (`chatGPT.md`, `claude.md`, `gemini.md`, `grok.md`, `qwen.md`), plus `retirement-finance.md` (a 20-book curated reading roadmap with staged phases). **Important:** `retirement-finance/claude.md` is one of these comparison outputs (a book list), not a Claude Code instructions file — don't confuse it with this root `CLAUDE.md`.

## Workflow: adding or editing a chapter analysis

1. Identify the book directory and open its `Template.md` (or `Template2.md` for *Same as Ever*) — it is the authoritative prompt/spec for section structure, tone, and target length for that book.
2. Name new files `chapterNN-<English-Chapter-Title-With-Hyphens>.md`, matching the exact chapter title casing/hyphenation already used in that directory's other chapter files and its README table.
3. Write in Korean, keep original English quotes verbatim when quoting the book, and always tie the analysis back to the owner's financial profile (see above), especially in the 나에게 적용하기 / 실행 원칙 sections.
4. After adding or renaming a chapter file, update that book's `README.md` chapter table/index to keep links and titles in sync.
5. Match the existing section count/order for that book — don't add Same-as-Ever's "상세 설명" deep-dive section to Psychology-of-Money chapters or vice versa.

## Asset Processing Rules
Identify asset information by reading the CURRENCY=WON and TOTAL_ASSET, NET_ASSET, and STOCK_ASSET variables from the @.env file.
When writing the answer, use the TOTAL_ASSET, NET_ASSET, and STOCK_ASSET variables, but when writing in markdown format, display the asset information as 000 billion won so that it is not exposed.
CURRENCY=WON
TOTAL_ASSET=000000000
NET_ASSET=000000000
STOCK_ASSET=000000000