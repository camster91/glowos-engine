# GlowOS Engine (Mainstream Pi Coding Agent)

<p align="center">
  <strong>The Everyday OS for the Modern Coding Agent</strong>
</p>

## 🚀 The Vision: Accessible Agentic Coding

**GlowOS Engine** is the core backbone for the next generation of Pi coding agents. Originally built as a fork of OpenClaw, GlowOS has pivoted its mission: **Bring powerful, automated, and agentic coding capabilities to mainstream, non-technical people.**

We believe that anyone should be able to spin up an AI developer, give it a prompt, and watch it build software. The GlowOS Engine connects the powerful Pi CLI ecosystem directly into consumer-friendly interfaces (like the GlowOS Broker and PWA), bridging the gap between raw terminal agents and the everyday user.

## 💰 Sustainable Mainstream Access

To provide consistent, high-quality AI coding assistance without burning through API limits or requiring expensive monthly subscriptions, GlowOS utilizes a **24-hour LLM usage reset strategy**. 

- **Daily Quotas:** Users get a fixed amount of LLM compute daily.
- **Profit Margin Friendly:** Costs are capped per user per day, ensuring sustainable scaling.
- **Fair Access:** The reset cycle allows everyday users to accomplish massive coding tasks across a week without paying enterprise prices.

## 🏗 Architecture

GlowOS Engine is designed to run anywhere, but its primary deployment target for consumers is via the **GlowOS Broker** ecosystem:

- **The Engine:** Handles the agent loop, memory, context, and tool execution (via Pi CLI and internal extensions).
- **The Broker:** Connects the isolated Engine safely to the outside world via WebSockets.
- **The Client:** A mainstream, consumer-friendly PWA where the user interacts with their coding agent.

## 🛠 Features

- **Omni-channel Integration:** Connects to Slack, Discord, WebChat, and more.
- **Extensible Skill System:** Add custom capabilities (like GitHub integration, shell execution, or web search) instantly.
- **Persistent Memory:** Remembers user preferences, project context, and past mistakes across sessions.
- **Secure Sandboxing:** Executes code and tasks safely, keeping the host system protected.

## 🚀 Getting Started

If you are a developer looking to build on the GlowOS Engine:

```bash
# Clone the repository
git clone https://github.com/camster91/glowos-engine.git

# Install dependencies (Node 18+ required)
npm install

# Run the setup wizard
npm run onboard
```

## 📜 Roadmap

- [ ] Complete simplification of the OpenClaw underlying system to focus purely on "Coding Agent" tasks.
- [ ] Implement the daily token/usage tracking mechanisms directly in the gateway.
- [ ] Finalize the secure bridge to `glowos-broker`.
- [ ] Release the mainstream PWA client.

---
*Built with 🦞 by the Nexus AI / GlowOS Team.*
