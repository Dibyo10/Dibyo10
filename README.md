# Dibyo Chakraborty

> Systems • Machine Learning • Backend  
> First-principles engineering. Real systems. Minimal abstractions.

---

## 👋 About Me

I’m **Dibyo**, a Computer Science undergrad focused on understanding **how systems behave under real constraints** — time, scale, failure, and correctness.

I’m most interested in problems where:
- trade-offs actually matter
- systems must remain debuggable over time
- correctness is more important than speed of iteration

My work sits at the intersection of:
- machine learning (classical + modern)
- backend and concurrent systems
- LLM pipelines built with guardrails, not guesswork

I treat AI tools as accelerators — not decision-makers.

---

## 🧠 Areas of Strength

### Backend & Systems
- Implemented **rate limiting algorithms** (Token Bucket, Leaky Bucket, Sliding Window) from scratch in Go
- Built **concurrency-safe systems** using goroutines, mutexes, and worker pools
- Designed time-based algorithms with lazy evaluation and clear invariants
- REST APIs with strict validation, authentication, middleware, and clean routing
- Practical understanding of failure modes, load behavior, and observability

### Machine Learning (Classical + Foundations)
- Linear algebra: eigenvalues/eigenvectors, SVD, PCA, Rayleigh quotient
- Optimization: Gradient Descent, SGD, Momentum, Adam
- Probabilistic models: Gaussian Mixture Models, Bayesian scoring
- Recommender systems:
  - content-based filtering
  - collaborative filtering
  - matrix factorization
  - time-decay and trend-aware ranking
- Dimensionality reduction:
  - PCA (theory + implementation)
  - t-SNE vs UMAP (trade-offs and scaling behavior)

### Sequence Models & Deep Learning
- Vanilla RNNs and **Backpropagation Through Time** from first principles
- Clear understanding of vanishing/exploding gradients
- Orthogonal initialization: benefits and limits
- Able to map math directly to PyTorch implementations

### LLM Systems & Applied AI
- RAG pipelines with retrieval, reranking, and context control
- SQL generation with schema validation and repair loops
- Deterministic compute pipelines (LLM → code → sandbox → verified output)
- Async summarization and memory compaction for long-running chats
- Reasoning about token budgets, latency, and cost at system level

---

## 🛠️ Tools & Stack

**Languages**
- Go, Python, TypeScript, Java

**Backend**
- net/http, FastAPI, Spring Boot
- PostgreSQL, MongoDB
- Docker, Cloud Run

**ML / AI**
- PyTorch
- Vector embeddings & search
- Transformer-based models
- Agent-style workflows (LangGraph-like)

---

## 🚀 Selected Work

### Rate Limiting Systems (Go)
- Implemented Token Bucket, Leaky Bucket, Sliding Window Log & Counter
- Focus on concurrency safety, lazy time computation, and load behavior
- Stress-tested and documented trade-offs (fairness, precision, latency)

### Autonomous API Feature Integrator
- Fetches API docs → extracts schemas → generates code and tests
- Executes, detects failures, and applies self-healing patches
- Outputs a usable SDK / feature module

### LLM Chat Backend
- Token-aware async summarization
- Persistent memory with recovery after restart
- Strict separation of prompts, tools, and execution paths
- Designed for long-running conversations

*(Everything listed here is something I can reason about line-by-line.)*

---

## 📊 Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Dibyo10&show_icons=true&theme=tokyonight&hide_border=true" height="150"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dibyo10&theme=tokyonight&hide_border=true" height="150"/>
</p>

---

📫 **Links**  
- GitHub: https://github.com/Dibyo10  
- LinkedIn: https://www.linkedin.com/in/dibyo-chakraborty-2a7309317/
