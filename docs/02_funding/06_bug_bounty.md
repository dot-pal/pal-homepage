---
title: Bug Bounty
description: Bug Bounty Reimbursement Program for Polkadot-SDK chains secured by Polkadot
---

:::warning
PAL has concluded — no further funding requests are being processed. This page is retained for historical reference. Existing engagements continue per their agreements.
:::

PAL can provide reimbursement for bug bounty programs run by chains built on Polkadot-SDK which are secured by Polkadot.

The Bug Bounty Reimbursement Program supports projects running effective bug bounty programs, ensuring vulnerabilities across the Polkadot ecosystem are discovered, fixed, and disclosed responsibly.

**Final decision on reimbursement amount (or denial) is made by PAL curators.**

## Bug Bounty Autonomy

1. Projects must fully manage their bounty programs (creation, announcements, reward disbursements).
2. PAL may offer guidance but does not run bounties on behalf of projects.
3. PAL will never interfere with any bug bounty program.

## Funding

Through the Bug Bounty Reimbursement Program, PAL can reimburse **up to 50%** of the total whitehat payout (**platform fees excluded**), with a hard cap of **$15,000** per project, every 6 months (**$30,000 per year**).

:::info
The $15,000 / 6 months ($30,000 / year) cap is **combined across all PAL funding programs**. Funds claimed from one program (for example, a parachain audit) count toward the same allowance for every other program (smart contracts, common-good, security tooling, and bug bounty) during the same 6-month period.
:::

Reimbursement is only available for **High** and **Critical** severity findings. The maximum payout per reported vulnerability depends on the severity classification per the following table:

| Severity | Max Payout       |
|----------|------------------|
| Critical | Up to $ 15,000   |
| High     | Up to $ 7,500    |
| Medium   | No reimbursement |
| Low      | No reimbursement |

<br />
In addition, reimbursement amounts consider potential cross-project or systemic risks, bug bounty report quality, timeliness of patching the vulnerability, and responsible disclosure with affected projects and stakeholders.

All funding is paid out in DOT using the 7-day DOT EMA price.

**Final decision on reimbursement amount (or denial) is made by PAL curators.**

## Eligibility Criteria

To be eligible to the Bug Bounty Reimbursement Program, applications need to satisfy all the following criteria:

* The vulnerability reported relates to Rust code that is part of the Runtime of a Polkadot-SDK chain or its node host.
* The applicant team is a Polkadot-SDK chain producing blocks on the Polkadot Network secured by Polkadot, or a common-good project that is part of the Polkadot ecosystem.
* The requested amount does not exceed the cap defined above.
* The code is open source.
* The bug must have been reported after December 1st, 2024 (included).
* The applicant agrees that PAL will make the bounty report public (once the team has addressed any open issues).
* After the team pays a bounty to the bounty reporter (whitehat), and optionally after the vulnerability is fixed, deployed, and ready for disclosure, the project is required to submit:
  1. A bounty report detailing the vulnerability, severity, and resolution.
  2. Evidence of whitehat payments (receipts, transaction IDs, etc.).
* If a discovered vulnerability may affect other projects, PAL may request a private disclosure phase before public release.

Reimbursement applications that fail to meet the criteria above are automatically discarded by PAL curators.

## Application

Follow the steps below to apply for the Bug Bounty Reimbursement Program:

1. Ensure you fulfill the [Eligibility Criteria](#eligibility-criteria).
2. Join the PAL Discord - this is where all communication takes place.
