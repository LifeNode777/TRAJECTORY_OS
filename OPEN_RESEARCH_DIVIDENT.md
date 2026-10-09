# TRAJECTORY OS — Open Research Dividend (ORD)

**Status:** Concept note / business-model hypothesis — public draft for scrutiny
**Version:** 0.3 (draft). Provisional until recorded Human Anchor acceptance. Versions 0.1 (2026-10-09) and 0.2 (2026-10-09) remain frozen lineage layers (§15).
**Date:** 2026-10-09
**Author:** Krzysztof Baran — Founding Architect, TRAJECTORY OS. v0.1 origin: Human Anchor with AI leg (ChatGPT) as resonator. v0.2 draft: AI leg (Qwen) as formalizer under Human Anchor audit. v0.2→v0.3 audit: AI leg (ChatGPT) as consistency/falsification auditor; v0.3 formalization: AI leg (Qwen) as formalizer. All amendments provisional until acceptance.
**Origin:** LifeNode open-research ecosystem
**License:** CC-BY-NC-SA 4.0 — see §0.3 for exactly what this license covers and what it does not
**Companions:** TRAJECTORY OS Technology Prospectus ("The Spearhead"); Technical Due-Diligence Paper ("The Hammer")

![TRAJECTORY OS — Open Research Dividend: the trajectory of ORD v0.1 → v0.3](https://raw.githubusercontent.com/LifeNode777/PHASE_1/main/img/Open_Research_Dividend_v03.png)

> The more valuable research an organization makes openly usable by others, the less it pays for the infrastructure it uses to conduct research.

**Epistemic legend (used throughout):** OBSERVED — what public records directly show · INTERPRETED — what those observations may reasonably indicate · PROPOSED — what the future program is intended to do · UNKNOWN — what current evidence cannot establish.

**Same-page non-claims restatement:** Economic mechanism: not validated. Traffic is observation, never validation. Narrative is interface, never evidence. AI output is not durable state. The Open Contribution Score — if it ever exists — will score reuse eligibility, process-record integrity, transparency, and evidence of external reusability and use; it will never score scientific truth, correctness, or significance. Screening or assessing a contribution is not certifying it. The canonical project non-claims live in the LifeNode Metasystem Contract §8 (public); this restatement is this document's operative statement until the TRAJECTORY OS repository surface carries that block. Nothing here updates or contradicts the canonical non-claims. Silence is not an update.

## 0. How to read this document

### 0.1 What it is, and what stays internal
This note is public deliberately: a business-model hypothesis whose value lies in execution gains more from being challengeable in the open than from being hidden. Publication invites scrutiny and establishes dated provenance for the concept. What remains internal until a pilot decision: scoring-rubric operations, reviewer tooling and identities, pilot unit economics, partner identities, credit mappings under negotiation. This mirrors the published TRAJECTORY OS IP posture (Hammer §7.2): open doctrine and interfaces; proprietary implementation and deployment know-how.

### 0.2 Terminology: screened and assessed, never "verified" (A8)
This document describes contributions as **eligibility-screened** (passed the §6.1 gate) or **independently assessed** (scored under the §6 rubric). The word "verified" is deliberately avoided for contribution status, because screening and scoring evaluate defined properties of records — permissions, provenance, transparency, replayability evidence — and never the truth or significance of the science behind them. Participation pattern names in §3 follow the same rule.

### 0.3 Three distinct layers of openness (A16)
Openness in this program is three separate decisions, not one:
1. **Public scrutiny of the concept.** This note is public so the mechanism can be attacked before it is built.
2. **License of this text.** CC-BY-NC-SA 4.0 is a deliberate posture: the business-model text is open to scrutiny, attribution-bound, share-alike, and non-commercial. Anyone wishing to implement the ORD mechanism as a commercial service must negotiate separate terms — exactly as Hammer §7.2 states for the kernel.
3. **Licensing of TRAJECTORY OS protocols and implementation.** Governed by the Hammer §7.2 split (selected open protocols, interfaces and doctrine; proprietary operational semantics, engine, security and deployment know-how).
A reader who asks "why does an open-reuse document restrict commercial reuse of its own text?" is asking about layer 2; the answer is that layer 2 protects the ability to keep layers 1 and 3 honest. The three layers are never conflated in pricing, scoring, or licensing decisions.

## 1. The core proposition
Open research creates value beyond the organization that pays to produce it. Reusable code, data, methods, protocols, reproducible workflows, negative results and carefully documented failures help other teams avoid duplicated work and study questions that would otherwise stay expensive or inaccessible. Yet the producer captures only part of that benefit.

The Open Research Dividend proposes a direct economic incentive: **eligibility-screened open contributions can reduce the contributor's TRAJECTORY OS subscription cost.** Open contribution → traceable public value → infrastructure credit → stronger incentive to contribute. The aim is not to convert every organization to an open-science identity; it is to make useful openness an economically rational option while preserving the right to protect legitimate confidential, personal, security-sensitive and proprietary information.

## 2. The problem: private costs, shared benefits
Organizations face real costs in preparing data, maintaining code, documenting methods, supporting replication and explaining failed approaches, while the benefits distribute across the ecosystem. The dividend is a hypothesis (PROPOSED) about how infrastructure pricing can partly close that gap: not as moral obligation, grant condition or communications claim, but as recognized economic value. The mechanism should reward useful, verifiable-in-its-records, reusable contributions — not public-relations activity and not raw volume of published files.

## 3. Three illustrative participation patterns
**A. Closed operation.** General statements of support for science; most relevant outputs unavailable or unusable externally. No dividend; standard price. Not a penalty for being commercial — the absence of a qualifying contribution.

**B. Independently assessed open contributor.** Releases useful research code, data, methods or a reproducible workflow under clearly stated terms, with traceable provenance and documentation sufficient for meaningful evaluation. May qualify for a subscription credit.

**C. Shared-infrastructure builder.** Additionally supports independent replication, maintains a reusable reference implementation, documents negative results, funds shared infrastructure, or enables external audit of complete research records. May qualify for a larger credit, subject to assessment and program economics.

These are conceptual patterns, not finalized customer tiers. Thresholds and discounts require piloting.

## 4. Why this could fit TRAJECTORY OS
TRAJECTORY OS is proposed as trajectory-native infrastructure for persistent multi-agent R&D: process continuity, provenance, explicit verdicts, failure preservation, agent substitution, replay. The production platform and generalized external integrations are development objectives, not completed capabilities (Hammer §5). The dividend extends that orientation into a commercial model: evaluating a contribution's value may require inspecting its provenance, license, methods, execution conditions, limitations, failed attempts, amendments, replication status and later independent use — a trajectory-oriented record could eventually make those elements inspectable. The proposal is to reward organizations for making more of their research **process** reusable and independently assessable, not merely for publishing more artifacts. Nothing here implies that automated scoring, credits, or review infrastructure already exist (PROPOSED).

## 5. What could qualify as an open contribution
Potentially eligible: research software and reference implementations; lawfully shareable datasets with documentation, provenance and governance; sufficiently specified methods and protocols; reproducible workflows (code, configurations, dependencies, execution records); **negative results and failed hypotheses** with conditions, diagnostics, limitations and interpretation changes; replication and independent review records; shared research infrastructure; maintenance and stewardship that keeps a contribution accessible, documented, usable and versioned.

Contributions may be registered as a **set of components** (see §6.5). Eligibility depends on the actual contribution and the rights granted: a publicly viewable repository is not automatically openly reusable; file counts, star counts, download counts and press releases are not evidence of value. Responsible withholding required by law, ethics, safety or valid contract is not a disqualifier and not misconduct (§9).

## 6. Open Contribution Score (OCS) — v0.3 design sketch

### 6.1 Eligibility gate before scoring
A contribution passes the gate only if: the submitter has the right to disclose it and grant the stated permissions; its source and version can be identified; its access terms are explicit; it is described well enough for a reviewer to understand what is offered; and **material restrictions, dependencies and limitations are disclosed — including withheld material on which reuse of the open components materially depends** (§6.5). Only then is it scored. A high score on one dimension never compensates for missing legal permission or unestablishable provenance.

### 6.2 Dimensions (indicative weights; not a validated rubric)

| Dimension | Weight | What it evaluates |
| --- | --- | --- |
| Accessibility and reuse rights | 20% | Access under clear terms permitting the claimed forms of reuse |
| Reproducibility and replayability (tool-neutral, §6.3) | 25% | Whether others have enough material to inspect, reproduce or replay the work, in the evidence forms admitted by the contribution's domain profile (§6.6) |
| Provenance and evidence integrity | 20% | Traceable origin, version history, methods, conditions, supporting records |
| Failure and uncertainty transparency | 15% | Negative results, limitations, discrepancies, amendments documented where relevant |
| External usefulness — assessed reusability | 10% | Domain-reviewer judgment of reuse value, including the avoided-work value of documented dead ends |
| External usefulness — observed reuse | 10% | Evidence of independent reuse, replication, review or integration |

**Boundary declaration (A9):** the OCS assesses reuse eligibility, process-record integrity, transparency, and evidence of external reusability and use. It does not assess scientific truth, correctness, or significance. This declaration governs the table above; any prose or tooling that narrows or widens it is amended prospectively, never silently.

### 6.3 Tool-neutrality clause
Reproducibility and replayability evidence is admissible from **any** method or toolchain: scripts, containers, notebooks, manual protocols, or third-party tools including competitors'. Use of TRAJECTORY OS is neither required nor rewarded in scoring; vendor-tool usage is recorded as OBSERVED metadata only and never enters the score. Rationale: a metric that rewards its own vendor's tooling is a lock-in subsidy wearing an openness costume.

### 6.4 Grace rule and negative-result valuation
Until a contribution has either first reuse evidence or the end of its exposure window, observed reuse is recorded as UNKNOWN — not zero — and the assessed-reusability review carries the combined 20%. **The exposure window is a pilot parameter, not a universal standard (A11):** each domain profile pre-registers its own window (indicative default 24 months; shorter for fast-reuse domains such as software libraries, longer or none for rare-observation domains), and the value is set or killed per profile in the pilot. Observed reuse is never an eligibility requirement. Documented failed hypotheses, dead ends and failed replications are assessed on **avoidance value** (whose work this saves, under what conditions), not on citation or reuse counts; a negative result with zero observed reuse can score full weight on failure transparency and assessed reusability, subject to the estimation protocol and fallback in §6.6.

### 6.5 Partial openness: component-level scoring (A15)
Organizations often publish part of a workflow while withholding part. The rule is component-wise, neither proportional-blur nor binary-gate:
- A contribution is registered as a set of **components** (code, dataset, method, workflow, record); each registered component is scored on its own permissions and evidence; the contribution score is an aggregation over registered components with component weights pre-registered per domain profile.
- **Withheld components are simply not registered:** neither scored nor penalized. Withholding is a right (§9), not a defect.
- **Dependency disclosure:** if reuse of a registered component materially depends on withheld material, that dependency must be declared at the eligibility gate. An undeclared dependency discovered later is a reversal-as-amendment case (§7.1), not a silent rescore.
This design avoids both failure modes: rewarding minimal disclosure (undeclared dependencies break eligibility or trigger reversal) and excluding legitimate hybrid open/proprietary models (withholding itself never lowers a score).

### 6.6 Domain evidence profiles (A10)
Common principles and a common outcome grammar (dimensions, weights, 0–100 per dimension, published rubric version) apply everywhere; **evidence requirements are domain-specific**. Each profile defines, per dimension, the admissible forms of evidence — for example: re-runnable code or containers (software/workflow profile); instrumented, condition-logged observations with lawful sharing terms (datasets/bio profile); single-instance field or astronomical observations with independent archives and reconstruction notes (field/rare-event profile); machine-checked or independently reconstructible arguments (formal profile). Profiles also define the **avoidance-value estimation protocol** for negative results: reviewer judgment with documented reasoning, domain benchmarks of typical replication cost, or later avoided-work citations when they arrive; inter-evaluator consistency is measured in the pilot, and if it falls below a pre-registered threshold the fallback activates prospectively: negative results are scored on transparency dimensions only, with the assessed-reusability weight redistributed to failure transparency by a pre-registered rule.

**Comparability rule:** scores are comparable only within a profile. The score-to-credit mapping uses profile-calibrated bands set (pre-registered) in the pilot. Cross-profile league tables — "90 in biology vs 90 in mathematics" — are invalid and are forbidden in any external communication of the program.

### 6.7 Quality over quantity
The program must not pay more for thousands of trivial artifacts than for one carefully documented, independently reproducible result. Downloads, views, stars and forks are observations of attention; they are neither reuse evidence nor validation, and cannot independently determine any dimension.

## 7. From contribution score to subscription credit

Proposed sequence: (1) establish base price from product costs and pilot customer-value evidence, not invented market numbers; (2) register the contribution (public link, license, provenance, documentation, component list, evidence); (3) review eligibility and quality under the published rubric and profile, recording uncertainty and conflicts of interest; (4) compute the score via a documented, versioned process; (5) apply an earned credit under a published, profile-calibrated mapping; (6) preserve the decision record (evidence, rubric version, profile version, outcome, amendments, appeals).

**Roles and the credit recipient (A12).** Registration carries a role register: author(s), producer, maintainer/steward, replicator, funder. The **steward** — the role accountable for keeping the contribution accessible, documented and versioned — is the default credit recipient. The entity that administratively holds the subscription has **no automatic claim** to credits for contributions it does not steward; this anti-capture rule exists because otherwise the model would reward administrative control rather than research value (the funder–producer–repository–replicator chain case). If steward and payer differ, the credit may be transferred by agreement, directed as a sponsored credit (§7.3), or declined. Multi-steward splits are pre-registered at submission with evidence; disputes follow §8 appeals.

No fixed discount percentages are proposed here. The mapping must account for review costs, subscription economics, contribution maintenance and manipulation risk; discounts are capped at a level that keeps the service solvent (§11.2, C1).

### 7.1 Reversal and amendment
If a scored contribution is later found fabricated, license-laundered, misattributed, or carrying an undeclared material dependency (§6.5), its score is reversed by **recorded amendment**: reason, evidence pointer, rubric and profile versions, decision date. Credits adjust prospectively from the reversal date. Neither the original score nor the reversal is deleted; the decision record retains both — correction as amendment, not erasure, in the same discipline as trajectory records.

### 7.2 Sponsored credits (extension, out of initial pilot scope)
A future extension could let organizations direct part of an earned dividend into sponsored credits for independent researchers, small labs or open-science projects. Tested separately, never assumed into the initial model.

## 8. Anti-gaming and governance
Published criteria (eligibility, dimensions, profiles, evidence requirements, discount mapping). Traceable decisions pointing to evidence, rubric version and profile version. Independent review for high-value or disputed credits. No volume-only rewards. No automatic double counting without defined reason (material new release, demonstrated maintenance, new external use). Role-register attribution (§7). Appeals and corrections that remain traceable. Periodic review of the rubric for gaming, unintended incentives, domain bias and disproportionate burden on smaller contributors. The program must not become an opaque authority deciding what counts as good science; its own evaluation process must be inspectable and correctable. 
**Recusal and vendor affiliation.** Contributions authored or co-authored by the TRAJECTORY OS vendor team, or produced inside vendor-operated pilots, are reviewed only by reviewers without material conflict; credit decisions on them are published with reviewer independence stated. The vendor recuses itself from credit decisions on its own contributions.

**Gaming controls — dead-math for the OCS.** The pilot must include pre-registered manipulation scenarios designed to be caught: volume farming, license laundering, reuse rings via shell organizations, self-reuse loops, negative-result spam, and minimal-disclosure registrations with undeclared dependencies. A pre-registered scenario that passes review undetected is recorded as a control failure and stops rubric adoption until amended prospectively — the same discipline as measurement controls in the parent research program. A scoring apparatus that cannot reject gaming is worse than useless.

## 9. Responsible openness, confidentiality and intellectual property

Open research must not mean disclosure at any cost. Organizations may legitimately withhold personal data, confidential customer information, security-sensitive material, ethically restricted datasets and trade secrets; withholding neither qualifies as an open contribution nor counts as misconduct when required by law, ethics, safety or contract. The scoring model evaluates **actual permissions, not labels**: public availability, open access, open-source licensing and open data are related but not interchangeable. Participation transfers no ownership; customer trajectories and confidential records are not automatically added to any public corpus; no data is reused beyond its license, consent or contractual authorization; open protocols remain governed by their published licenses; proprietary implementation and commercial rights require explicit legal terms.

## 10. Legal, tax and compliance surface

The legal form of a credit (price discount vs rebate vs taxable benefit) is UNKNOWN until legal review. Cross-border VAT/GST treatment of credit issuance is UNKNOWN. To limit implied certification, program language uses "scored contribution record", "eligibility-screened" and "independently assessed", never "verified" or "certified" research; whether that language suffices is UNKNOWN until review. Review records may contain submitter-supplied metadata; data-minimization and retention rules are PROPOSED for the pilot. Scoring modifies no license.

**Audit and certification scope boundary (A17).** Where the companion Hammer lists audit and certification services as potential revenue, the auditable object is **process integrity** — provenance chains, replay completeness, tamper-evidence, role and decision records — never scientific truth or significance. OCS scores and ORD credits are inputs to pricing, not certificates; any future certification offering must inherit this boundary in its own documentation, in both documents, at the same amendment window.

This section is input to the funded legal/IP work package (Hammer §9.2); no resolution is claimed here.

## 11. A possible pilot

Before adoption as commercial policy: define rubric v1, profiles v1 and the eligibility gate; evaluate a varied sample of real contributions across domains and organization sizes; record review effort, evaluator disagreement, missing evidence and gaming attempts; test a limited credit against real subscription economics with willing partners; publish a report describing method, results, limitations, failures and required changes. **Pre-registration:** rubric v1, profile windows and bands, gaming controls (§8) and failure criteria are committed before the first scoring run. Candidate measures: number and diversity of qualifying contributions; proportion independently reproducible or meaningfully reused within their profiles; reviewer time and cost per assessment; inter-evaluator consistency (including avoidance-value consistency, §6.6); external reuse evidence; dispute and successful-appeal rates; detected vs undetected manipulation attempts; effect of the credit on participation and solvency. Explicit failure criteria: if review costs overwhelm value created, if scores are easily manipulated, or if the incentive does not increase meaningful open contribution, the model is revised or rejected. A failed pilot produces a documented result, not a rebranded success.

### 11.2 Pilot design constraints (six open questions)

These are pilot design questions, not concept-note gaps. The concept proposes that screened open contributions can reduce infrastructure cost; the pilot determines whether the mechanism is viable, proportionate and behavior-changing.

**C1 — Solvency constraint.** Solvency is defined operationally before the pilot (e.g., credit issuance capped at a pre-registered share of pilot-cohort revenue; operating-margin floor stated). If earned credits breach the definition, the score-to-credit mapping is revised or the mechanism rejected.

**C2 — Review-cost economics.** Two costs are measured separately: reviewer time and cost per assessment, and contributor-side cost of producing and maintaining the contribution. Review depth is tiered by requested credit band (tiers pre-registered). Solvency alone is not success: the net incentive must still be large enough to change behavior (C6).

**C3 — Multi-party attribution.** The role-register protocol (§7) is tested on chain cases (funder / producer / repository maintainer / replicator). Measured: proportionality, auditability, gaming resistance. Watched failure mode: credit captured by the subscription-holding administrator rather than the value contributor.

**C4 — Partial openness.** Component-level scoring (§6.5) is tested against alternatives (proportional single-score, binary gate). Watched failure modes: minimal-disclosure gaming and exclusion of legitimate hybrid models.

**C5 — Avoidance-value estimation.** The §6.6 estimation protocol is tested for inter-evaluator consistency; if consistency falls below the pre-registered threshold, the fallback (transparency-only scoring for negative results, pre-registered weight redistribution) activates prospectively.

**C6 — Behavioral effect, with a no-incentive comparison.** The pilot includes a comparison strategy against a no-incentive baseline (matched organizations not offered the credit, or pre/post within-organization disclosure decisions under pre-registered metrics). Participants sharing valuable material is not evidence that the dividend caused it; they might have been open anyway. The pilot tests whether the mechanism changes organizational decisions, not merely whether the scoring machine runs.

## 12. The intended feedback loop

Research contribution → traceable evidence and terms → quality and reuse assessment → earned infrastructure credit → lower cost of future research → more capacity to create and share reusable knowledge. The intended outcome is neither universal openness nor the elimination of commercial incentives; it is a pricing structure in which sharing useful research resources becomes economically rewarded behavior — and a more legible record of how shared research value is produced: what was contributed, under what conditions, with what evidence, and with what subsequent use.

## 13. What this document explicitly does not claim

It does not claim an implemented feature, a finalized pricing policy, or a promise of future credits. It does not claim a validated rubric (weights are an indicative sketch) or validated unit economics; economic mechanism: not validated. It does not claim that screening or assessing a contribution certifies, verifies or endorses its science: **screened ≠ certified; assessed ≠ true**. The OCS — if it exists — assesses reuse eligibility, process-record integrity, transparency, and evidence of external reusability and use; it does not assess scientific truth, correctness, or significance. Scores are comparable only within a domain profile; cross-profile comparisons are invalid. A high score is not endorsement, certification or peer review. This document updates no canonical non-claim.

## 14. Concept status and open questions

Unresolved: which contribution types produce enough external value to justify a credit; how profile-calibrated bands are set and kept honest; how the score-to-discount mapping preserves solvency while remaining behavior-changing; how review depth tiers stay proportionate; how shared work, maintenance and reuse are attributed across role chains; whether assessed-reusability review can avoid domain bias; the enforcement cost of tool-neutrality; the appeal window for reversals; the legal form of the credit; whether the per-profile exposure windows converge or must stay permanent. These are answered only by a versioned, evidence-led pilot whose rubric, assumptions, results and failures remain traceable.

## 15. Lineage and amendment discipline

**v0.1 (2026-10-09):** frozen origin, reproduced in §16.
**v0.2 (2026-10-09):** frozen layer; amendments **A1** tool-neutrality clause and vendor recusal (conflict-of-interest / lock-in risk); **A2** usefulness split into assessed reusability and observed reuse, grace rule, negative-result valuation (bias against small contributors and negative results); **A3** reversal-as-amendment protocol (missing clawback path); **A4** same-page non-claims restatement and OCS≠validity firewall (certification-drift risk); **A5** legal/tax/compliance section (unexamined enforceability surface); **A6** gaming controls as dead-math for the metric (a metric without designed-to-fail controls is unfalsifiable); **A7** epistemic legend and disclosure-class note (public commercial document must state its evidence grammar and boundaries). v0.2 text is superseded, not erased.
**v0.3 (this draft):** amendments with recorded reasons and sources — **A8** screened/assessed language replaces "verified" (source: ChatGPT leg audit 2026-10-09; certification-drift risk); **A9** expanded OCS boundary declaration covering reusability and use evidence (source: ChatGPT leg audit; v0.2 §0 declaration was narrower than its own dimension table); **A10** domain evidence profiles, within-profile comparability, avoidance-value estimation protocol with pre-registered fallback (sources: ChatGPT leg audit §7-A; Qwen leg audit C5); **A11** exposure window as per-profile pilot parameter (source: ChatGPT leg audit §3); **A12** role register, steward-default credit recipient, anti-capture rule (source: ChatGPT leg audit §7-B; DeSci chain case); **A13** review-cost vs contribution-cost separation and operational solvency definition (sources: ChatGPT leg audit §7-C; Qwen leg audit C1–C2); **A14** no-incentive comparison / behavioral-effect test (source: ChatGPT leg audit §7-D); **A15** component-level partial-openness scoring with dependency disclosure (source: Qwen leg audit C4); **A16** three-layer openness/license clarification (source: ChatGPT leg audit §8-second); **A17** audit/certification scope boundary with The Hammer (source: ChatGPT leg audit §8-second). Pilot constraints C1–C6 (§11.2) map to A13, A13, A12, A15, A10, A14 respectively.
Future layers remain distinct: amendments (prospective only), pilot observations, validated results. Frozen layers are never retro-edited.

## 16. Origin record (v0.1, frozen)

On 2026-10-09, during a discussion about open research and DeSci, a new question emerged: *What if, instead of supporting open research only through grants and donations, research infrastructure itself rewarded organizations for making more of their work openly usable by others?* The Open Research Dividend is the initial formulation of that question as a potential business model for TRAJECTORY OS. This document records the concept at an early stage. It does not claim that the mechanism has been implemented, that a final scoring formula exists, or that its commercial effects are already established.

TRAJECTORY OS — Open Research Dividend.

 **The more you contribute to open research, the less you pay to conduct it.**

🧿
