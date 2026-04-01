<!-- <img src="https://thirdkey.ai/logo-tran.png">  -->

# Secure AI Infrastructure for the Autonomous Future

ThirdKey builds the trust layer for autonomous AI agents — policy enforcement, cryptographic identity, tool governance, and network visibility.

---

## Featured Projects

### [Symbiont](https://github.com/ThirdKeyAI/Symbiont) — Policy-Governed Agent Runtime

> AI agents are easy to demo and hard to trust. Symbiont is the Rust-native execution layer that separates agent intent from execution authority.

- Cedar-based fine-grained policy authorization
- Typestate-enforced ORGA reasoning loop (Observe → Reason → Gate → Act)
- MCP tool integration with SchemaPin cryptographic verification
- Docker sandboxing with resource limits and approval gates
- Tamper-evident cryptographic audit trails
- Secrets management via Vault/OpenBao, persistent memory, and RAG

👉 **[symbiont.dev](https://symbiont.dev)** | **[Source](https://github.com/ThirdKeyAI/Symbiont)**

### [ToolClad](https://github.com/ThirdKeyAI/ToolClad) — Declarative Tool Interface Contracts

> Stop writing repetitive custom code for every tool. ToolClad defines typed, validated, policy-aware tool contracts in `.clad.toml` manifests.

- Three execution modes: **oneshot** (CLI), **session** (interactive PTY with Cedar gating), **browser** (governed headless via CDP/Playwright)
- Shell injection prevention, direct `execve` dispatch, process group isolation
- 14 built-in type validators, conditional evaluation, evidence envelope generation
- Reference implementations in Rust, Python, JavaScript, and Go

### [AgentSniff](https://github.com/ThirdKeyAI/AgentSniff) — AI Agent Network Scanner

> Detect AI agents operating on your network through passive monitoring, active probing, protocol detection, and behavioral analysis.

- Seven detection techniques: passive DNS analysis (40+ LLM API domains), TCP port scanning, AgentPin identity discovery, MCP server probing, HTTP endpoint signatures, JA3 TLS fingerprinting, behavioral traffic patterns
- Deploy standalone, via Docker, or Docker Compose with web dashboard
- Continuous scanning, webhook/SMTP alerting, SQLite history

---

## Trust Stack

| Project | Description |
|--------|-------------|
| 🔐 [SchemaPin](https://github.com/ThirdKeyAI/SchemaPin) | Cryptographic protocol for signing AI tool schemas and policies |
| 🪪 [AgentPin](https://github.com/thirdkeyai/agentpin) | Domain-anchored cryptographic identity for AI agents |

## Research & Tools

| Project | Description |
|--------|-------------|
| 🕶️ [AgentNull](https://github.com/ThirdKeyAI/AgentNull) | Reference implementation of a restricted LLM agent for security testing |
| 📦 [VectorSmuggle](https://github.com/jaschadub/VectorSmuggle) | Covert data exfiltration via vector embeddings (research prototype) |

---

## Stay Connected

- 🌐 Website: [thirdkey.ai](https://thirdkey.ai)
- 🔬 Research: [research.thirdkey.ai](https://research.thirdkey.ai)
- 🧠 Symbiont: [symbiont.dev](https://symbiont.dev)

---

_ThirdKey.ai — Infrastructure for AI you can trust._
