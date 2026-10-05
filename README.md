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

## Tech stack

- **AI / LLM:** OpenAI API, Vercel AI SDK, LangChain, RAG, hybrid search (FAISS + BM25), embeddings, ChromaDB, tool calling, LLM evals (LLM-as-judge, Laminar)
- **Frontend:** React, TypeScript, Redux, RTK Query, Next.js, Storybook, Tailwind
- **Backend:** Ruby on Rails, Node.js, Python, PostgreSQL
- **Mobile:** Flutter, React Native
- **Testing & tooling:** Jest, Vitest, Cypress, Playwright, GitHub Actions, Claude Code, Cursor

## Connect

[LinkedIn](https://www.linkedin.com/in/taniket/) · [Email](mailto:taniket.mehra@gmail.com)
