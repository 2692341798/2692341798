## Hi, I'm Qijun Huang 👋

Backend engineer based in Singapore, working on AI-agent integrations and distributed systems. I'm a software engineer intern at **SendOS**, where my work spans C#/.NET integration services, OAuth reliability, execution-result verification, and cross-service observability.

- 🎓 NUS-ISS Graduate Diploma in Systems Analysis (GPA 3.56/5.0) · B.Eng. Software Engineering, East China University of Technology
- 🔭 Currently building **OnlineJudge for the ECUT Computer Association (东华理工大学计算机协会)**
- 📫 [LinkedIn](https://www.linkedin.com/in/qijun-huang/) · huangqj73@gmail.com

### Current work

**SendOS — backend and AI-agent engineering**

- Develop Microsoft 365 integration in C#/.NET 8, with attention to OAuth token lifecycle, Continuous Access Evaluation, API failure handling, and safe retry behavior.
- Work on verifying agent execution outcomes against persisted results, supported by repeatable integration checks.
- Improve request and operation correlation across services and asynchronous processing so failures can be traced through the system.

**[ECUT Computer Association OnlineJudge](https://github.com/DL-Association-for-Computing-Machinery/OnlineJudge) — developer and maintainer**

Building the technical foundation for a programming practice and campus contest platform:

- PostgreSQL-backed submission persistence, idempotent receipts, and task leases.
- Worker authentication with mTLS, lease-scoped material access, integrity checks, and GNU++17 sandbox experiments.
- Integration tests for worker handover and failure paths; separate Redis/PostgreSQL session-revocation experiments.
- Reproducible Docker tooling and CI checks for static analysis, race detection, secret scanning, and dependency vulnerabilities.

**Status:** M0 technical experiments. Formal login, the complete training product, and overall M0 acceptance are still in progress; this is not a production deployment.

### Other projects

| Project | Focus | Stack |
| --- | --- | --- |
| [InkWords Trainer](https://github.com/2692341798/InkWords) | Learning platform that turns repositories and documents into a knowledge wiki, quizzes, and courses, with multi-stage LLM generation and review | Go · PostgreSQL · Redis · RabbitMQ · React · DeepSeek |
| [Load-Balanced Online Judge](https://github.com/2692341798/load-balanced-online-oj) | Earlier distributed OJ project exploring compile-node health checks, failover, and Linux process sandboxing | C++ · Linux |
| [Message Queue](https://github.com/2692341798/Message_Queue) | RabbitMQ-inspired message broker with direct, fanout, and topic exchanges, durable storage, and acknowledgements | C++ · Muduo · Protobuf · SQLite |

### Tools I work with

- **Languages:** C# · Go · C++ · TypeScript · Python · SQL
- **Backend and integrations:** .NET · Microsoft Graph · OAuth · PostgreSQL · Redis · RabbitMQ
- **Reliability:** structured logging · request correlation · integration testing · Docker · GitHub Actions
- **Systems and AI:** Linux process isolation · worker orchestration · LLM pipelines · SSE
