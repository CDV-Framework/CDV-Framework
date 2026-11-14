# CDV scoring rubrics

**Version 1.1** (researcher revision of 1.0, frozen before validation; see [CHANGELOG](../CHANGELOG.md)).

Anchors at Levels 1, 3 and 5 denote absence, partial realisation and full realisation of each democratic criterion. Levels 2 and 4 mark documented progress beyond the lower anchor without reaching the higher one.

D3a and D3b are scored separately and each enters the Process mean. D7 is the unweighted mean of its four sub-dimensions (D7a–D7d).

Source of version 1.0: Melidis, A. (2026). *Co-creation of Democratic Value: A Framework for Evaluating Digital Public Participation.* EGOV-CeDEM-ePart 2026, §§3.2–3.3 (definitions) and Appendix A, Tables A1–A2 (descriptors).

---

## Process dimensions

### D1 — Co-Design of process
*Who designs the rules of participation?*

D1 Co-Design of process assesses citizen participation in designing the participatory process itself — selection of methods, tools, timing, and rules of engagement. Which topics are opened to participation is assessed under D2.

1. Government-only design; no citizen input
2. Citizens informed after the process is designed; non-binding comment
3. Consultative design incorporating citizen feedback on a government-drafted process
4. Active co-design within government-set parameters (e.g., fixed timing and tools)
5. Citizens hold equal or controlling power over process design (methods, tools, timing, rules)

### D2 — Co-Agenda setting
*Who sets the participation agenda?*

D2 Co-Agenda setting evaluates citizen capacity to determine what topics are opened to participation.

1. Fully imposed government agenda
2. Selection from a predefined menu; priority voting; government makes the final selection
3. Mixed agenda allowing citizen proposals alongside government topics
4. Agenda co-shaped through deliberative dialogue; iterative, consensus-building
5. Citizens control which topics are opened to participation, within broad mandates

### D3a — Co-Production
*Who creates proposals, solutions and policy drafts?*

Co-Production evaluates citizen involvement in creating proposals, solutions, and policy drafts.

1. Passive reception of government-produced content
2. Commenting on pre-drafted legislation
3. Citizens produce proposals that the organization aggregates
4. Citizens and organization co-develop content and solutions
5. Equal partnership: citizens co-author content with decisional weight over final outputs

### D3b — Co-Governance
*Who governs the platform itself?*

Co-Governance assesses citizens’ role in managing the platform itself — feature decisions, moderation policies, and governance structures.

1. Full government control of the platform
2. Citizens can flag/report issues
3. User representatives sit on an advisory body
4. Shared decision-making over selected governance domains (e.g., moderation rules and/or feature development)
5. Fully democratic governance with equal citizen participation in platform decisions

### D4 — Co-Analysis of data
*Who interprets the participation data?*

D4 Co-Analysis of data addresses who interprets participation data, whoever controls this interpretation holds power over how participation shapes policy.

1. Closed ministerial/organizational analysis
2. Aggregate results published in structured, reusable form; no access to raw data
3. Open raw-data access without analytical support
4. Tools and support for participatory analysis (visualization, workshops, technical support)
5. Full collaborative analysis; iterative joint interpretation by diverse stakeholders

### D5 — Co-Evaluation of impact
*Who assesses whether participation succeeded?*

D5 Co-Evaluation of impact assesses citizen participation in evaluating whether participation succeeded and what it changed. It incorporates three time horizons: short-term (0–6 months), medium-term (6–24 months) and long-term (2–5+ years).

1. No public impact evaluation
2. Internal evaluation; organization evaluates and publishes; no external verification
3. Open, independent evaluation (by researchers or citizens) is possible, but with no binding commitment to integrate findings
4. Participatory evaluation; mixed team; co-defined indicators; longitudinal tracking
5. Citizens lead the evaluation (they set its questions and indicators and validate its findings); it covers the medium- and long-term horizons, and there is a binding commitment to integrate its findings into the redesign of the next cycle; the evaluation is owned jointly by citizens and the organization: its data, methods and findings are open and reusable by citizens

---

## Values dimensions

### D6 — Inclusion
*Who actually participates and is heard, not only who can participate?*

D6 Inclusion evaluates substantive inclusion of all citizen groups, particularly marginalized populations, across all participation stages, along the access, skills and outcomes divides.

1. Structural exclusion with active barriers
2. Passive accommodation with basic accessibility (e.g., WCAG)
3. Active outreach with targeted campaigns for underrepresented groups
4. Comprehensive strategy (skills, hybrid, intersectional) with monitoring of differential influence across groups (second- and third-level divides tracked)
5. Full equitable participation; structural barrier removal and third-level inequality monitoring

D6 applies a three-level digital divide model (access, skills, outcomes) across five intersectional axes: socioeconomic status, geographic location, demographic characteristics, capabilities, and digital competency.

### D7a — Transparency
*Can citizens see how the process works and how their input was treated?*

Transparency assesses openness regarding processes, decisions, algorithms, moderation choices, and results — including whether citizens can understand how their input was treated.

1. Black-box processes
2. Basic information disclosed
3. Open documentation; decision rationale
4. Input-to-decision traceability for citizens
5. Full process, moderation, and algorithmic traceability

### D7b — Accountability
*Who can oblige the organization to justify or revisit what it decided?*

Accountability assesses whether the organization is obliged to justify to participants and oversight bodies how their input was treated, and whether participants, oversight bodies and civil society can contest that justification with consequences for the organization (vertical, horizontal, diagonal and social channels).

1. No accountability
2. Formal reporting only
3. Explanation of decisions
4. Appeal/redress mechanisms
5. Binding consequences: an independent body or procedure, which participants can activate, can oblige the organization to revisit or re-justify a decision

### D7c — Data protection
*Who controls participants’ personal data?*

Data protection examines data minimization, purpose limitation, informed consent architecture, and citizen control rights over their personal participation data.

1. Opaque data use
2. General privacy policy
3. Regulatory compliance (GDPR/equivalent)
4. Privacy-by-design; data minimization beyond compliance
5. Citizen data sovereignty and portability

### D7d — Sustainability
*Will the process continue regardless of who governs?*

Sustainability assesses political commitment beyond founding administrations, legal embedding, secured multi-year funding, institutional integration across government levels, and civic ownership enabling continuity independent of governmental will.

1. Ad-hoc; no guarantees
2. Survival depends on the current administration's will; or a legal mandate exists but is nominal (no resourcing or continuity)
3. Institutional/legal embedding with resourcing; continuity not yet demonstrated
4. Secured multi-year funding and institutional integration; continuity demonstrated within an administration
5. Continuity proven independent of governmental will (cross-partisan persistence) + civic ownership

---

## Scoring

```
Process Score = (D1 + D2 + D3a + D3b + D4 + D5) / 6
Values Score  = (D6 + D7) / 2
Total CDV     = (Process Score × 0.6) + (Values Score × 0.4)
```

The process score divides by six rather than five because D3 comprises two analytically distinct sub-dimensions, each capturing a different form of power: content-creation power and platform-governance power.

The 60/40 weighting reflects the framework's emphasis on process-based power redistribution while giving transversal democratic values substantial weight. The weights, including the equal weighting of D7a–D7d, are fixed: they do not vary by application or evaluator, so that scores remain comparable across cases. The uncertainty of the choice is handled by sensitivity analysis, not by adjusting the weights: comparative studies report the main score together with an alternative weighting (e.g. 50/50) and the non-compensatory ceiling rule

```
CDV′ = min(CDV, min(D6, D7) + 1)
```

CDV′ is reported alongside the main score and does not replace it. It shows how far high process scores compensate for weak Inclusion or Integrity, which the framework treats as necessary conditions.

### Intermediate and half-point scores

Level 2 is assigned when a platform clearly exceeds the Level 1 anchor but does not reach Level 3; Level 4 when it demonstrably exceeds Level 3 but falls short of Level 5 on documented grounds. Half-point scores (e.g. 4.5) are used when strong evidence supports Level 4 alongside a specific, explicitly cited constraint preventing Level 5. **The constraint cannot rest on evaluator judgement alone — it must derive from cited evidence.**

### Object of evaluation

Scores refer to the participation system as it operates at the time of evaluation: the platform, the procedure that governs it and the practice of the organisations that use it. Neither the software alone nor planned features are scored.

### Evidence, not intention

Every level requires documented evidence. A legal provision that is not applied is not scored on what it provides for. Ascending a scale is a shift of decision-making authority, not an intensity of participation: a higher volume of comments raises no score.

### Process

1. **Preparation** — define evaluation purpose and scope; form a mixed-stakeholder evaluation team including citizen representatives; gather systematic evidence across academic literature, platform documentation and user data.
2. **Dimension-by-dimension assessment** — independent scoring by each team member, followed by structured discussion.
3. **Aggregation** — apply the formula above.
4. **Reporting** — publish scores with the evidence cited for each level.
