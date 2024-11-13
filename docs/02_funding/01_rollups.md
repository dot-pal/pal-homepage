---
title: Rollups
description: Audits of Polkadot-SDK chains secured by Polkadot
---

PAL can provide funding for audits of Polkadot rollups - i.e. chains built on Polkadot-SDK which are secured by Polkadot.

## Funding
PAL can cover **up to 80%** of the costs of an audit, with a hard cap of **$100,000**.

The maximum payout amount depends on how long the applicant has been producing blocks on the Polkadot network:

| # Consecutive Cores  | # Blocks produced   | Max Payout                      |
|----------------------|---------------------|---------------------------------|
| 1                    | 1 - 403,200         | $ 25,000                        |
| 2                    | 403,201 - 806,400   | $ 50,000                        |
| 3                    | 806,401 - 1,209,600 | $ 75,000                        |
| 4 / Parachain Slot   | 1,209,601 +         | $ 100,000                       |

The limits above apply per project for 6 months. After 6 months, they are reset.

All funding is paid out in DOT using the 30-day DOT EMA price.

## Eligibility Criteria
To receive PAL funding, applications need to satisfy all the following criteria:

* The audit relates to Rust code that is part of the Runtime of a Polkadot-SDK chain or its node host.
* The applicant team is a Polkadot-SDK chain producing blocks on the Polkadot Network secured by Polkadot. 
* The requested amount is, at most, the maximum defined in the table above.
* The code is open source.
* The code is production-ready and under development freeze - no new commits are allowed unless agreed with the auditors (fixes of identified bugs).
* The applicant agrees that PAL will make the audit report public (once the team has addressed any open issues).

## Application
Follow the steps below to apply for audit funding:

1. Ensure you fulfill the [Eligibility Criteria](#eligibility-criteria).
2. Determine the audit scope (LOC + refs, excluding tests).
3. Examine the [Pre-Audit Preparedness Checklist](../03_audits/04_prepare.md).  
4. Join the PAL Discord - this is where all communication takes place.
5. Request at least two offers for an audit from at least 2 PAL-approved auditors.
6. Decide which offer you wish to proceed with.
7. Fill out the Application Form.

Applications are usually processed in 1-2 weeks. We will keep you updated on a dedicated Discord channel.
