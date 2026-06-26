# 👋 Hi, I'm Rama Krishna

I build small, working AI products — not just tutorial code. Most of what's here ships an actual API or app: a Cloudflare Workers AI backend with a live endpoint, a Streamlit frontend that talks to it, or a local LLM agent you can run in one command.

🔭 Currently focused on: **LLM agents, prompt engineering, and lightweight AI-product architecture (local LLMs via Ollama + serverless inference via Cloudflare Workers AI)**
🌱 Looking for: **AI / ML / GenAI engineering roles**
💬 Ask me about: prompt design, Ollama, Cloudflare Workers AI, Streamlit
📫 Reach me: [LinkedIn](https://www.linkedin.com/in/ramakrishnavullaganti/) · ramakrishnavullaganti@gmail.com

---

## 🚀 Featured projects

### 🏢 [Enterprise AI QA Auditor](https://github.com/ramakrishna2512/ai-agents-hub/tree/main/ai-qa-auditor)
A QA assistant that takes a feature spec or prompt and produces a prompt-quality review, a functional gap analysis, a security review, and a matching set of automated pytest cases — with the test count verified using Python's `ast` module so the LLM can't fudge the number. Deterministic LLM config, JSON-schema-validated output, retry logic, structured logging.
`Python` `Streamlit` `Ollama` `JSON Schema` `AST validation`

### 📧 AI Email Writer — [live demo](https://email-writer.vullagantiramakrishna.workers.dev/) · [frontend](https://github.com/ramakrishna2512/email-writer-cloudflare-frontend) · [backend](https://github.com/ramakrishna2512/email-writer-cloudflare-backend)
Generates tone-aware professional emails. Streamlit UI → Cloudflare Worker → Workers AI (Llama-3-8B). Deployed and callable right now, not just runnable locally.
`Streamlit` `Cloudflare Workers AI` `Llama 3` `Serverless`

### ✍️ AI Prompt Rewriter — [live demo](https://prompt-rewriter-cloudflare.vullagantiramakrishna.workers.dev) · [repo](https://github.com/ramakrishna2512/prompt-rewriter-cloudflare)
Rewrites a rough prompt into a clearer one while preserving intent. Same pattern: Streamlit UI calling a deployed Cloudflare Workers AI endpoint (Mistral-7B).
`Streamlit` `Cloudflare Workers AI` `Mistral 7B`

### 🧠 [AI Agents Suite](https://github.com/ramakrishna2512/ai-agents-hub)
Five small, single-purpose local agents built around Ollama: a prompt evaluator, a prompt rewriter, a task clarifier, a task planner, and the QA auditor above. Each agent does one thing, runs fully offline, and ships with its own README and example output.
`Python` `Ollama` `LLaMA 3` `Mistral`

---

## 🛠️ Stack

**Languages:** Python, JavaScript
**AI/LLM:** Ollama (local inference), Cloudflare Workers AI, prompt engineering, JSON-schema-constrained output
**App layer:** Streamlit
**Infra:** Cloudflare Workers, Wrangler
**Testing:** Vitest, Pytest, AST-based validation

---

