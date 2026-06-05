# Anchor Browser (anchorbrowser)

Anchor Browser is an AI-native cloud browser infrastructure platform that lets AI agents interact with the web the same way a human would. It provides hosted, isolated Chromium sessions ("Anchor Chromium"), built-in stealth and bot-evasion tuning, an authentication layer (OmniConnect) for managing logged-in user credentials, a built-in enterprise VPN, residential and sticky-IP proxies, a Web Action Cache that hardens flaky workflows into deterministic code, and a REST API plus SDKs for Playwright, Puppeteer, MCP, LangChain, and CrewAI. The platform is positioned as the sandbox runtime for agentic browser automation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/anchorbrowser/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/anchorbrowser/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Browser Infrastructure
- AI Agents
- Cloud Browser
- Browser Automation
- Sandbox
- Stealth Browser
- MCP

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Anchor Browser API

The Anchor Browser REST API exposes cloud browser sessions for AI agents. It covers session lifecycle (create, async create, status, end, list history), batch session creation (up to 5,000 simultaneous sessions), browser profiles (save/load cookies, local storage, cache), file upload/download inside sessions, recording with pause/resume, custom browser extensions, AI-driven task execution (Claude, Gemini, OpenAI), web unlocker for bot-protected sites, captcha solving, ad/popup blocking, sticky residential IPs, secret management, and CA certificate management. SDKs are Stainless-generated and an OpenAPI specification is published.

- **Human URL:** [https://docs.anchorbrowser.io](https://docs.anchorbrowser.io)

#### Tags

- Browser Sessions
- REST API
- Browser Automation
- AI Agents

#### Properties

- [Documentation](https://docs.anchorbrowser.io/introduction)
- [Getting Started](https://docs.anchorbrowser.io/quickstart/use-via-sdk)
- [API Reference](https://docs.anchorbrowser.io)
- [Authentication](https://docs.anchorbrowser.io)
- [Console](https://app.anchorbrowser.io/playground)
- [Postman Collection](collections/anchorbrowser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/anchorbrowser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Anchor Browser MCP Server

A Model Context Protocol server (hosted and open-source) that lets MCP-compatible AI clients drive Anchor Browser sessions as tools.

- **Human URL:** [https://browsermcp.com](https://browsermcp.com)

#### Tags

- MCP
- AI Agents
- Browser Automation

#### Properties

- [Documentation](https://docs.anchorbrowser.io)
- [M C P Server](https://browsermcp.com)
- [Postman Collection](collections/anchorbrowser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/anchorbrowser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangChain Anchor Browser Tools

LangChain-ready tools that wrap Anchor Browser-powered browser actions for use inside LangChain and LangGraph agent workflows.

- **Human URL:** [https://github.com/anchorbrowser/langchain-anchorbrowser](https://github.com/anchorbrowser/langchain-anchorbrowser)

#### Tags

- LangChain
- AI Agents
- Integration

#### Properties

- [GitHub Repository](https://github.com/anchorbrowser/langchain-anchorbrowser)
- [Postman Collection](collections/anchorbrowser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/anchorbrowser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://anchorbrowser.io)
- [Documentation](https://docs.anchorbrowser.io)
- [Getting Started](https://docs.anchorbrowser.io/quickstart/use-via-sdk)
- [Authentication](https://docs.anchorbrowser.io)
- [Sign Up](https://app.anchorbrowser.io)
- [Console](https://app.anchorbrowser.io/playground)
- [Blog](https://anchorbrowser.io/blog)
- [Status Page](https://status.anchorbrowser.io)
- [Trust Center](https://trust.anchorbrowser.io)
- [SDK](https://docs.anchorbrowser.io/quickstart/use-via-sdk)
- [GitHub Repository](https://github.com/anchorbrowser/langchain-anchorbrowser)
- [M C P Server](https://browsermcp.com)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [L L Ms Txt](https://docs.anchorbrowser.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** http://apievangelist.com
