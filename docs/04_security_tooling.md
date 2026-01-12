---
title: Security Tooling
---

PAL funds the development of security tooling which benefits the Polkadot ecosystem.

On this page you will find a list of all security tools that were funded by PAL, organized by category. If you are looking to apply for funding, check out the [funding page](/funding/security_tooling).

## Static Analysis
### Scout by Coinfabrik
Link: [https://github.com/CoinFabrik/scout-audit](https://github.com/CoinFabrik/scout-audit)

Scout is a static analysis tool which enables developers to automatically identify common vulnerabilities in their code (e.g. unsafe math). It includes 19+ detectors for Substrate, and 33+ detectors of Ink! smart contracts. The detectors have been selected based on an analysis of security audits to identify the most common issues.

Scout uses the rustc compiler infrastructure to analyze the syntax tree and detect problematic code. Developers can run Scout on their projects with a single command to receive a detailed report of detected issues. The tool supports multiple output formats, including HTML and Markdown, allowing users to choose the one that best fits their workflow. Additionally, Scout integrates into development environments through the Scout VS Code Extension and into CI/CD pipelines via the Scout GitHub Action.

Scout also includes a machine learning dataset which can be used to RAG train a model on Polkadot-SDK vulnerabilities - [scout-substrate-dataset](https://github.com/CoinFabrik/scout-substrate-dataset). This dataset is also available on [Hugging Face](https://huggingface.co/datasets/CoinFabrik/scout-substrate).

## Monitoring
### Polkadot Ecosystem Monitoring Tool

Link: [https://www.ocelloids.net/docs/](https://www.ocelloids.net/docs/)

The Polkadot Ecosystem Monitoring Tool is an open-source platform for real-time and historical monitoring across the Polkadot ecosystem, currently under active development. Built on the Ocelloids framework, it provides actionable insight into transfer activity, including cross-chain bridge transfers, DeFi protocol metrics, and governance events.

**Current Capabilities**  
- Tracking major Polkadot interoperability protocols: XCM, Snowbridge, Hyperbridge, Wormhole, and the Polkadot–Kusama Bridge.  
- Monitoring governance proposal life cycles on Polkadot, Kusama, and their parachains.  
- Real-time alerts delivered via Telegram and webhooks.  
- Visibility of all bridge and XCM flows on [XCSCAN](https://xcscan.io).  
- Polkadot and Kusama governance [Telegram notification bot](https://t.me/+skwPmvoNau83OTc0).

**Upcoming Features**  
- A **monitoring console** for teams to manage alerts, visualize metrics, and investigate events.  
- DeFi protocol metrics, including TVL, swap, and lending volumes across Asset Hub, Hydration, Moonbeam, Acala, and Bifrost.  
- Visualization of transfer flows, including XCM and bridged transfers, CEX inflows/outflows, and tagged address activity.  
- Enhanced rule engine with a lightweight DSL for defining custom alert conditions across chains, events, and time.

Source code: [https://github.com/sodazone/ocelloids-services](https://github.com/sodazone/ocelloids-services)
