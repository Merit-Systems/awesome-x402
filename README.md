# Awesome x402

![Merit Logo](./merit-logo.webp)

Curated resources for the x402 ecosystem: specs, repos, standards, and community. Contributions welcome via pull requests.

### Quick Links
- [Website](https://www.x402.org/)
- [Spec / Repo](https://github.com/coinbase/x402)
- [Explorer](https://x402scan.com/)

### What is x402?
x402 is an emerging open standard from the Coinbase ecosystem focused on safer, more composable authorization and transaction flows. This list tracks authoritative resources and adjacent standards commonly used alongside x402-style flows.

### Official Resources
- [x402 Official Website](https://www.x402.org)
- [x402 Whitepaper (PDF)](https://www.x402.org/x402-whitepaper.pdf)
- [x402 Developer Docs Portal](https://docs.cdp.coinbase.com/x402/welcome)
- [Coinbase Announcement – Introducing x402](https://www.coinbase.com/developer-platform/discover/launches/x402)
- [GitHub repo](https://github.com/coinbase/x402) — issues, proposals, and reference materials
  - [Issues](https://github.com/coinbase/x402/issues)
- [Cloudflare Announcement of the x402 Foundation](https://blog.cloudflare.com/x402/)

### Ecosystem
- [x402Scan](https://x402scan.com/) - Analytics and overview of the x402 ecosystem.
- [x402station](https://x402station.com/) - Analytics and monitoring platform for x402 services with real-time insights and performance tracking.
- [x402 Ecosystem Directory](https://www.x402.org/ecosystem)

### Facilitators & Networks
- [Coinbase Hosted Facilitator (Base)](https://docs.cdp.coinbase.com/x402#offload-your-infra)
-- [Supported Networks](https://docs.cdp.coinbase.com/get-started/supported-networks#x402)
- [PayAI Facilitator & Supported Networks](https://docs.payai.network/x402/quickstart#facilitator)
- [thirdweb Facilitator & Supported Networks](https://portal.thirdweb.com/payments/x402/facilitator)
- [Corbits Faremeter Facilitators & Supported Networks](https://docs.corbits.dev/about-corbits/networks)


### Open Source & SDKs
- [coinbase/x402 (GitHub)](https://github.com/coinbase/x402)
- [x402-rs (Rust Facilitator & SDK)](https://github.com/x402-rs/x402-rs)
- [x402 TypeScript SDKs](https://github.com/coinbase/x402/tree/main/typescript)
- [x402-analytics (NPM)](https://www.npmjs.com/package/x402-analytics) - Analytics wrapper for x402 payments with monitoring and insights.
- [x402-Solana (Community)](https://github.com/8bitsats/x402-Solana)
- [Pipegate (x402 + Payment Channels)](https://github.com/Dhruv-2003/pipegate)
- [thirdweb/x402 (Github)](https://github.com/thirdweb-dev/js/tree/main/packages/thirdweb/src/x402)
- [Faremeter (Typescript Facilitator, Middleware, and Examples)](https://github.com/faremeter/faremeter)
- [x402-dotnet (Community)](https://github.com/michielpost/x402-dotnet)
- [MCPay (Build and Monetize MCP servers. SDK, Infrastructure and Examples)](https://github.com/microchipgnu/mcpay)
- [x402-mcp package (Vercel)](https://github.com/ethanniser/x402-mcp)
- [x402proxy server (Proxy Server & API)](https://github.com/zachalam/x402proxy)

### Standards and EIPs
- [ERC-3009 — Transfer With Authorization](https://eips.ethereum.org/EIPS/eip-3009): meta-transaction transfers using EIP-712 signatures, enabling gasless and recipient-submitted transfers.
- [EIP-712 — Typed Structured Data Hashing and Signing](https://eips.ethereum.org/EIPS/eip-712): canonical typed signing used by modern wallets.
- [EIP-2612 — permit for ERC-20](https://eips.ethereum.org/EIPS/eip-2612): approvals via signatures; often complementary to authorization-based flows.
- [ERC-4337 — Account Abstraction (AA)](https://eips.ethereum.org/EIPS/eip-4337): smart account architecture that pairs well with authorization patterns.

#### Extensions
- [ERC-3009 Forwarding](https://github.com/TheGreatAxios/eip3009-forwarder): forwarding contract extending meta-transactions with EIP-721 signatures to any ERC-20 on any network

### Tutorials & Guides
- [QuickNode – How to Implement a Crypto Paywall with x402](https://www.quicknode.com/guides/infrastructure/how-to-use-x402-payment-required)
- [Circle Blog – Autonomous Payments using Circle Wallets, USDC, and x402](https://www.circle.com/blog/autonomous-payments-using-circle-wallets-usdc-and-x402)
- [x402 Quickstart for Sellers](https://docs.cdp.coinbase.com/x402/quickstart-for-sellers)
- [x402 Quickstart for Buyers](https://docs.cdp.coinbase.com/x402/quickstart-for-buyers)
- [MCP Server with x402 Guide](https://docs.cdp.coinbase.com/x402/mcp-server)
- [Base AgentKit – Building Autonomous Agents with x402](https://docs.base.org/agentkit/x402)
- [Vercel x402 MCP SDK Announcement](https://vercel.com/blog/introducing-x402-mcp-open-protocol-payments-for-mcp-tools)

### Example Apps
- [QuickNode Video Paywall Demo](https://www.quicknode.com/sample-app-library/coinbase-x402)
- [Hyperbolic x402 Chat API (LLM Pay-per-Request)](https://github.com/HyperbolicLabs/hyperbolic-x402)
- [Pinata – Pay to Pin on IPFS with x402](https://pinata.cloud/blog/pay-to-pin-on-ipfs-with-x402/)
- [Pinata 402-server (Code)](https://github.com/PinataCloud/402-server)
- [Pinata – Monetize AI Hardware (Jetson) with x402](https://pinata.cloud/blog/using-x402-to-monetize-ai-hardware/)
- [Pinata jetson-x402 (Code)](https://github.com/PinataCloud/jetson-x402)
- [x402 Example Gallery (GitHub)](https://github.com/coinbase/x402/tree/main/examples)
- [x402 Analytics Examples](https://github.com/RemsLabs/x402-analytics-examples) - Practical examples demonstrating x402-analytics usage with buyer and seller implementations.


### Security & Ops
- [x402 Whitepaper – Security Section](https://www.x402.org/x402-whitepaper.pdf)
- [x402 FAQ – Security](https://docs.cdp.coinbase.com/x402/support/faq#security)

### Benchmarks & Analysis
- [Dev.to – x402 vs Traditional Payments (Micropayments)](https://dev.to/pathak_prakarsh/x402-finally-payments-built-for-the-internet-not-bolted-onto-it-1058)

### Videos
- [x402: Building Tools for AI agents, Demos, and Use-Cases](https://www.youtube.com/watch?v=Nodgp7fiPQc&t=197s)
- [x402: Revolutionizing How AI Agents Pay for Services](https://www.youtube.com/watch?v=UQJl8jCDMlo)
- [x402: Building dynamic tools for AI agents, demos, and use-cases.](https://www.youtube.com/watch?v=pL5LxhZ8iCY)
- [Agent Bootcamp with x402 I Lincoln Murr](https://www.youtube.com/watch?v=GtrX9gHfLak)
- [Eliza Social Club: The latest with x402 and autonomous agents](https://www.youtube.com/watch?v=gvLWsY3l_zU)

### Podcasts & Media
- [Cognitive Revolution Podcast – "402 Payment Required"](https://www.cognitiverevolution.ai/402-payment-required-a-new-way-for-ai-agents-to-pay-with-nemil-dalal-dev-platform-lead-coinbase/)
- [The Index Podcast – Coinbase's x402 & AI Agents](https://www.youtube.com/watch?v=P03BXU0fnMo)
- [RelayMag – x402 Handshake Explainer](https://therelaymag.com/x402-the-paywall-handshake-that-lets-agents-pay-the-web)
- [Boosty Labs Blog – AI Agents That Pay Their Own Bills](https://boostylabs.com/ai-agents-that-pay-their-own-bills)
- [a16z – The Month Fintechs Embraced Stablecoins (mentions x402)](https://a16zcrypto.com/posts/article/making-sense-of-stablecoin-news/)

### Community
- [Reddit – r/x402](https://www.reddit.com/r/x402/)
- [Discord – Coinbase Developer Platform](https://discord.com/invite/cdp)
- [x402 Discord Community](https://discord.gg/x402)

### Contributing
- Add high-signal links: specifications, reference implementations, deep-dive posts, audits, and example apps.
- Prefer primary sources and canonical specifications.
- Submit a PR with a concise description; group items under existing sections when possible.

### License
This list is offered under CC0; see upstream specs for their respective licenses.
