## Hi, I'm Rafael 👋 — AI Engineer

I build AI systems that are honest about what they don't know. Coming from 5+ years of full-stack and freelance web development, I'm now focused on retrieval-augmented generation and LLM application engineering — specifically the part most RAG projects skip: proving an answer wasn't fabricated.

### 🔦 Featured project

**[Crivo](https://github.com/rafaeelprado/crivo)** — RAG for contract due diligence, with citations verified against the source text.

Answers questions over a corpus of real Brazilian government contracts, citing the exact document, clause and page — and refuses to answer when the answer isn't in the documents. Four layered defenses against hallucination: relevance-threshold abstention, a closed numbered prompt, literal fuzzy-match citation verification, and an auditable source trail in the UI. Result so far: **10/10 correct abstentions** on out-of-domain questions with zero fabricated answers, and **67 tests** with every model call injected/faked, so the suite runs in seconds and spends zero API tokens. Stack: Python, FastAPI, ChromaDB + BM25 hybrid search, BGE-M3 embeddings, the Claude API with structured tool-use output, and Streamlit.

📓 [Technical journal](https://github.com/rafaeelprado/crivo/blob/main/docs/DIARIO_TECNICO.md) — the real bugs found, the trade-offs made, and why.

### 🏫 Also shipped

**[colegio-3d-site](https://github.com/rafaeelprado/colegio-3d-site)** — production site for a real school, live at [colegio3d.com.br](https://colegio3d.com.br). Built end-to-end from spec to deploy: hand-written HTML/CSS/JS with no framework, WCAG contrast verified by calculation rather than guesswork, a real production bug found and fixed with root-cause analysis, an LGPD-compliant privacy policy written from the actual code, and a spam-resistant contact form with no third-party captcha.

### 🧰 Stack

**AI / backend:** Python · FastAPI · ChromaDB · BM25 · Claude API (Anthropic) · RAGAS · Docker

**Full-stack foundation:** JavaScript · TypeScript · React · Next.js · HTML5 · CSS3 · WordPress

### 📫 Reach me

Email: [rafapsd@gmail.com](mailto:rafapsd@gmail.com) · LinkedIn: [linkedin.com/in/rafapsd](https://www.linkedin.com/in/rafapsd/) · Also on [Behance](https://www.behance.net/rafapradev) for design work
