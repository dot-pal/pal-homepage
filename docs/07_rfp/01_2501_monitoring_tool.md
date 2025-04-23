---
title: 2501 - Monitoring Tool
description: RFP for an Ecosystem Monitoring Toool
slug: 2501
---

In 2025 PAL aims to facilitate the delivery of a Monitoring Tool for the Polkadot ecosystem which monitors the most important value flows in the Polkadot ecosystem and flags any suspicious activity. The goal of the tool is to improve the security capabilities of the ecosystem by making potentially malicious flows discoverable and enabling teams to detect, respond in a timely manner and facilitate recovery potentially.

This document sets out the general Specifications of the tool, as well as the procedure that can be followed by interested vendors to apply.

## Specifications
Below you find a preliminary list of the most important flows and metrics that should be covered. This list includes both general metrics (applicable to the whole ecosystem, e.g. XCM), and specific metrics. In the case of specific metrics, priority is given to features and products which are of highest importance to the ecosystem (e.g. due to their high usage and economic importance - TVL, Volumes etc).

1. XCM  
    a. Flows between the various chains;  
    b. Excessive minting from a parachain as compared to its reserves;
2. Bridges  
    a. Wormhole to Moonbeam  
    b. Snowbridge  
    c. Polkadot / Kusama bridge  
    d. Hyperbridge  
3. DEFI TVL and Volumes (includes AMMs and lending)  
    a. Hydration AMMs (Omnipool, Stablepools, Isolated Pools) and Hydration Lending  
    b. Acala  
    c. Polkadot AssetHub AMMs  
    d. Bifrost vDOT (total issuance)  
    e. Moonbeam (Moonwell, StellaSwap, Beamex)  
4. CEX Flows between CEX and Polkadot and any relevant chains (funding and trades; to Polkadot and any other chain eg: between USDT AH and Binance, HDX Hydration and Kraken)  
    a. Binance  
    b. Coinbase  
    c. Kraken  
    d. KuCoin  
    e. Gate.io  
    f. OKX  
5. Addresses of interest    
    a. Trigger alerts on addresses flagged already by CEX, DEX  
    b. Trigger alerts on a defined custom list of addresses to be flagged  
6. Governance  
    a. A new proposal is done  
    b. When proposals change future state (from deciding to confirming, from preparing to deciding etc)  
    c. When it is executed  

All amounts should be tracked both in asset amount and DOT in USD amount.

In addition, the tool must provide the ability to allow teams to define custom rules (For example,  storage value of X @ chain A + storage value of Y @ chain B - storage value of Z @ chain C smaller than 100).

## How to Apply
Vendors who are interested to deliver the requested tool can apply following this procedure (**application deadline: May 15th, 2025**):

* Check out the [eligibility criteria](/funding/security_tooling). A short recap hereunder:
    * Max funding is $250,000, split into milestones not exceeding $50,000
    * If the total costs exceed this limit, it can be negotiated to deliver an MVP with the core functionality that fits within the limit, with a follow-up request to OpenGov to cover the remaining functionality (once the MVP has been delivered)
    * The tool should be open-source
* Apply by submitting [this form](https://forms.gle/AjtCnAPagab7bQPv7)
* The application should include an offer which details out the scope of the implementation, the timeframes, the milestones and the cost (including man-hours and rate per role)  
* The proposal should cover the maintenance of the tool during 12 months after its delivery, as well as an estimate of the maintenance costs thereafter


Once you submit your application, please [join our Discord](https://discord.gg/xDyGGcnCJw) and get in touch.
