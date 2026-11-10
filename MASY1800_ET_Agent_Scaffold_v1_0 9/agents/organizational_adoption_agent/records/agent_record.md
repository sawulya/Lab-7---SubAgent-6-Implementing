# Assignment 7 — Organizational Adoption Agent | Student Record

**Student:** Alexandra Chsherbinina  
**Date:** 2026-11-09  
**Repository:** not yet published (working copy supplied in ZIP)  
**Branch / commit:** not yet created on GitHub; fill after upload  
**Scaffold:** MASY1800_ET_Agent_Scaffold_v1_0 (FROZEN CORE unchanged)  
**Version:** 1.1-student-2026-11-09

## Governing question / context
Can a bank sustainably operate a bounded internal autonomous-agent triage assistant over the next 90 days? The technology and the application remain the same across a conservative, unprepared community bank and a well-equipped moderate adopter. These are **fictional instructional scenarios**, not statements about actual banks.

## Three-level finding
- **ET generally:** Agents can attempt multi-step tasks but configuration-specific reliability, access safety and auditability need testing. Institutional readiness does not alter inherent technology evidence.
- **Application:** Internal triage/drafting with approved knowledge and human review can be evaluated without delegating sensitive decisions to the agent.
- **Organization:** Harbor Community Bank is **NOT READY TO DEPLOY** because of failed load test, untagged access, absent recurring budget and no operating owner. Northbridge Bank is **CONDITIONAL LIMITED PILOT** after documentary budget verification, because sponsor, workflow, owners, capped load tests and controls are in place.
- **Independent judgment:** Do not pilot at Harbor until infrastructure, funding/ownership and governance gates pass. A strictly capped and human-approved pilot at Northbridge can be contemplated after signed ongoing support capacity is shown. The most consequential common risk is unsupported operational sustainability; for Harbor, infrastructure and ownership are also immediate blockers.

## Eight-dimension readiness framework
Leadership; skills/training; workflow; infrastructure/data; resources/budget; governance/risk; culture/change; operating ownership. Each dimension produces strengths, gaps, severity, inferred owner and verification gate. A critical blocker overrides other positive scores.

## Test evidence
- **Primary:** `cases/primary.json` -> `responses/primary_response.json`: NOT READY TO DEPLOY.
- **Context contrast:** `cases/contrast_1.json` -> `responses/contrast_1_response.json`: CONDITIONAL LIMITED PILOT subject to signed funding and operating capacity.
- **Stayed stable:** General ET uncertainty, application scope, human approval and access/audit requirements.
- **Changed appropriately:** Readiness verdict, blockers, first-priority actions, accountable functions and deployment conditions.

## Explicit failed behavior and revision
**Diagnosed v1 weakness (analytical dry run, not a separately stored automated model transcript):** A generic 'provide training, communicate change, and run a pilot' recommendation would have missed the primary scenario's failed load test, missing ongoing budget and absent operating owner. **Revision v1.1:** Explicit eight-dimension gap evidence; critical-blocker override; gap -> action -> owner -> verification -> gate; abstention/request for signed support plan. Both included structured responses use v1.1 instructions. This is a documented critique of an inadequate candidate response, not a claim of an independent third run.

## Evidence / AI use / uncertainty
Case details supplied here are *invented educational assumptions*, not observational or independently verified evidence. ChatGPT assisted with framework design, case construction, structured-output reasoning, critique and documentation. The local scaffold validators check basic output shape, not truth or decision quality. No real bank policies, regulator obligations or current product claims were independently established. Before deploying in reality, request original load/access test records, security reviews, signed budget plan, named operational owners, applicable compliance assessment and user performance metrics.

## Team handoff / boundaries
Include leadership sponsor, training roles, exception workflow, access controls/data quality, load-test evidence, recurring funding and staffing horizon, incident/audit/rollback controls, workforce feedback, and named primary/backup service owners in the shared intake. Agent does **not** certify compliance, approve sensitive actions, or select a vendor. Reassess on material changes to operating capacity, controls, incidents or funding.
