# Hi, I'm Taniket 👋

Product engineer with 7+ years building React and TypeScript applications and Ruby on Rails APIs, now building LLM applications: agents, retrieval-augmented generation (RAG) and evals.

- 🔭 Most recently a Senior Frontend Engineer on an AI products team, shipping AI features end to end
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

7+ years building product frontends and APIs for B2B SaaS, AI products and fintech, in senior engineer and tech lead roles. Some of the problems I've worked on:

**🔍 An AI feature users couldn't find.** Usage data showed people weren't discovering it. I redesigned it with product and design, then shipped it gradually behind feature flags so each step could be measured. Conversion went from **9% to 15–18%**.
<sub>React · TypeScript · feature flags · experimentation</sub>

**🏗️ Migrating a product off a legacy system without downtime.** I designed the frontend foundation (component, asset and API layers) so the team could build on it in parallel, and added a maintenance-mode flag for the database cutover. **30+ components shipped in about 3 weeks** instead of months, with **zero downtime**.
<sub>React · Redux · RTK Query · Ruby on Rails</sub>

**🧩 One component, three AI surfaces, two legacy versions.** I built a shared context selector that stayed backward compatible with older versions running in parallel, with a 3-tier permissions model, and moved data fetching to RTK Query to remove redundant API calls.
<sub>React · TypeScript · RTK Query</sub>

**🏷️ Onboarding white-label customers took two weeks.** I designed a multi-tenant pipeline with per-tenant UI configuration, routing and asset bundling, where one tenant's failure can't affect the others. Onboarding dropped to **15 minutes**.
<sub>React · multi-tenant architecture</sub>

**⚡ Slow apps and heavy bundles.** Web Vitals budgets cut load times by **30%**; I cut the Redux-related bundle size of a core shared repository by **95%**; and a Next.js + headless CMS rebuild kept **95+ Lighthouse** scores while reusing the existing content through its API.
<sub>Next.js · React · Redux · Web Vitals · headless WordPress</sub>

**📱 Banking on three platforms with one codebase.** I designed a Flutter architecture with a shared business-logic layer, delivering banking and lending modules on iOS, Android and web.
<sub>Flutter · Dart</sub>

**📏 A coverage metric that was wrong.** I traced a bug in how end-to-end test coverage was reported and corrected the figure from **37% to 48.5%**.
<sub>E2E testing · CI</sub>

**👥 Growing a team, not just code.** As a tech lead I led a squad of 4–5 engineers, mentored 6–8, and helped an engineering org grow from **8 to 65+ developers** by defining hiring rubrics, interviewing, and running frontend onboarding.

More detail on [LinkedIn](https://www.linkedin.com/in/taniket/).

## Tech stack

- **AI / LLM:** OpenAI API, Vercel AI SDK, LangChain, RAG, hybrid search (FAISS + BM25), embeddings, ChromaDB, tool calling, LLM evals (LLM-as-judge, Laminar)
- **Frontend:** React, TypeScript, Redux, RTK Query, Next.js, Storybook, Tailwind
- **Backend:** Ruby on Rails, Node.js, Python, PostgreSQL
- **Mobile:** Flutter, React Native
- **Testing & tooling:** Jest, Vitest, Cypress, Playwright, GitHub Actions, Claude Code, Cursor

## Connect

[LinkedIn](https://www.linkedin.com/in/taniket/) · [Email](mailto:taniket.mehra@gmail.com)
