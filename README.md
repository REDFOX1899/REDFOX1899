## Shantanu Patil

I build AI-native developer tools — systems where language models aren't bolted on as features but are the core architecture. I'm drawn to the hard problems: making LLM outputs reliable, building safety mechanisms that don't slow developers down, and designing interfaces that make complex AI behavior transparent and controllable.

**M.S. UMass Amherst | B.Tech IIT Dhanbad** | Austin, TX

---

### What I'm building

**[BetterCodeWiki](https://github.com/REDFOX1899/BetterCodeWiki)** — Generates interactive wikis from any GitHub/GitLab/Bitbucket repository using a multi-model RAG pipeline (Claude, GPT, Gemini, Ollama). The system analyzes codebases, creates vector embeddings, generates structured documentation with Mermaid diagrams, and serves it through an interactive UI with a 3D Three.js landing page. Includes a visual dependency graph, global search, reading mode, and export to 5 formats. Next.js 15, React 19, FastAPI, WebSocket streaming.

**[GitUnderstand](https://github.com/REDFOX1899/gitunderstand)** — Converts repositories into LLM-friendly text digests and interactive architecture diagrams. Claude analyzes the codebase and generates clickable Mermaid diagrams where nodes link back to source files. Three-service architecture: Next.js frontend, FastAPI ingestion API, and a diagram generation backend with PostgreSQL caching. Live at [gitunderstand.com](https://gitunderstand.com).

**[ShellPilot](https://github.com/REDFOX1899/vigilant-sanderson)** — Natural language shell command executor written in Go. The core design question: how do you give an LLM the ability to execute shell commands without creating a footgun? My answer: 55+ danger detection patterns with tiered risk assessment (low/medium/high/critical), mandatory human-in-the-loop approval for destructive operations, and context-aware generation that inspects git state, file references, and command history before suggesting anything. Supports Claude, GPT-4o, Gemini, and Ollama.

**[Content Scraper](https://github.com/REDFOX1899/content-scraper)** — Multi-source content intelligence platform. Collects from Twitter, YouTube, blogs, podcasts, and books with AI-powered authenticity scoring (0-100), vector embeddings for semantic search, and pluggable storage backends (PostgreSQL, Pinecone, ChromaDB, Weaviate).

---

### What I think about

**Safety as a design constraint, not a feature.** ShellPilot exists because I wanted to explore what it looks like when safety isn't a checkbox but the central architecture decision. Danger detection patterns, risk tiers, approval flows — these aren't guardrails added after the fact; they're the product itself. I think the most interesting unsolved problem in AI tooling is making models powerful without making them dangerous, and I want to work on that.

**Making AI systems legible.** BetterCodeWiki and GitUnderstand both come from the same intuition: AI should help developers build genuine understanding of their codebases, not replace that understanding with opaque summaries. The diagrams link to source. The documentation is structured so you can verify it. The goal is augmented comprehension, not abstracted-away complexity.

**End-to-end ownership.** I design the system architecture, write the frontend and backend, wire up the LLM pipelines, containerize it (Docker, Terraform), and deploy it. Each project above went from an idea I was curious about to something running in production.

---

### Technical range

**Languages:** Go, TypeScript, Python, C++
**AI/ML:** Multi-model orchestration (Claude, GPT, Gemini, Ollama), RAG pipelines, vector embeddings (OpenAI, Google AI, Ollama), prompt engineering, AI safety patterns, streaming inference
**Frontend:** React 19, Next.js 15, Three.js, Framer Motion, Tailwind CSS
**Backend:** FastAPI, WebSocket streaming, PostgreSQL, vector databases (Pinecone, ChromaDB, Weaviate)
**Infrastructure:** Docker, Terraform, AWS, GCP, CI/CD pipelines

---

[shantanupatil1899@gmail.com](mailto:shantanupatil1899@gmail.com) | [LinkedIn](https://www.linkedin.com/in/patil-shantanu/)
