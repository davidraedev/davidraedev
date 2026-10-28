### Hi! I'm David Rae.

I'm a Senior Backend Engineer specializing in distributed systems, Node.js, and hybrid infrastructure (cloud and bare-metal Linux). For the last 9 years I've worked as an independent consultant building scalable, data-intensive applications. That client work lives in private repositories under NDA, which is why my contribution graph is quiet.

**Currently**: I'm building [SpeechWeave](https://speechweave.com), a speech-to-text platform that runs open-source and fine tuned models behind its own API. The API is OpenAI-compatible, so existing apps can switch seamlessly. I designed and built it end to end (arch below)

  - A control plane that queues jobs and provisions, dispatches to, and tears down ephemeral GPU workers based on real-time cost and speed targets
  - Two service modes (standard and a cheaper deferred mode), with results returned inline or through polling and webhooks
  - Usage-based billing with prepaid wallets, metering, and payment reconciliation
  - Official SDKs for Node and Python, plus an MCP server (pinned below)

**Open source**: contributor to [Kilo Code](https://github.com/Kilo-Org/kilocode/pull/3807)

Happy to talk system design: [davidraedev.com](https://davidraedev.com)
