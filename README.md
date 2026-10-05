# Hi, I'm Taniket 👋

Product engineer with 7+ years building React and TypeScript applications and Ruby on Rails APIs, now building LLM applications: agents, retrieval-augmented generation (RAG) and evals.

- 🔭 Most recently a Senior Frontend Engineer at [Apollo.io](https://www.apollo.io), where I shipped AI product features end to end
- 🤖 Currently building AI engineering projects from first principles: agent loops, RAG pipelines and the evals around them
- 📍 Delhi, India · open to AI engineering and product engineering roles

## Featured projects

### 🎭 [Shakespeare RAG](https://github.com/taniket15/shakespeare-rag) · [Live demo](https://shakespeare-rag-taniket.streamlit.app/)
Ask questions about Shakespeare's 38 plays, 4 poem collections and his life. A deployed RAG app that answers only from retrieved passages, with inline citations, follow-up questions and streamed answers.

- **Hybrid retrieval** (FAISS + BM25 + Reciprocal Rank Fusion, plus LLM query expansion) raised top-5 retrieval accuracy from **64% to 100%** on a 33-question eval
- **Layout-aware PDF parsing** removed 17% noise and attributed every speech to its speaker
- **LLM-as-judge answer eval**: completeness 49% → 58%, faithful answers 15/17 → 17/17

`Python` `LangChain` `FAISS` `BM25` `sentence-transformers` `OpenAI API` `PyMuPDF` `Streamlit`

### 🖥️ [Agentic CLI](https://github.com/taniket15/agentic-cli)
A terminal AI agent built in TypeScript with no agent framework: a hand-rolled tool-calling loop with context compaction, human-in-the-loop approval, run budgets, and an eval suite of 21 cases scored by tool-selection precision, recall and an LLM judge.

`TypeScript` `Vercel AI SDK` `OpenAI API` `Zod` `Ink` `Laminar` `Vitest`

### 📝 [React Form Builder](https://github.com/taniket15/react-form-builder)
A Google Forms-style builder with a design mode and a fill mode (submit and export to PDF), built around an extensible field-type registry and a pure, unit-tested engine for conditions and calculations.

`React` `TypeScript` `Vitest`

## Experience

I've spent 7+ years building product frontends, and the work I enjoy most sits where engineering meets product decisions: finding out why users aren't getting value from something, shipping a fix carefully, and measuring whether it worked.

Most recently I was on the AI Apps team at **Apollo.io**, a B2B sales-intelligence platform. My favourite project there started with data: an AI feature was underused because people couldn't find it. Working with product and design, I redesigned it and rolled it out gradually behind feature flags, and conversion went from about 9% to 15–18%. I also designed the frontend foundation for a large platform migration, so the team could ship 30+ components in around three weeks with zero downtime, and picked up Ruby on Rails work on the APIs behind it.

Before that I spent nearly seven years at **Josh Technology Group**, growing from my first developer role to tech lead. Highlights: a multi-tenant white-labeling system that cut customer onboarding from two weeks to 15 minutes, cross-platform banking apps in Flutter, and a Next.js rebuild I led with a small squad. I also cared about the people side, mentoring engineers and helping the engineering org grow from 8 to 65+ developers through hiring and onboarding.

Building AI products at Apollo made me want to understand the model side properly, which is what my recent projects are about.

| When | Role | Proudest of |
| --- | --- | --- |
| 2025–2026 | Senior Frontend Engineer · Apollo.io | AI feature conversion: 9% → 15–18% |
| 2022–2025 | Associate Technical Lead · JTG | Next.js rebuild; helping grow the org to 65+ engineers |
| 2021–2022 | Senior Front End Developer II · JTG | Customer onboarding: 2 weeks → 15 minutes |
| 2019–2021 | Senior Front End Developer I · JTG | Flutter banking apps on iOS, Android and web |
| 2018–2019 | Front End Developer · JTG | Component library for a ground-up rewrite |

The full details are on [LinkedIn](https://www.linkedin.com/in/taniket/).

## Tech stack

- **AI / LLM:** OpenAI API, Vercel AI SDK, LangChain, RAG, hybrid search (FAISS + BM25), embeddings, ChromaDB, tool calling, LLM evals (LLM-as-judge, Laminar)
- **Frontend:** React, TypeScript, Redux, RTK Query, Next.js, Storybook, Tailwind
- **Backend:** Ruby on Rails, Node.js, Python, PostgreSQL
- **Mobile:** Flutter, React Native
- **Testing & tooling:** Jest, Vitest, Cypress, Playwright, GitHub Actions, Claude Code, Cursor

## Connect

[LinkedIn](https://www.linkedin.com/in/taniket/) · [Email](mailto:taniket.mehra@gmail.com)
