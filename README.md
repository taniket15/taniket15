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

### Senior Frontend Engineer · [Apollo.io](https://www.apollo.io) · May 2025 – May 2026
B2B sales-intelligence platform, on the AI Apps team.

- **Owned an AI-discovery feature end to end (v1 to v2).** User-data analysis showed the feature was hard to find; I partnered with product and design on a redesign and shipped it through a phased feature-flag rollout, lifting conversion from a **9% baseline to a 15–18% average** (peaking at 24–26%).
- **Designed the frontend foundation for a platform migration** off a legacy profile system onto a new Content Center API: assets, components and API layers. The team shipped **30+ components in about 3 weeks** against a multi-month baseline, and a maintenance-mode feature flag enabled a **zero-downtime** database migration.
- **Built a reusable Context Selector shared across 3 AI product surfaces**, backward compatible with 2 legacy versions running in parallel; designed a 3-tier permissions model (Viewer, Editor, Admin) and moved data fetching to RTK Query, removing redundant API calls.
- **Expanded into Ruby on Rails backend work**: features, fixes and critical incidents on the Content Center APIs.
- **Fixed how quality was measured:** diagnosed a bug inflating reported E2E test coverage and corrected the metric from 37% to 48.5%.
- **Improved how the team works:** introduced a ship-room visibility cadence the team adopted, wrote frontend architecture documentation, onboarded a new engineer, and shared on-call and experimentation practices.

`React` `TypeScript` `Redux` `RTK Query` `Ruby on Rails` `Feature flags`

### Josh Technology Group (JTG) · Aug 2018 – May 2025
Nearly 7 years, growing from Front End Developer to Associate Technical Lead.

**Associate Technical Lead** · Oct 2022 – May 2025
- **Rebuilt the marketing site on Next.js and headless WordPress**, reusing the legacy CMS dataset through its API, sustaining **95+ Lighthouse scores** and assessed as 10x more scalable than its predecessor.
- **Reduced Redux-related bundle size by 95%** in a core shared repository.
- **Led a squad of 4–5 engineers** on the rebuild at 50% allocation, alongside a flagship product; mentored 6–8 engineers.
- **Helped scale the engineering org from 8 to 65+ developers:** interviewed candidates, defined onboarding and senior-hiring rubrics, and ran the frontend induction program, recruitment drives and the interview-question-bank team.

**Senior Front End Developer II** · Apr 2021 – Sept 2022
- **Designed a multi-tenant white-labeling pipeline** (tenant-specific UI configuration, routing and asset bundling) that isolated tenant failures and **cut customer onboarding from 2 weeks to 15 minutes**, a 99% reduction.
- **Designed the data model and repo structure for a client-configuration module**, later adopted as the coding standard by 2 engineering teams.
- **Cut app load times by 30%** with Web Vitals budgets, and led the team's migration to Jenkins CI/CD.

**Senior Front End Developer I** · Oct 2019 – Mar 2021
- **Designed a cross-platform Flutter architecture** with a shared business-logic layer, delivering core banking and lending modules on iOS, Android and web.
- **Raised user engagement by 40%** through data-driven UX and conversion-funnel work with executive leadership.

**Front End Developer** · Aug 2018 – Sept 2019
- **Built a reusable React and Storybook component library** during a ground-up application rewrite.
- **Reduced production bundle size and load times** through code splitting, API optimization and SEO improvements.

`Next.js` `React` `Redux` `Flutter` `Dart` `Storybook` `Web Vitals` `Jenkins` `Headless WordPress`

### Education
**B.Tech, Information Technology** · Northern India Engineering College, GGSIPU · 2018

## Tech stack

- **AI / LLM:** OpenAI API, Vercel AI SDK, LangChain, RAG, hybrid search (FAISS + BM25), embeddings, ChromaDB, tool calling, LLM evals (LLM-as-judge, Laminar)
- **Frontend:** React, TypeScript, Redux, RTK Query, Next.js, Storybook, Tailwind
- **Backend:** Ruby on Rails, Node.js, Python, PostgreSQL
- **Mobile:** Flutter, React Native
- **Testing & tooling:** Jest, Vitest, Cypress, Playwright, GitHub Actions, Claude Code, Cursor

## Connect

[LinkedIn](https://www.linkedin.com/in/taniket/) · [Email](mailto:taniket.mehra@gmail.com)
