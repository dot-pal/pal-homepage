---
title: Prepare for an Audit
description: Learn how to maximize the effectiveness of your audit
---

There is a range of measures that you can take to maximize the effectiveness of your audit.

There are two groups of such measures: Pre-Audit and Post-Audit.

## Pre-Audit

Mandatory pre-audit items are:

* Ensure the context is well-documented, including a high-level architecture document.
* Ensure code is well-documented, including inline comments explaining complex logic.
* Ensure unit tests have a minimum coverage: provide your coverage evaluation. It is recommended that the coverage be between 80% and 90%.
* Familiarize yourselves with common Substrate vulnerabilities (for example, [Top 10](https://forum.polkadot.network/t/common-vulnerabilities-in-substrate-polkadot-development/3938)) and do a manual walkthrough looking for those types of scenarios.
* If you have skills/time, don’t hesitate to do fuzzy reviews ([resources](https://forum.polkadot.network/t/security-fuzzers-in-polkadot-ecosystem/5948)).
* Perform an internal code review before mandating an external audit, and provide your evaluation of coverage.
* Run static analysis tooling and confirm which % of coverage has been achieved before requesting the audit.
* Document known issues, limitations, and critical points of risk/concern, including risk mitigation and context of risk acceptance.
* Confirm the scope of the audit requested to the audit firms and, if applicable, what has been descoped and the associated rationale.

Optional, yet recommended, pre-audit items are:

* Create an overall threat model, including data flow diagrams.
* Perform [fuzzy reviews](https://forum.polkadot.network/t/security-fuzzers-in-polkadot-ecosystem/5948).
* Run static analysis tooling and confirm which percentage of coverage has been achieved.
 
## Post-Audit

Mandatory post-audit items are:

* Fix the critical and high-severity security issues found by the auditors. In case of downgrading a vulnerability and/or risk acceptance, the team needs to add detailed context.
* Deliver the full audit report without any alteration to PAL once it is available.
* In case there is a disagreement with the content of the report, which has not been agreed upon with the audit firm, the project can provide a dedicated write-up about it, which will be made available when PAL publishes the report.
* PAL will make the audit report public as received in the subsequent transparency report.

