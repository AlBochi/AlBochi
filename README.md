# SAILLENT 🔐

**Runtime Security for AI Agents**

The AI Action Firewall that prevents dangerous actions, prompt injection, and sensitive data exposure.

saillent.com | info@saillent.com

---

## What We Build

SAILLENT is a zero-trust security layer that sits between your AI agents, your models, and your tools. It intercepts, inspects, enforces, and audits every request in real-time.

### AI Action Firewall
PII Shielding → Prompt Injection Protection → MCP Tool Authorization → Zero-Trust Enforcement → Real-Time Audit & Monitoring

### Core Capabilities
- **Data Protection** - Automatic PII detection and redaction before reaching external LLMs
- **Threat Prevention** - Block prompt injection, jailbreak attempts, and indirect attacks
- **Tool Security** - Zero-trust authorization for MCP tool execution
- **Complete Visibility** - Real-time dashboard with audit logs and Prometheus metrics
- **GitOps Policies** - Define security policies in YAML, version control with Git

### Performance
- **140k decisions/second** policy engine
- **<10ms** proxy overhead
- **100%** PII redaction accuracy
- **30+** attack vectors tested and blocked

---

## Technology Stack
Built with Rust for maximum performance and security:
- High-performance policy engine (140k decisions/sec)
- Runtime proxy with streaming support
- Advanced evasion resistance (Unicode, Base64, Gzip, URL encoding)
- Real-time monitoring dashboard
- Docker & Kubernetes deployment

---

## Attack Vectors Blocked
✓ Prompt Injection (direct, indirect, roleplay, translation)  
✓ PII Evasion (Unicode, zero-width, combining chars, Base64, Gzip)  
✓ Tool Obfuscation (full-width Unicode, case variants, whitespace)  
✓ MCP Attacks (SSRF, path traversal, tool chaining)  
✓ Resource Exhaustion (large payloads, deep JSON, concurrent requests)  
✓ Compression Attacks (gzip-encoded PII)  
✓ Agent Impersonation (header spoofing, empty IDs)  
