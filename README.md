## Hi, I'm Qijun Huang

I build backend systems and AI workflows with explicit constraints, verifiable results, and useful failure handling. Based in Singapore; currently a **Software Engineer Intern at SendOS**.

[LinkedIn](https://www.linkedin.com/in/qijun-huang/) · [Email](mailto:huangqj73@gmail.com)

### Industry experience

**SendOS — backend and AI-agent engineering**

- Develop C#/.NET integration services, including Microsoft 365 OAuth token lifecycle, Continuous Access Evaluation, and API failure handling.
- Work on agent-execution verification against persisted results, supported by repeatable integration checks.
- Improve correlation across services and asynchronous processing so an operation can be followed through failures and handoffs.

### Selected engineering work

**[FoodMind cooking planner](https://github.com/foodmind-team/foodmind-intelligence) — constrained planning with an independent verifier**

Owned the cooking-planner feature across the agent, Spring Boot backend, web and Android clients, and AWS staging delivery.

- Turn 1–6 recipes into a coordinated timeline with LangGraph and OR-Tools CP-SAT. Keep LLM interpretation separate from deterministic scheduling and safety checks.
- Optimize completion time, dish holding time, and a task-switching proxy in priority order; retain earlier feasible results when later optimization cannot finish.
- Verify schedules independently of the solver using task dependencies, timing checks, and sweep-line resource-capacity checks. Distinguish a timeout from proven infeasibility, with bounded repair and confirmation paths.

**[InkWords](https://github.com/2692341798/InkWords) — evidence-backed learning content**

Built a Go-based platform that turns repositories and documents into knowledge pages, quizzes, and courses.

- Validate chapter claims against evidence IDs and require code blocks to match source evidence or lab artifacts. Hard quality-gate failures block chapter assembly.
- Use staged drafting, review and targeted repair; run long generation and export tasks through RabbitMQ with SSE progress.
- Track token usage and cache hits, and bound model concurrency to make generation costs and failures observable.

**[C++ message broker](https://github.com/2692341798/Message_Queue) — messaging internals**

Implemented direct, fanout and topic routing, acknowledgement tracking, and durable message storage with Muduo, Protobuf and SQLite. Queue data uses length-prefixed records, invalidation and compaction; topic wildcard matching uses dynamic programming.

**[ECUT Computer Association OnlineJudge](https://github.com/DL-Association-for-Computing-Machinery/OnlineJudge) — worker coordination and isolation**

Developing PostgreSQL-backed submissions, idempotent receipts and task leases, with mTLS worker authentication, lease-scoped material access and integrity checks. GNU++17 sandbox experiments and handover/failure-path integration tests support the design.

Status: M0 technical experiments; the complete training product and overall M0 acceptance remain in progress. Not a production deployment.

### Open-source and team contributions

- **[Nango Elasticsearch integration — PR #7759](https://github.com/NangoHQ/nango/pull/7759):** proposed API-key authentication and deployment-specific endpoints. Use the authentication endpoint so index-scoped keys can connect without cluster-monitor privileges. Added setup documentation and validation cases. **PR open; not yet merged.**
- **[Wellness AI — merged RAG contribution](https://github.com/Terrence129/wellness-app-ai/pull/5):** added SQLite FTS5/BM25 retrieval with content-fingerprint index reuse, rebuild-and-replace indexing, bounded document loading and retrieval failure isolation.
- **[Earlier load-balanced OJ](https://github.com/2692341798/load-balanced-online-oj):** extended a course project with compile-node health checks and failover, multi-language judging, and Linux resource limits and privilege reduction.

### Background

NUS-ISS Graduate Diploma in Systems Analysis · B.Eng. Software Engineering, East China University of Technology

C#/.NET · Go · Python · C++ · SQL · PostgreSQL · Redis · RabbitMQ · Docker · GitHub Actions
