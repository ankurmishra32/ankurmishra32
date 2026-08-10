# Ankur Mishra

Senior Frontend Engineer — 11+ years shipping React, Angular, and
TypeScript at GlobalLogic, Practo, Oracle, and LG.

- Noida, India
- [LinkedIn](https://linkedin.com/in/ankurmishra32)
- [Resume (PDF)](https://github.com/ankurmishra32/ankurmishra32/blob/main/resume.pdf)
- [Email](mailto:ankurmishra32@gmail.com)

---

## What I work on

Frontend architecture, greenfield builds, framework migrations, and
the unglamorous work that makes them land — accessibility, testing
culture, CI, and release coordination under other people's quality
bars (Google, T-Mobile, Amazon).

I think about UI as a system, not a screen. Component libraries that
don't fight you, state management that matches the data shape, and
tests that catch the regressions reviewers actually approve against.

## Selected work

### [talk-to-the-dead-poc](https://github.com/ankurmishra32/talk-to-the-dead-poc)
Next.js + Firebase + local Ollama LLM. Persona chat with streaming
responses, per-user auth scoping, server-side prompt assembly, and
a guided onboarding form. The interesting parts aren't the LLM call
— they're the prompt-injection discipline, the per-user memory
boundary, and the "this is a simulation, not a real person" framing
that lets the product ship responsibly.

`Next.js 16` · `React 19` · `TypeScript` · `Firebase Auth + Firestore` · `Ollama (llama3.2)` · `SSE streaming`

### [NodeReactWithAI](https://github.com/ankurmishra32/NodeReactWithAI)
RAG-style chat over PDF knowledge bases. Local Ollama does both
embedding (nomic-embed-text) and chat (llama3.2); Express serves
top-k cosine-similarity chunks as context. Built end to end —
PDF ingestion, chunking, embedding persistence, retrieval, and a
Vite/React frontend.

`Express` · `Ollama` · `pdfjs-dist` · `Vite` · `React 19` · `dotenv`

### [clockify](https://github.com/ankurmishra32/clockify) · [chart](https://github.com/ankurmishra32/chart) · [todo-list-getir](https://github.com/ankurmishra32/todo-list-getir)
Interview-era CRA projects (React 18 + react-scripts). Each has
real tests, lint clean, and the kind of bug fixes that come from
actually running the code:
- **clockify** — time tracker with project state, started/stopped
  timer logic, and a reproducible `nextId` for stable keys.
- **chart** — D3 line chart with date-range and filter UI.
  Tooltip ref-scoped so multiple charts on one page don't collide.
- **todo-list-getir** — fetch + CRUD against jsonplaceholder, with
  AbortController for unmount safety and a deterministic id
  generator.

## Algorithms & data structure practice

### [DataStructureAndAlgorithmsMadeEasyInJavaScript](https://github.com/ankurmishra32/DataStructureAndAlgorithmsMadeEasyInJavaScript)
Solutions to the Narasimha Karumanchi book in plain JS. Module-scoped
memo tables (Fibonacci, LCS) deliberately kept local to each function
to avoid the "tests pass in isolation, fail in batch" trap.

## Writing

- **Journal:** "Intelligent Phishing Detection System using
  Similarity Matching Algorithms," Int. J. Information and
  Communication Technology, Vol. 12, Nos. 1/2, 2018.
- **Patent:** "Business Card Exchange through Handshake" (LG, 2015).

## Currently

Open to senior frontend roles (Staff / Lead / Principal). Strong
preference for product companies where frontend is on the critical
path, not a downstream consumer of someone else's API.

If you're hiring and your problem is "we need someone to architect
the frontend, raise the bar, and ship under scrutiny" — that's
exactly what I've been doing.

---

<sub>Last updated: 2026.</sub>
