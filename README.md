### Md Tanvir Alam

CTO at **Alawaf Technologies Limited** · Dhaka, Bangladesh

I am a hands-on software engineer. My work spans software engineering, AI tooling, banking systems, and cybersecurity and digital forensics.

Previously I was an Oracle contractor, customizing Flexcube for Bank Danamon Indonesia and SMBC Singapore. I was not an Oracle employee.

On GitHub since December 2014. [Website](https://tanvir-ux.github.io)

### Current focus

- Software engineering
- AI tooling, including agents, retrieval, and MCP
- Banking systems
- Cybersecurity and digital forensics

### Selected projects

The repositories below are my own portfolio projects. The banking-shaped ones are demos. They are not bank or customer intellectual property.

**[ai-engineering-stack](https://github.com/tanvir-ux/ai-engineering-stack)** is a knowledge-copilot demo that keeps the whole path in one repository: a React front end, OIDC sign-in and role-based access, a FastAPI gateway, LangGraph orchestration with a human approval step, an OpenAI Agents SDK agent, an MCP tool server, PySpark and Delta, a Databricks bundle, Snowflake SQL and dbt, hybrid retrieval with evals, Docker, Helm, a Terraform sketch, and CI. The project README says what was run and what was only validated. [Recorded replay](https://ai-engineering-stack-demo.netlify.app/).

Related AI demos:

- **[agent-platform](https://github.com/tanvir-ux/agent-platform)** — One support task, implemented with several agent frameworks, behind FastAPI, MCP, and A2A. [Demo](https://tanvir-ux.github.io/agent-platform/).
- **[graphrag-service](https://github.com/tanvir-ux/graphrag-service)** — GraphRAG compared with vector RAG, with LlamaIndex and LangChain adapters and an evaluation harness. [Demo](https://tanvir-ux.github.io/graphrag-service/).
- **[llm-finetune-serve](https://github.com/tanvir-ux/llm-finetune-serve)** — LoRA fine-tuning of SmolLM2 on CPU, plus an OpenAI-compatible server. The project README separates runs that were executed from deploy code that was not run. [Demo](https://tanvir-ux.github.io/llm-finetune-serve/).

Banking-shaped demos:

- **[agentic-mcp-gateway](https://github.com/tanvir-ux/agentic-mcp-gateway)** — MCP server and agentic RAG tools that retrieve docs, search mock payments, and create tickets. The default path runs without an API key.
- **[banking-payments-spring](https://github.com/tanvir-ux/banking-payments-spring)** — Spring Boot 3 / Java 17 payments API with JWT, idempotency, Kafka events, and ISO 20022-inspired flows.
- **[kafka-spring-microservices](https://github.com/tanvir-ux/kafka-spring-microservices)** — Transfer API, double-entry ledger, and notifications over Kafka, with Docker Compose and Kubernetes manifests.

### Open source

Selected pull requests I authored. Maintainers of each project merged them.

- **[Google Gson](https://github.com/google/gson)** — Update the JSON path after `promoteNameToValue`. [#3098](https://github.com/google/gson/pull/3098), merged 2026.
- **[Meta Infer](https://github.com/meta/infer)** — Fix a BufferOverrun false positive on `String.split` with a non-positive limit. [#2094](https://github.com/meta/infer/pull/2094), merged 2026.
- **[Apache Maven](https://github.com/apache/maven)** — Fix `ArtifactCoordinates.getId()` so an empty classifier does not produce a double colon. [#12813](https://github.com/apache/maven/pull/12813), merged 2026.
- **[Apache Commons IO](https://github.com/apache/commons-io)** — Do not discard `CharsetEncoder` errors in `ReaderInputStream` (IO-780). [#874](https://github.com/apache/commons-io/pull/874), merged 2026.
- **[Netflix DGS](https://github.com/Netflix/dgs-framework)** — Preserve a user's `spring.autoconfigure.exclude` list. [#2339](https://github.com/Netflix/dgs-framework/pull/2339), merged 2026.
- **[Checkstyle](https://github.com/checkstyle/checkstyle)** — Quote UnusedLocalVariable examples. [#21362](https://github.com/checkstyle/checkstyle/pull/21362) and [#21363](https://github.com/checkstyle/checkstyle/pull/21363), merged 2026.

Earlier documentation fix: [keras-team/keras-io#596](https://github.com/keras-team/keras-io/pull/596), merged in 2021.

[GitHub profile](https://github.com/tanvir-ux) · [GitRanks profile](https://gitranks.com/profile/tanvir-ux)
