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

## [1.1] — unreleased

### A. Researcher revisions

- **Weights fixed across applications.** The 60/40 Process/Values weighting and the equal weighting of D7a–D7d no longer vary by application or evaluator; the uncertainty of the choice is handled by sensitivity analysis (e.g. 50/50).
  *Why:* adjustable weights would give the same process different scores depending on who evaluates it and break comparability across cases.
  *Affected:* `rubrics/CDV-Rubrics.md` (composite score section, "Alternative weightings are permissible…"); dissertation Ch. 4 §§4.4.7, 4.5.3, 4.5.4.
- **Non-compensatory reading added to the sensitivity analysis.** Ceiling rule CDV′ = min(CDV, min(D6, D7) + 1), reported alongside the main score and not replacing it.
  *Why:* D6 Inclusion and D7 Integrity are defined as necessary conditions; the weighted mean lets high process scores compensate for them.
  *Affected:* `rubrics/CDV-Rubrics.md`; dissertation Ch. 4 §4.5.4.

### A. Pending (to be completed before the freeze)

- D5 and D7b: tautological level-5 descriptors.
- D7b: circular definition.
- D1: reference to "agenda parameters" in the definition, against the D1/D2 distinction in Ch. 4.
- Alignment of dissertation Ch. 4 with Appendix A of the EGOV paper (EN and EL).
- Improvements carried over from the Munich (ConsulCon26) and Athens (FOSSCOMM 2026) workshops.

---

## [2.0] — after validation

### B. Validation changes

*(Filled in after the expert-panel session. Each entry: change · decision rule · study item or panel agenda point · panel agreement count.)*

---

## [1.0] — 2026

Initial version: Melidis, A. (2026). *Co-creation of democratic value: A framework for evaluating digital public participation*. EGOV 2026.
