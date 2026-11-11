# SAILLENT
### Runtime Enforcement for Autonomous AI

**The AI Action Firewall.**

The model can decide what to do. SAILLENT decides whether it gets to happen.

[saillent.com](https://www.saillent.com) · info@saillent.com

---

## What We Build

Autonomous AI agents are gaining the ability to interact with tools, APIs and enterprise systems. But the ability to request an operation should never be confused with the authority to perform it.

**SAILLENT is a runtime policy enforcement layer that helps organizations control which actions their AI agents are permitted to execute through covered execution paths.**

It sits between AI systems and protected capabilities, intercepting requests, inspecting relevant context, evaluating explicit policies, and enforcing decisions before requests proceed to protected destinations.

**Intercept. Inspect. Enforce.**

## The Enforcement Layer

SAILLENT provides an independent control point for governing AI execution:

- **Runtime Interception** — Inspect supported requests before they reach protected destinations.
- **Policy Enforcement** — Apply explicit, policy-driven Allow and Deny decisions.
- **AI Tool Authorization** — Govern covered agent and tool execution requests.
- **Data Protection** — Inspect payloads and support PII detection and redaction within supported coverage.
- **Policy as Code** — Define and manage enforcement policies using YAML and Git-based workflows.
- **Audit Evidence** — Record enforcement decisions and relevant execution context.
- **Execution Governance** — Apply controls at the boundary between an AI system's request and the operation it seeks to perform.

## Engineering

Built in Rust, SAILLENT is designed around a high-performance runtime enforcement architecture.

Core engineering areas include:

- Runtime request interception and policy evaluation.
- Synchronous enforcement before forwarding.
- Structured request validation and inspection.
- Payload normalization for supported encoding and evasion cases.
- Policy-driven authorization.
- Quota enforcement and usage accounting.
- Audit recording and operational monitoring.
- Signed licensing and deployment management.

## Security Validation

SAILLENT's engineering approach emphasizes evidence over unsupported security claims.

Validation work includes:

- Policy-engine verification under defined formal harness assumptions.
- Runtime acceptance and integration testing.
- Destination-side testing of denied operations within defined test scenarios.
- Security-focused payload and normalization tests.
- Dependency auditing and software bill of materials generation.
- Release-specific testing and evidence tracking.

Security guarantees are limited to the integrations, configurations, and execution paths actually covered by the runtime and its validation evidence.

## Technology

- **Rust** — Runtime enforcement engine.
- **YAML** — Policy definition.
- **GitOps** — Policy versioning and management.
- **SQLite** — Local audit storage.
- **HTTP/JSON** — Supported request mediation.
- **AI integrations** — Supported OpenAI, Anthropic and MCP-related execution paths.

## Our Principle

AI models generate decisions. Enterprise systems execute operations.

Those are different responsibilities.

SAILLENT exists to enforce the boundary between them: ensuring that an AI agent's ability to request an action does not automatically grant it permission to execute that action.

**Allow what should happen. Block what shouldn't.**

[Website](https://www.saillent.com) · [Contact](mailto:info@saillent.com)
