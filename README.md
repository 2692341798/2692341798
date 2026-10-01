## Hi, I'm Qijun Huang 👋

Backend engineer based in Singapore. I build integration services and distributed systems — currently a software engineer intern at **SendOS**, an AI-native business operating system, where I build the Microsoft 365 connector in C#/.NET 8: Continuous Access Evaluation, refresh-failure classification by OAuth error code, egress hardening on Microsoft Graph, and agent writes made idempotent via Graph's `transactionId`.

- 🎓 NUS-ISS Graduate Diploma in Systems Analysis (GPA 4.0/5.0) · B.Eng. Software Engineering, East China University of Technology
- 🔭 Interested in backend platforms, third-party API integration, AI-agent tooling and systems programming
- 📫 huangqj73@gmail.com

### Featured projects

| Project | What it is | Stack |
| --- | --- | --- |
| [InkWords Trainer](https://github.com/2692341798/InkWords) | AI learning platform that turns repos, PDFs and course packs into an Obsidian-style knowledge wiki, quizzes you on it, and builds courses from codebases via AST analysis. Multi-stage LLM quality pipeline (draft → score → repair → revise), DeepSeek cache-aware token tracking, 6 Go services on RabbitMQ + SSE | Go · Gin · PostgreSQL · Redis · RabbitMQ · React · DeepSeek |
| [Load-Balanced Online Judge](https://github.com/2692341798/load-balanced-online-oj) | Distributed OJ with heartbeat health checks that take failed compile nodes offline and re-admit them, per-test-case failover, C++/Python/Java judging and DeepSeek error explanations; sandbox with RLIMIT_NPROC, privilege drop and wait4 memory-limit detection | C++ · Linux · DeepSeek |

### Tech

- **Languages:** C# · Go · C++ · TypeScript · Python · SQL
- **Integrations & identity:** Microsoft Graph (CAE, `transactionId`, Retry-After) · Entra ID · OAuth token lifecycle · MCP
- **LLM systems:** DeepSeek API (context caching, token accounting) · multi-stage generation pipelines · Go/TypeScript AST analysis
- **Systems:** RabbitMQ task queues · SSE streaming · Nginx gateway routing · Linux process sandboxing (setrlimit, privilege drop)
