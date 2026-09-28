<div align="center">

# Hey, I'm ModernOps888 👋

### AI Systems Architect · Language Designer · Open-Source Engineer

[![The Forge](https://img.shields.io/badge/The_Forge-Multi_Agent_Swarm-ff6b00?style=for-the-badge&logo=python&logoColor=white)](https://github.com/ModernOps888/the-forge)
[![Vitalis](https://img.shields.io/badge/Vitalis_Lang-Self_Evolving-a855f7?style=for-the-badge&logo=rust&logoColor=white)](https://github.com/ModernOps888/vitalis)
[![MCPlex](https://img.shields.io/badge/MCPlex-Smart_MCP_Gateway-00f0ff?style=for-the-badge&logo=rust&logoColor=white)](https://github.com/ModernOps888/mcplex)
[![AgentLens](https://img.shields.io/badge/AgentLens-DevTools_for_Agents-10b981?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/ModernOps888/agentlens)
[![Free Tools](https://img.shields.io/badge/10+_Free-Dev_Tools-a78bfa?style=for-the-badge&logo=nextdotjs&logoColor=black)](https://infinitytechstack.uk)
[![Consulting](https://img.shields.io/badge/Book_Consulting-22c55e?style=for-the-badge&logo=calendar&logoColor=white)](https://infinitytechstack.uk/consulting)

</div>

---

### 🧬 What I Build (Open Source)

I design and build **autonomous AI systems, developer tooling, compiler backends, and multi-agent platforms** that push the boundaries of software engineering. High-performance production code across **Rust, TypeScript, Python, and C++**.

<div align="center">

| | Project | Category | Stack | Description |
|---|---------|----------|-------|-------------|
| ⚡ | **[MCPlex](https://github.com/ModernOps888/mcplex)** | Agent Infrastructure | Rust · Tokio · Axum | **The MCP Smart Gateway** — Semantic tool routing (70–90% token savings), RBAC guardrails, Prometheus metrics, and multi-model support |
| 🔍 | **[AgentLens](https://github.com/ModernOps888/agentlens)** | Observability | TypeScript · React 19 · Next.js | **Chrome DevTools for AI Agents** — Time-travel debugging, real-time per-model token & cost tracking, anomaly detection, MCP-native |
| 🔥 | **[The Forge](https://github.com/ModernOps888/the-forge)** | Code Evolution | Python · Vitalis JIT · Multi-LLM | **Multi-Agent Code Evolution** — 4 LLMs compete head-to-head in an arena, judged by a JIT compiler and bred across generations |
| 🦀 | **[Vitalis](https://github.com/ModernOps888/vitalis)** | Compilers & Languages | Rust · Cranelift JIT + AOT | Custom self-evolving compiled language — 345 modules, 6,742 tests, native x86-64, ARM64, and RISC-V execution |
| 🧠 | **[Gestalt Blueprint](https://github.com/ModernOps888/gestalt-blueprint)** | Cognitive Systems | Python · FastAPI · Multi-GPU | **Cognitive Architecture & Blueprint Engine** — Cross-platform multi-GPU hardware profiling, dynamic VRAM fit, local SLM |
| 🏆 | **[Neuromantix ARC-AGI-3](https://github.com/ModernOps888/neuromantix-arc-agi-3)** | Neuro-Symbolic AI | Python · SMT · Z3 · AST | **88.0% Verified Win Rate (22/25 Games Won)** on ARC-AGI-3 with bit-exact deterministic replay |
| 📊 | **[Neuromantix LiveBench](https://github.com/ModernOps888/neuromantix-livebench)** | AI Benchmarking | Python · Symbolic Engines | Official LiveBench submission: **97.0% Reasoning**, 100% Data Analysis, 81% Math |
| ✨ | **[Humaniser](https://github.com/ModernOps888/humaniser)** | Privacy & NLP | Vanilla JS · Web APIs | Zero-dependency AI writing humaniser with multi-provider Deep Rewrite (OpenAI, Gemini, Claude, DeepSeek) |
| 📈 | **[Infinity Signal](https://github.com/ModernOps888/infinity-signal)** | Quant Systems | Next.js · TypeScript | Professional-grade multi-indicator trading dashboard (15 indicators, 33 instruments, 4 timeframes) |
| 🛡️ | **[Infinity Security](https://github.com/ModernOps888/infinity-Security-stack)** | IAM & Zero-Trust | Rust · Axum · OIDC | Open-source, Rust-native replacements for SaaS — Infinity ID secure IAM (OIDC/OAuth2, MFA, RBAC) + edge gateway |

</div>

---

## 🏗 Flagship Open-Source Projects

### ⚡ [MCPlex](https://github.com/ModernOps888/mcplex) — The Model Context Protocol Smart Gateway

<a href="https://github.com/ModernOps888/mcplex">
<img src="https://img.shields.io/badge/GitHub-ModernOps888/mcplex-00f0ff?style=for-the-badge&logo=github&logoColor=black" alt="MCPlex Repo" />
</a>

A high-throughput, asynchronous gateway for the **Model Context Protocol (MCP)** written in Rust. MCPlex acts as an intelligent intermediary between autonomous AI agents and dozens of MCP tool servers.

<table>
<tr>
<td align="center" width="25%">

**🎯 Semantic Routing**
Dynamic vector-based tool selection
saving 70–90% in prompt token
overhead per agent turn

</td>
<td align="center" width="25%">

**🔒 RBAC Guardrails**
Fine-grained authorization,
tool execution policies, and
dangerous argument sanitization

</td>
<td align="center" width="25%">

**📊 Observability**
Prometheus metrics, latency
histograms, and structured JSON
audit logs for enterprise runs

</td>
<td align="center" width="25%">

**⚡ Rust-Native Speed**
Sub-millisecond routing overhead
built on Tokio async runtime
and Axum web framework

</td>
</tr>
</table>

```
┌─────────────────────────────────────────────────────────────┐
│   AI Agent (Claude / GPT-4o / Gemini / Local SLM / Cursor)  │
└──────────────────────────────┬──────────────────────────────┘
                               │ MCP Request (JSON-RPC)
                               ▼
┌─────────────────────────────────────────────────────────────┐
│                 ⚡ MCPlex Smart Gateway                     │
│  • Token Optimizer  • RBAC Guardrails  • Prometheus Monitor │
└──────────────┬───────────────┼───────────────┬──────────────┘
               ▼               ▼               ▼
      [ Local Filesystem ]  [ PostgreSQL ]  [ GitHub / Slack ]
```

---

### 🔍 [AgentLens](https://github.com/ModernOps888/agentlens) — Chrome DevTools for AI Agents

<a href="https://github.com/ModernOps888/agentlens">
<img src="https://img.shields.io/badge/GitHub-ModernOps888/agentlens-10b981?style=for-the-badge&logo=github&logoColor=white" alt="AgentLens Repo" />
</a>

An interactive developer cockpit and observability suite designed specifically for **agentic LLM architectures**. Inspect multi-turn agent execution loops, track per-model token expenditure in real time, and debug tool-calling incidents.

<table>
<tr>
<td width="50%">

**Key Features**
- **Time-Travel Debugging** — Step backwards and forwards through multi-agent turns
- **Cost & Token Telemetry** — Real-time tracking across 60+ frontier AI models
- **Tool-Call Inspection** — Full argument validation, return payload diffs, and error detection
- **MCP-Native** — Direct integration with Model Context Protocol servers and clients
- **Modern Stack** — Next.js 15, React 19, Tailwind CSS, TypeScript

</td>
<td width="50%">

**Observability Panels**
- 🕹️ **Live Turn Ledger** — Chronological feed of thoughts, tool calls, and results
- 💰 **FinOps Monitor** — Input, cached input (90% discount), and output cost breakdown
- 🚨 **Incident Watch** — Intercepted failures, infinite-loop detection, timeout alerts
- 📦 **Payload Exporter** — Export sanitized session transcripts for automated test suites

</td>
</tr>
</table>

---

### 🔥 [The Forge](https://github.com/ModernOps888/the-forge) — Multi-Agent Code Evolution Arena

<a href="https://github.com/ModernOps888/the-forge">
<img src="https://img.shields.io/badge/GitHub-ModernOps888/the-forge-ff6b00?style=for-the-badge&logo=github&logoColor=white" alt="The Forge Repo" />
</a>

An open-source multi-agent code evolution platform where **4 distinct LLMs compete in an arena** to generate, optimize, and evolve algorithmic implementations. Solutions are judged by an automated JIT compiler test suite and bred across generations using genetic algorithms.

<table>
<tr>
<td width="50%">

**Evolutionary Workflow**
1. **Arena Challenge** — An optimization target is dispatched to competing LLMs
2. **JIT Execution Judge** — Compiles and benches each candidate against strict test suites
3. **Fitness Scoring** — Measures runtime latency, memory footprint, and code conciseness
4. **Genetic Breeding** — High-fitness ASTs are recombined and mutated for the next generation
5. **Pareto Frontier** — Surfaces optimal speed-memory-readability trade-offs

</td>
<td width="50%">

**Engine Highlights**
- **Multi-LLM Support** — Anthropic Claude, OpenAI, Google Gemini, and local Ollama models
- **Strict Sandboxing** — Capability-restricted execution jail preventing unsafe operations
- **Algorithmic Benchmarking** — Sorting, string matching, graph traversal, and numerical solvers
- **Interactive Terminal UI** — Live generational leaderboards and fitness curve visualizations

</td>
</tr>
</table>

---

### 🧬 [Vitalis](https://github.com/ModernOps888/vitalis) — The Self-Evolving Programming Language

<a href="https://github.com/ModernOps888/vitalis">
<img src="https://img.shields.io/badge/GitHub-ModernOps888/vitalis-a855f7?style=for-the-badge&logo=github&logoColor=white" alt="Vitalis Repo" />
</a>

A compiled programming language built from scratch in **Rust** that generates native machine code via **Cranelift JIT and AOT**. Features an integrated code evolution engine, static effect system, and lifetime analysis. Cross-compiles to x86-64, AArch64 (ARM64), and RISC-V 64.

```
Source (.sl) → Lexer → Parser → AST → Type Checker → SSA IR → Optimize → Cranelift → Native Binary
                                                                                     ↕
                                                                          C FFI & Python Bridge
```

<table>
<tr>
<td width="50%">

**Compiler Pipeline**
- **Lexer** — Logos-based zero-copy tokenizer, 127 token variants
- **Parser** — Recursive-descent + Pratt, typed AST with 27 nodes
- **Type Checker** — Two-pass with scope chains, lifetime analysis
- **IR** — SSA-form with ~30 instruction variants
- **Optimizer** — Constant folding, DCE, strength reduction, predictive JIT
- **Codegen** — Cranelift JIT + AOT → native x86-64, AArch64, RISC-V

</td>
<td width="50%">

**Runtime Features**
- **Evolution Engine** — `@evolvable` functions, fitness tracking, auto-rollback
- **SIMD** — AVX2 F64×4 vectorization (15 ops, ~4× throughput)
- **Effect System** — Static capability types, algebraic effects
- **Lifetime Analysis** — Region-based borrow scopes, outlives constraints
- **Hot Reload** — File watching, incremental recompilation
- **Zero LLVM Dependency** — Fast compilation and minimal footprint

</td>
</tr>
</table>

---

### 🧠 [Gestalt Blueprint](https://github.com/ModernOps888/gestalt-blueprint) — Cognitive Architecture Engine

<a href="https://github.com/ModernOps888/gestalt-blueprint">
<img src="https://img.shields.io/badge/GitHub-ModernOps888/gestalt-blueprint-6366f1?style=for-the-badge&logo=github&logoColor=white" alt="Gestalt Blueprint Repo" />
</a>

Cross-platform multi-GPU hardware profiling, factual VRAM model fitting, and local small-language-model (SLM) synthesis. Dynamically allocates cognitive tasks across available compute tiers (discrete GPUs, Apple Silicon Unified Memory, and CPU fallbacks).

---

### 🛠️ Free Developer Tools & Ecosystem ([infinitytechstack.uk](https://infinitytechstack.uk))

A suite of 10+ production-grade developer tools, interactive academies, and platform extensions — completely free, no sign-up required.

<table>
<tr>
<td width="50%">
  
**Free Developer Tools**
- ⬢ **[Prompt Studio](https://infinitytechstack.uk/prompt-playground)** — 60-model prompt engineering sandbox, simulator & MCP builder
- ⬡ **[Forge SEO](https://infinitytechstack.uk/forge-seo)** — Meta tags & SERP snippet generator
- ◈ **[ResumeForge](https://infinitytechstack.uk/resume-builder)** — AI-powered developer resume builder with role tailoring
- ⎔ **[SchemaForge](https://infinitytechstack.uk/schema-generator)** — JSON-LD structured data generator
- △ **[JSONForge](https://infinitytechstack.uk/json-formatter)** — JSON formatter, validator, and diff tool
- ◇ **[ColorForge](https://infinitytechstack.uk/color-palette)** — UI color palette & contrast generator
- ◈ **[ReadmeForge](https://infinitytechstack.uk/readme-generator)** — GitHub README.md profile generator
- ◇ **[CostForge](https://infinitytechstack.uk/api-calculator)** — LLM API cost comparison calculator
- ⬡ **[PropValuer](https://infinitytechstack.uk/propvaluer)** — Property valuation & rental yield calculation engine
- ✨ **[Humaniser](https://infinitytechstack.uk/humaniser)** — Zero-dependency text humanisation tool

</td>
<td width="50%">

**Interactive Academies & Resources**
- 🎓 **[Claude Academy](https://infinitytechstack.uk/claude-academy)** — Master Anthropic prompting, tool use & extended thinking
- ⚙️ **[MCP Academy](https://infinitytechstack.uk/mcp)** — Master the Model Context Protocol architecture & servers
- 🤖 **[Agents Academy](https://infinitytechstack.uk/agents-academy)** — Build autonomous multi-agent orchestration
- ⚡ **[OpenAI Academy](https://infinitytechstack.uk/openai-academy)** — Master OpenAI o3/o1 reasoning & function calling
- 💻 **[Cursor Academy](https://infinitytechstack.uk/cursor-academy)** — Master Composer agent mode, rules & tab autocomplete
- 🦀 **[Rust Academy](https://infinitytechstack.uk/rust-academy)** — Systems engineering, memory layout & async programming
- 🛡️ **[EU AI Act Hub](https://infinitytechstack.uk/eu-ai-act)** — Regulatory compliance & scope checker
- 🛠️ **[Claude Toolkit](https://infinitytechstack.uk/claude-toolkit)** — Copy-paste configs for IDEs

</td>
</tr>
</table>

---

### 🛠 Tech Stack

<table>
<tr>
<td align="center" width="20%">

**Languages**

</td>
<td align="center" width="20%">

**AI & ML**

</td>
<td align="center" width="20%">

**Cloud & DevOps**

</td>
<td align="center" width="20%">

**Security**

</td>
<td align="center" width="20%">

**Admin**

</td>
</tr>
<tr>
<td align="center">

![Rust](https://img.shields.io/badge/Rust-b7410e?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

</td>
<td align="center">

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-191919?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-00f0ff?style=flat-square&logo=anthropic&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000?style=flat-square&logo=ollama&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor_AI-000?style=flat-square&logo=cursor&logoColor=white)

</td>
<td align="center">

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/K8s-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

</td>
<td align="center">

![CyberSec](https://img.shields.io/badge/Cybersecurity-FF0000?style=flat-square&logo=hackthebox&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000?style=flat-square&logo=owasp&logoColor=white)
![Sentinel](https://img.shields.io/badge/Sentinel-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Defender](https://img.shields.io/badge/Defender-0078D4?style=flat-square&logo=windows&logoColor=white)
![Intune](https://img.shields.io/badge/Intune-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![SIEM](https://img.shields.io/badge/SIEM-333?style=flat-square&logo=elastic&logoColor=white)
![ZeroTrust](https://img.shields.io/badge/Zero_Trust-1a1a2e?style=flat-square&logo=letsencrypt&logoColor=white)

</td>
<td align="center">

![M365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat-square&logo=microsoft&logoColor=white)
![Exchange](https://img.shields.io/badge/Exchange-0078D4?style=flat-square&logo=microsoftexchange&logoColor=white)
![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?style=flat-square&logo=microsoftsharepoint&logoColor=white)
![Teams](https://img.shields.io/badge/Teams-6264A7?style=flat-square&logo=microsoftteams&logoColor=white)
![Power Platform](https://img.shields.io/badge/Power_Platform-742774?style=flat-square&logo=powerautomate&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=windows&logoColor=white)
![Graph API](https://img.shields.io/badge/Graph_API-0078D4?style=flat-square&logo=microsoft&logoColor=white)

</td>
</tr>
</table>

---

### 🎯 Current Focus

- ⚡ Expanding **MCPlex** smart gateway with dynamic semantic routing and vector tool-indexing
- 🔍 Advancing **AgentLens** for deep inspection and real-time cost tracking of autonomous multi-agent runtimes
- 🧬 **Vitalis** compiler cross-compilation (x86_64, AArch64, RISC-V) and self-hosted bootstrap pipeline
- 🤖 Scaling multi-agent code evolution and Pareto consensus in **The Forge**
- 🛡️ Open-source zero-trust security architectures, IAM, and AI agent guardrails

---

### ⚡ Consulting & Services

<table>
<tr>
<td align="center" width="25%">

**🔒 AI Security Audits**
Threat modelling, prompt injection
defence, model supply-chain review

*from £350*

</td>
<td align="center" width="25%">

**🏗️ Architecture Advisory**
System design for autonomous AI,
multi-agent pipelines, Rust toolchains

*£400 / hr*

</td>
<td align="center" width="25%">

**⚡ Custom Toolchain Builds**
Compilers, JIT engines, FFI bridges,
SIMD-accelerated libraries

*Scoped quote*

</td>
<td align="center" width="25%">

**🛡️ M365 & Zero Trust**
Entra ID, Intune, Defender, Purview,
Sentinel — full stack hardening

*Scoped quote*

</td>
</tr>
</table>

<div align="center">

[![Book a Session](https://img.shields.io/badge/Book_a_Consulting_Session_→-infinitytechstack.uk/consulting-22c55e?style=for-the-badge)](https://infinitytechstack.uk/consulting)

</div>

---

<div align="center">

[![Tech Stack](https://img.shields.io/badge/Full_Interactive_Tech_Stack_→-infinitytechstack.uk/techstack-a855f7?style=for-the-badge)](https://infinitytechstack.uk/techstack)

*Building systems that build themselves.*

**100% Open-Source Focus · Rust · Python · TypeScript · C++ · Model Context Protocol (MCP)**

</div>
