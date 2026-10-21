# Changelog

All notable changes to the Foundational Data Product™ Progressive Certification framework will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html) and the [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) format.

---

## [1.2.1] - 2026-10-21

### Added

- **Additional permission (LICENSE.md).** Any organization, including a commercial organization, may use the framework and calibrate its weights for its own internal operations. Redistributing modified versions, resale, embedding in a commercial product, and paid services to others still require a separate license. README.md and ABOUT.md updated to match.

---

## [1.2.0] - 2026-10-21

Rules for released uses and re-scoring. The workbook's sign-off label now reads "product owner"; its scoring is unchanged.

### Added

- **Released uses on expired readings.** When a reading expires, uses released on it are held until the product is re-scored
- **Use approval below Gold.** Below Gold, the product owner confirms each use the fit check releases

### Changed

- **Owner naming.** "Primary owner" is now "product owner" in the three-owner sign-off (SCORING_METHODOLOGY.md and the workbook's Certification tab)
- **Re-scoring cadence.** At least quarterly for every product, including products at Gold
- **Tier 1 scope.** Tier 1 confirms traceability to the source system; Lineage Transparency measures the full path from source to use

---

## [1.1.0] - 2026-10-21

Clarifications to how certification holds over time. The workbook is unchanged.

### Added

- **Expired readings.** A reading past its re-scoring date shows as expired on the passport, and the seal is suspended until the product is re-scored (SCORING_METHODOLOGY.md, README.md)
- **Scope of sign-off.** The three-owner sign-off records the approved uses. A new use, or a change to the product's meaning, requires a new sign-off even when the score is unchanged
- **Consumer minimums.** The owner of each use sets its minimum dimension percentages and records them with the use, so the fit check can be repeated and audited

### Clarified

- Which weaknesses block which level: exposed data blocks Silver; untraceable origin, absent ownership and conflicting meaning block the seal

---

## [1.0.0] - 2026-10-19

Initial public release of the Foundational Data Product™ Progressive Certification framework as a standalone, citable repository.

### Added

- Excel workbook (`foundational-data-product-certification-v1.0.xlsx`) with eight weighted dimensions, twenty-four criteria scored from 0 to 100, automated certification percentage, certification conditions, dimension floors, certification level and seal, a Trust Profile view and a Consumer Fit check
- README documenting the purpose, audience, dimensions, levels and use of the framework
- SCORING_METHODOLOGY.md explaining the scoring formula, the evidence scale, the weighting rationale, the dimension floors and the certification conditions
- EXAMPLE_OUTPUT.md providing a fully completed sample certification with consumer fit readings for three AI use cases
- ABOUT.md establishing what the framework is for, what it is not for, the assumptions it makes, and its positioning
- LICENSE.md applying CC BY-NC-ND 4.0 with plain-language summary, commercial licensing path, and trademark notice
- CITATION.cff for formal citation in research, advisory work, and institutional reporting
- This CHANGELOG

### Methodology context

The framework extends the six weighted dimensions first published in *Trust Is Not a Gate. It Is a Signal That Must Travel.* (November 2025) with two further dimensions, Semantic Coherence and Accessibility and Interoperability, and adds a portability condition for the certification seal.

---

## Versioning policy

The framework will follow semantic versioning:

- **Major versions (2.0, 3.0, ...)** indicate substantive structural changes: adding or removing dimensions, materially changing the weighting structure, or revising the certification levels and conditions.
- **Minor versions (1.1, 1.2, ...)** indicate refinements to criterion language, weight calibration based on field use, naming alignment, or clarifications to the guidance.
- **Patch versions (1.0.1, 1.0.2, ...)** indicate corrections to typos, formatting, or non-substantive updates.

Each release will be tagged in the GitHub repository and accompanied by release notes documenting the changes and the rationale.

---

*© 2026 Anna Jibgashvili | Foundeon | Foundational Data Products™*
