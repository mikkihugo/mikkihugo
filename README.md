# Hi, I'm Mikki 👋

I build **production-grade distributed systems** at the intersection of AI orchestration, enterprise architecture, and high-performance computing.

## 🎯 Current Focus

### **Singularity Platform** - AI-First Process Orchestration
Building a distributed AI platform combining BPMN, multi-agent systems, and secure execution:

**Architecture:**
- **Erlang/OTP** for fault-tolerant distributed services (12,000+ files monorepo)
- **Custom Bazel rules** for AI/ML workloads (swarm orchestration, federated learning, AGI analysis)
- **Multi-language**: TypeScript (NestJS), Elixir, Rust, Gleam, Python
- **Micro-frontends** with Module Federation (Webpack 5)
- **Dynamic sandboxing**: E2B Cloud, Firecracker MicroVMs, Modal GPU containers

**Services (55+ microservices):**
- Workflow Orchestration (BPMN integration)
- Overwatch Command Center (AI agent supervision)
- Guardian Kubernetes Protection (ML-assisted emergency response)
- Knowledge Graph Service (semantic search)
- Edge Inference Orchestration (distributed ML)
- MLflow Model Registry (MLOps)
- Terminal Session Gateway (secure execution)
- Certificate Authority (PKI infrastructure)

**Self-Improving AI Systems:**
- **CodeSage**: Edge-deployed LLM that refines code with ML Linter feedback loop
- **Central Brain**: Pattern discovery across distributed edge instances
- **VectorGit**: GitHub alternative with NATS-based geographic replication
- **Guardian**: Cross-instance rollback coordination for autonomous AI safety
- **Genesis**: Isolated sandbox for safe experimentation with auto-rollback

**Integration:**
- LangChain, CrewAI, AutoGen (AI frameworks)
- CopilotKit (AI copilot runtime)
- Anthropic SDK (Claude API)
- Microsoft Teams A2A (enterprise collaboration)

**Build System:**
- Bazel monorepo (enterprise-grade)
- Nix flakes (reproducible environments)
- pnpm workspaces (JavaScript)
- Mix (Elixir)

### **VectorDrive** - Self-Learning Distributed Vector Database
Production vector database competing with Pinecone/Qdrant:
- 61µs latency (30x faster than Pinecone's 2ms)
- GNN layers make search improve over time (self-learning)
- PostgreSQL extension with 120+ SQL functions
- Graph database with Cypher/SPARQL queries
- Raft consensus + 16 shards + 3x replication
- 39 attention mechanisms (Flash, Hyperbolic, MoE, Graph)
- SONA (Self-Optimizing Neural Architecture) runtime adaptation
- 2-32x memory compression with adaptive tiering
- Agent economy with bounties and credits
- Production: 500M concurrent streams, 15 regions, <10ms global latency

**FlakeCache** - High-Performance Nix Binary Cache
Production infrastructure for Nix binary caching:
- Elixir backend with S3 storage
- Rust CLI for cache operations
- FastCDC content-defined chunking
- Kubernetes + Fly.io deployment

### **Enterprise Systems** - Microservices at Scale
Java Spring Boot ecosystem for telecom/hosting:
- 30+ microservices (billing, invoicing, ITSM, CMDB)
- RESTful APIs with React frontends
- Liferay Portal integration
- Real-time billing pipelines

### **NixOS Cloud** - Universal Infrastructure
Making declarative infrastructure accessible:
- Universal NixOS images (14+ cloud providers)
- SOPS encrypted secrets
- GitHub Actions automation
- Terraform modules

## 🛠️ Technical Expertise

**Languages:**
- **Systems**: Rust, Go, Elixir, Gleam
- **Enterprise**: Java, TypeScript, Python
- **Scripting**: Shell, Perl, Nix

**Distributed Systems:**
- Erlang/OTP supervision trees
- Raft consensus (VectorDrive clustering)
- Kubernetes orchestration
- NATS messaging
- PostgreSQL (TimescaleDB, pgvector, custom extensions)

**AI/ML:**
- Multi-agent orchestration (swarm intelligence)
- LLM integration (OpenAI, Anthropic, Google)
- Edge-deployed AI systems (CodeSage)
- Self-improving feedback loops (ML Linter)
- Federated learning infrastructure
- Pattern discovery and synchronization (Central Brain)
- Tree-sitter parsing
- Bumblebee (Elixir ML)

**Build & Infrastructure:**
- Bazel (custom rules for AI/ML)
- Nix (reproducible builds)
- Module Federation (micro-frontends)
- GitHub Actions (CI/CD)

**Frontend:**
- React (CopilotKit, Headless UI)
- NestJS backends
- Module Federation
- Real-time UIs

## 🏗️ Architecture Patterns

**Monorepo Management:**
- Bazel for polyglot builds
- pnpm workspaces for JavaScript
- Custom build rules for AI workloads
- Selective test execution

**Microservices:**
- Service mesh patterns
- Event-driven architectures
- CQRS/Event Sourcing
- Saga orchestration

**Security:**
- Dynamic code sandboxing (Firecracker, E2B)
- Certificate authority infrastructure
- Kubernetes security policies
- Encrypted secret management (SOPS)

## 💡 Philosophy

**Production-First** - Build systems that scale to real workloads

**Polyglot When Needed** - Right tool for the job (Erlang for distribution, Rust for speed, Nix for reproducibility)

**Automation Everything** - From builds to deployments to testing

**Type Safety** - Static typing where possible (TypeScript, Rust, Gleam, Elixir specs)

**Open Source** - Contributing back to the ecosystem

## 🌟 Notable Projects

**Singularity Platform**
- 55+ microservices orchestrated with Erlang/OTP
- Custom Bazel rules for AI/ML workloads
- BPMN-based workflow engine (custom-built, not Temporal)
- Multi-agent swarm intelligence
- Production-grade sandboxing

**CodeSage + ML Linter**
- Self-improving AI coding system
- Edge-deployed LLM refines code from larger models
- ML Linter provides continuous feedback loop
- Pattern learning specific to codebase standards
- Gets better over time through fine-tuning

**VectorGit**
- GitHub alternative replacing Git's file storage with vector embeddings
- Stores code AS vectors in pgvector (not text files)
- AST parsing + semantic feature extraction (1536-dimensional embeddings)
- Content addressing via SHA-256 → vector mapping (70% storage reduction)
- Sub-100ms vector lookups (pgvector + Qdrant + Redis 3-layer cache)
- NATS-based geographic replication for data sovereignty (not HTTP)
- Regional isolation: US, EU, APAC clusters with eventual consistency
- Gitea integration maintaining Git API compatibility
- Semantic deduplication and similarity-based conflict resolution

**Central Brain**
- Pattern discovery across edge CodeSage instances
- Three methods: statistical, ML, LLM
- SQLite-based distributed learning
- Confidence tracking and effectiveness metrics
- Global pattern synchronization

**Guardian + Genesis**
- Cross-instance rollback coordination for autonomous AI
- Tracks code changes across all instances with safety profiles
- Auto-approves safe changes (>0.90 semantic similarity)
- Auto-rollbacks on threshold breach (<0.90 success rate)
- Genesis sandbox: 3-layer isolation (filesystem, database, process)
- Learned rollback strategies from historical successes
- pgvector semantic safety analysis
- NATS-based cross-instance coordination

**VectorDrive**
- Self-learning distributed vector database (competes with Pinecone/Qdrant)
- 61µs latency (30x faster than Pinecone)
- GNN layers for adaptive search improvement
- PostgreSQL extension: 120+ SQL functions + 64+ graph functions
- Raft consensus with distributed clustering (16 shards, 3x replication)
- 39 attention mechanisms (Flash, Hyperbolic, Graph, MoE)
- SONA: Runtime adaptation with LoRA + EWC++ + ReasoningBank
- Production-validated: 500M streams, 15 regions, <10ms global latency

**FlakeCache**
- High-performance Nix binary cache
- S3-backed storage with intelligent chunking
- Kubernetes deployment automation
- CLI tools in Rust

**Language Tools**
- Glistix: Gleam → Nix compiler fork
- Tree-sitter grammars (Mermaid.js)
- Code analysis engines

**Infrastructure**
- NixOS cloud images (universal deployment)
- Kubernetes security (Guardian protection)
- CI/CD automation (GitHub Actions)

**Enterprise**
- Complete billing platform (30+ services)
- cPanel/PowerDNS integration
- Real-time payment processing

## 🎓 Key Strengths

**Distributed Systems:**
- Erlang/OTP fault tolerance
- Kubernetes orchestration
- Service mesh architecture
- Event-driven systems

**AI/ML Infrastructure:**
- Multi-agent orchestration
- Self-improving AI systems (CodeSage + Central Brain)
- Autonomous AI safety (Guardian + Genesis)
- Edge-deployed LLM refinement
- Cross-instance rollback coordination
- Semantic safety analysis (pgvector)
- LLM integration patterns
- Federated learning
- Edge inference
- Pattern discovery and learning

**Enterprise Architecture:**
- BPMN process orchestration
- Microservices design
- API gateway patterns
- Message queues (NATS, RabbitMQ)

**Developer Experience:**
- Custom build tooling (Bazel macros)
- Reproducible environments (Nix)
- Type-safe code generation
- Comprehensive testing

---

*Building distributed AI systems that scale to production.* 🚀
