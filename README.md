# Hi, I'm Gaurang 👋

**I build fast systems and AI tools — options-pricing engines, GPU compute, and LLM tooling.**

Honours Computer Science + Statistics @ the University of Waterloo · incoming Technical Systems Analyst co-op @ RBC. I like problems where performance and correctness both matter — pricing engines, low-latency streaming, and the infrastructure around them.

🌐 **[gaurangkhurana.ca](https://gaurangkhurana.ca)** &nbsp;·&nbsp; 💼 **[LinkedIn](https://www.linkedin.com/in/gaurang-khurana-567b802a8)** &nbsp;·&nbsp; ✉️ **[g7khuran@uwaterloo.ca](mailto:g7khuran@uwaterloo.ca)**

---

## 🚀 Projects

### [QuantCore](https://github.com/gkhurana21/quantcore) — real-time options pricing & risk engine &nbsp;·&nbsp; [▶ Live Demo](https://quantcore-gk.netlify.app)
C++ Black-Scholes + Monte Carlo core with analytic Greeks and pybind11 bindings. Apple Metal GPU Monte Carlo hits **69× over vectorized NumPy** at 10M paths; pricing validated to **<0.01%** against real market option prices; FastAPI WebSocket streaming at **sub-5ms p99** into a Next.js dashboard; VaR backtested at a **4.5% breach rate over 851 days** of real multi-asset data (caught the April 2025 tariff shock).
<br>`C++` · `Apple Metal GPU` · `pybind11` · `FastAPI` · `Next.js` · `Monte Carlo`

### [BulkPilot](https://github.com/gkhurana21/bulkpilot) — embedded Shopify app
Bulk product-variant price editor with live before/after preview and one-click snapshot rollback. Applies changes via the GraphQL Admin API (`productVariantsBulkUpdate`) chunked to Shopify's 250-variant limit, with Prisma snapshot-based rollback and per-variant partial-failure handling.
<br>`Shopify` · `React Router` · `Polaris` · `App Bridge` · `GraphQL Admin API` · `Prisma`

### [CodeShift](https://github.com/gkhurana21/codeshift) — autonomous Python 2→3 migration agent
LLM agent that migrates *and verifies behavioral correctness*, not just syntax: **95.1% pass rate** on a pre-registered 41-case behavioral-oracle benchmark, byte-identical results across Anthropic and Gemini backends.
<br>`Python` · `parso` · `LangChain` · `Claude` · `Gemini`

### [questrade-risk](https://github.com/gkhurana21/questrade-risk) — read-only brokerage analytics
Live position pricing, Greeks, and VaR off the Questrade API — read-only by design, no order placement.
<br>`Python` · `Questrade API`

---

## 🛠️ Tech stack

**Languages:** C++ · Python · TypeScript / JavaScript · Java · SQL
**Systems:** Apple Metal (GPU compute) · SIMD / NEON · multithreading · pybind11 · low-latency
**Finance / Quant:** Black-Scholes · Monte Carlo · Greeks · Value-at-Risk · backtesting
**Web:** Next.js · React · React Router · Node.js · FastAPI · GraphQL · Shopify (Polaris, App Bridge) · Tailwind
**AI / ML:** LLM APIs (OpenAI, Anthropic, Gemini) · LangChain · RAG · Vector Embeddings · Pandas · NumPy · TensorFlow
**Data & Cloud:** PostgreSQL · SQLite · Neo4j · Pinecone · Redis · AWS · Azure · Docker · Vercel · CI/CD

---

## 📌 Currently

- **Technical Systems Analyst co-op @ RBC** — Toronto
- **Seeking Fall 2026 co-op** in software engineering / quant dev / trading systems / fintech
- Elite & President's Scholarship ($50K) · Group I Distinction, Waterloo Euclid · Bloomberg Market Concepts

---

<sub>Full portfolio, interactive demos, and a playable $1M market sim → <b><a href="https://gaurangkhurana.ca">gaurangkhurana.ca</a></b></sub>
