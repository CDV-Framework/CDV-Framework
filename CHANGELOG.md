# Changelog

Every change to the CDV definitions, rubrics and scoring rules is recorded here, as the README commits to ("revisions are versioned and documented").

## Versions

| Version | Defined by | Source |
|---|---|---|
| 1.0 | The researcher (*researcher-defined*) | Melidis (2026), EGOV 2026: definitions in §§3.2–3.3, descriptors in Appendix A |
| 1.1 | The researcher, before validation | Wording revisions and EN/EL alignment; frozen before the ethics application and the timestamped deposit |
| 2.0 | The researcher, after peer review (*peer-informed*) | Definitional-distinctiveness study and expert panel, under the pre-registered decision rules |

Changes are kept in two categories so that what the researcher changed on his own initiative stays separate from what came out of validation:

- **A. Researcher revision (1.0 → 1.1).** Made to improve the use of the instrument, not to pass the validation checks.
- **B. Validation (1.1 → 2.0).** Each entry cites the decision rule (1–8) and the validation item that triggered it.

Published 1.0 scores (e.g. opengov.gr 1.63, Decidim Barcelona 3.70) remain results of version 1.0, with their stated limitations.

Each entry records: what changed · why · category and rule · affected documents.

---

## [1.1] — 2026-11-14 (frozen before validation)

### A. Researcher revisions

- **Weights fixed across applications.** The 60/40 Process/Values weighting and the equal weighting of D7a–D7d no longer vary by application or evaluator; the uncertainty of the choice is handled by sensitivity analysis (e.g. 50/50).
  *Why:* adjustable weights would give the same process different scores depending on who evaluates it and break comparability across cases.
  *Affected:* `rubrics/CDV-Rubrics.md` (composite score section, "Alternative weightings are permissible…"); dissertation Ch. 4 §§4.4.7, 4.5.3, 4.5.4.
- **Non-compensatory reading added to the sensitivity analysis.** Ceiling rule CDV′ = min(CDV, min(D6, D7) + 1), reported alongside the main score and not replacing it.
  *Why:* D6 Inclusion and D7 Integrity are defined as necessary conditions; the weighted mean lets high process scores compensate for them.
  *Affected:* `rubrics/CDV-Rubrics.md`; dissertation Ch. 4 §4.5.4.

- **D1 definition: "agenda parameters" removed.** The definition now lists methods, tools, timing and rules of engagement, and states that which topics are opened to participation is assessed under D2.
  *Why:* Ch. 4 distinguishes D1 (who sets the rules) from D2 (who sets the topics); the 1.0 definition placed an agenda element inside D1. The definition now matches the D1 Level 5 descriptor, which already listed methods, tools, timing and rules only.
  *Affected:* `rubrics/CDV-Rubrics.md`; dissertation Ch. 4 §4.4.1.
- **D1 Level 4: example of government-set parameters.** "(e.g., timing, scope fixed)" → "(e.g., fixed timing and tools)".
  *Why:* "scope" can be read as the agenda, which now belongs to D2; the examples are taken from the elements of the D1 definition, so that Levels 4 and 5 differ over the same elements.
  *Affected:* `rubrics/CDV-Rubrics.md`, `rubrics/cdv-rubrics.csv`.
- **D2 definition and Level 5: "enter the (participatory) arena" → "are opened to participation".**
  *Why:* the D1 definition refers to D2 with this wording; the English now matches the Greek ("τίθενται σε συμμετοχή"). No change in meaning.
  *Affected:* `rubrics/CDV-Rubrics.md`, `rubrics/cdv-rubrics.csv`.
- **Central question in every definition.** Added to the definitions of D3a, D3b, D4, D6 and D7a–D7d (1.0 had one only for D1, D2 and D5). The rubric questions for D3b and D4 are kept; those for D3a ("Who creates the content?") and D6 ("Who is substantively inside the process?") are replaced to match the definitions; D7a–D7d had none.
  *Why:* a difference in form between definitions can cue the judges of the distinctiveness study. Starting point: the guiding questions of the Munich (ConsulCon26) and FOSSCOMM 2026 worksheets, adapted to the 1.0 definitions and, for D7b, to the 1.1 definition.
  *Affected:* `rubrics/CDV-Rubrics.md`.
- **D5 Level 5 rewritten with observable elements.** "Citizen-led co-evaluation; long-term studies; adaptive-learning cycles; shared ownership" → citizens set the evaluation questions and indicators and validate its findings; medium- and long-term horizons; a binding commitment to integrate the findings into the redesign of the next cycle; joint ownership of the evaluation (open, reusable data, methods and findings).
  *Why:* the 1.0 descriptor repeated the dimension name and did not say what an evaluator must observe to give 5 rather than 4. "Shared ownership" is kept and made observable as ownership of the evaluation. The binding-commitment clause repeats the wording of Level 3 ("no binding commitment to integrate findings"), so that the Level 3/5 difference is explicit.
  *Affected:* `rubrics/CDV-Rubrics.md`, `rubrics/cdv-rubrics.csv`; dissertation Ch. 4 §4.4.5 (after the freeze).
- **D7b definition rewritten.** The organisation's obligation to justify to participants and oversight bodies how their input was treated, and the possibility for participants, oversight bodies and civil society to contest that justification with consequences for the organisation; the four channels of 1.0 (vertical, horizontal, diagonal, social) are kept in parentheses.
  *Why:* the 1.0 definition defined accountability through types of accountability (circular).
  *Affected:* `rubrics/CDV-Rubrics.md`; dissertation Ch. 4 §4.4.7 (after the freeze).
- **D7b Level 5 rewritten.** "Enforceable accountability" → "Binding consequences: an independent body or procedure, which participants can activate, can oblige the organization to revisit or re-justify a decision".
  *Why:* the 1.0 descriptor was tautological. Level 5 now differs from Level 4 (appeal/redress) by independence and obligation.
  *Affected:* `rubrics/CDV-Rubrics.md`, `rubrics/cdv-rubrics.csv`; dissertation Ch. 4 §4.4.7 (after the freeze).
- **Definitions added to the rubrics file; text aligned with the canonical 1.1 wording.** The rubrics file held descriptors only; it now gives each definition. Rubrics file and CSV reproduce the canonical English text verbatim, which removes small divergences of the earlier files (spelling, "or" for "/", and three CSV anchors that lacked the bracketed part of the descriptor: D5 L3, D6 L4, D7d L2).
  *Why:* one text for the freeze and the timestamped deposit.
  *Affected:* `rubrics/CDV-Rubrics.md`, `rubrics/cdv-rubrics.csv`.
- **Object of evaluation stated.** Scores refer to the participation system as it operates at the time of evaluation (platform, governing procedure and the practice of the organisations that use it), not to the software alone or to planned features.
  *Why:* made explicit in the FOSSCOMM 2026 worksheet; applies the existing "Evidence, not intention" rule.
  *Affected:* `rubrics/CDV-Rubrics.md`.

- **"Organization" throughout.** "Government" → "organization" in D1 L1, L3, L4, D2 L1–L3, D3a L1 and D3b L1, as already used in D3a L3–L4, D4, D5 and D7b and throughout the Greek text.
  *Why:* CDV evaluates processes run by municipalities, agencies or associations as well as governments; the mixed wording of 1.0 was inconsistent.
  *Affected:* `rubrics/CDV-Rubrics.md`, `rubrics/cdv-rubrics.csv`.
- **Wording clarifications from the EN/EL equivalence check.** D2 L2 "menu or priority voting" (either suffices, as in the Greek); D3a L2 "legislation or policy documents"; D5 L4 "mixed team (citizens and organization)"; D6 L5 monitoring "that triggers corrective action" (the L4 monitoring is no longer repeated as the L5 criterion); D7a L3 "published decision rationale"; D7d "civic co-ownership"; one opening pattern for all definitions ("Dx Name assesses …"); D4 punctuation.
  *Why:* each closes a reading that the two language versions did not share or that did not separate adjacent levels. The Greek text was corrected in the same pass where it diverged from the English (e.g. D5 L3 and L5 "binding", D6 "intersectional", D7d "administration").
  *Affected:* `rubrics/CDV-Rubrics.md`, `rubrics/cdv-rubrics.csv`; Greek working text.

### EN/EL equivalence check

Back-translation in two passes (14 November 2026): a blind translation of the Greek text into English by one reviewer, then a comparison with the English source by a second reviewer who had not seen the first; the revised items went through a second round. Both reviewers were AI agents working independently; every finding was checked and decided by the researcher.

### Known issues carried to 2.0

- D5 L3 "is possible": whether permitted or actively enabled (with data and access provided) is open in both languages.
- D2 L5 "within broad mandates": who sets the mandate is not stated.

Both are left to the distinctiveness study and the expert panel rather than settled before validation.

### Notes (no change to the framework)

- **Dissertation Ch. 4 aligned with 1.0.** Four descriptors in Ch. 4 §4.4 diverged from Appendix A of the EGOV paper (D2 L5, D3a L5, D5 L3, D7a L4–5); the chapter now follows 1.0. Two related corrections in §4.4.3: D3a L4 no longer mentions decisions, and the D3b definition no longer includes the process.
- **Workshop worksheets.** The Munich (ConsulCon26) and FOSSCOMM 2026 worksheets used the Ch. 4 wording at those points (and, at Munich, a different D6 L4 and a single D7 row). Scores collected with them are workshop scores, not 1.0 or 1.1 scores.

---

## [2.0] — after validation

### B. Validation changes

*(Filled in after the expert-panel session. Each entry: change · decision rule · study item or panel agenda point · panel agreement count.)*

---

## [1.0] — 2026

Initial version: Melidis, A. (2026). *Co-creation of democratic value: A framework for evaluating digital public participation*. EGOV 2026.
