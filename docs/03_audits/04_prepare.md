---
title: Prepare for an Audit
description: Learn how to maximize the effectiveness of your audit
---

There is a range of measures which you can take to maximize the effectiveness of your audit.

There are 2 groups of such measures: Pre-Audit and Post-Audit.

## Pre-Audit
* Ensure the context is well-documented, including a high-level architecture document.
* Ensure code is well-documented, including inline comments explaining complex logic.
* Ensure unit tests have a minimum coverage: provide your evaluation of coverage. It is recommended to reach 80%-90%.
* Familiarize yourselves with common Substrate vulnerabilities (for example, [Top 10](https://forum.polkadot.network/t/common-vulnerabilities-in-substrate-polkadot-development/3938)) and do a manual walkthrough looking for those types of scenarios.
* If you have skills/time, don’t hesitate to do fuzzy reviews ([resources](https://forum.polkadot.network/t/security-fuzzers-in-polkadot-ecosystem/5948)).
* Perform internal code review before mandating an external audit, and provide your evaluation of coverage.
* Run static analysis tooling and confirm which % of coverage has been achieved before asking for the audit.
* Document known issues, limitations, and critical points of risk/concern, including risk mitigation and context of risk acceptance.
* Confirm the scope of the audit requested to the audit firms and if applicable, what has been descoped and associated rationale.
 
## Post-Audit
