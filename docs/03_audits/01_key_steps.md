---
title: Key Steps
description: Overview of the audit process steps
---

This checklist is for project teams preparing for an external audit. Items in bold highlight steps where teams often need extra support.

## Scoping

* Write a concise context summary: what is being built, dependencies, timelines, and intended release.
* **Define and document the functional scope, including what is explicitly out of scope.**
* **Define and document the technical scope (repositories, commit hashes, environments, integrations, toolchain versions).**
* **Draft a lightweight threat model that maps entry points, privileged actors, assets, and known risk areas.**
* Ask for a scope review (PAL, advisor, or peer) to confirm nothing critical is missing.

## Upfront engagement with the suppliers

* Contact multiple auditors early with the context, scope, code locations, and desired audit window.
* Share objectives and expectations (depth of review, focus areas, deliverables, retest approach) so proposals are comparable.
* **Request support to broker introductions or refine scope before contacting suppliers, if needed.**
* Review offers and, if required, ask for changes to align with objectives.
* Compare offers on shared criteria: methodology, allocated engineers, schedule, cost, retest policy, and report format.
* Choose the supplier, agree on communication cadence, and finalize the contract or statement of work.

## Audit

* Provide repo access, build/run instructions, and a primary contact to unblock auditors quickly.
* Keep a regular check-in cadence during the audit to address questions and track emerging findings.
* Confirm each finding is reproducible and actionable; **validate severity and ask for rationale when needed.**
* Plan fixes and, when applicable, schedule a retest; document mitigations or accepted risks.
* Review and sign off on the final report, then share it with relevant stakeholders (including PAL if applicable).
