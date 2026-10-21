# Scoring Methodology

*Companion document to the Foundational Data Product™ Progressive Certification framework.*

---

## Purpose

This document explains how certification scores work, why the dimensions are weighted as they are, and what each certification level means. A certification without a transparent scoring method is an opinion. The scoring is the framework.

## Structure

The framework evaluates eight dimensions through twenty-four criteria, three per dimension. Each criterion is scored from 0 to 100 against current evidence. Each criterion carries a weight. The weights sum to 1.0, so the certification percentage runs from 0 to 100.

The formula for each weighted score is:

```
Weighted Score = IF(Score is blank, blank, Score × Weight)
```

No multiplier is needed: scores already run from 0 to 100, and the weights sum to 1.0. A score of 100 on every criterion produces 100.

Two further values are calculated from the weighted scores:

```
Dimension percentage      = Dimension subtotal ÷ Dimension weight
Certification percentage  = Sum of all weighted scores
```

The dimension percentage is the value a consumer sees for each dimension on the product's passport.

## Scoring a criterion

| Score | What the evidence shows |
| --- | --- |
| 0 | No evidence the criterion is met. |
| 1–39 | Partial evidence; the practice exists in places or by individual effort. |
| 40–59 | The practice is defined and applied to part of the product. |
| 60–79 | The practice is applied across the product, with gaps that are known and tracked. |
| 80–99 | The practice is applied across the product, evidenced and monitored. |
| 100 | Fully evidenced, monitored and verified by someone other than the producing team. |

Score current evidence. A planned control scores as not yet in place.

Criteria a platform can measure, such as quality checks, refresh timeliness, availability and access enforcement, can be scored continuously from monitoring. The rest, such as approved definitions, audited lineage and tested escalation paths, are attested by the product's owners against evidence they can show.

Certification records are designed to be sampled by internal audit. Certified products enter the same sample audit draws for other controls, and the audit confirms that a selection of scores and attestations match the evidence.

## The dimensions, in depth

### 1. Data Quality

**Weight: 15% (0.05 per criterion)**

1. Critical data elements meet completeness and correctness targets at the source and in the product.
2. Data arrives within each source's contracted refresh frequency.
3. Duplicates and cross-source conflicts are identified and resolved against a declared authoritative source per attribute.

Data Quality measures whether the data is sound in form, whole, and on time. Correctness here means valid in form: types, formats and permitted values. Whether a value means what the enterprise intends is measured under Semantic Coherence. Source data issues are routed to the source owner, who owns the fix; until then the dimension shows the gap openly.

### 2. Semantic Coherence

**Weight: 15% (0.05 per criterion)**

1. Every critical data element carries an approved business definition.
2. Definitions are reconciled with the enterprise-level meaning used by other products, with no open conflicts.
3. Each concept resolves to a single column definition and name across the sources that feed the product.

A single product can explain itself. When an AI agent reads across several products, it needs their meanings to agree. Semantic Coherence measures whether this product's meaning holds when it meets the rest of the enterprise.

### 3. Metadata Completeness

**Weight: 10% (0.0334, 0.0333, 0.0333)**

1. The product contract states purpose, scope, ownership, permitted use and prohibited use.
2. Every field carries a description, data type and classification.
3. The product is registered in the enterprise catalog with its passport.

Metadata is the mechanism that carries trust with the data. Without it, every other dimension stays invisible to the consumer.

### 4. Lineage Transparency

**Weight: 15% (0.05 per criterion)**

1. The origin of every attribute is documented.
2. Transformations from source to product are documented and versioned.
3. Lineage is traceable through to consumption and has been audited.

Lineage is how the enterprise proves where a value came from when a decision built on it is questioned. It carries one of the highest weights because it is what makes an AI-supported decision reconstructable.

### 5. Security and Compliance

**Weight: 15% (0.05 per criterion)**

1. Access controls enforce the permitted uses stated in the contract.
2. Sensitive data is masked, encrypted or minimized as policy requires.
3. Applicable regulatory obligations are mapped to the product and evidenced.

Protection is built into the product. A gap here cannot be offset by strength elsewhere, which is why this dimension carries a floor at Silver and a higher floor at Gold.

### 6. Governance

**Weight: 10% (0.0334, 0.0333, 0.0333)**

1. A named owner and steward, held as roles, hold explicit decision rights over the product.
2. Changes to meaning, permitted use or authority follow approved change control, with each approval recorded.
3. Incident and escalation paths are defined and have been tested.

Governance is the enforcement layer: who can change the product, under what conditions, and what happens when something goes wrong.

### 7. Performance

**Weight: 8% (0.0267, 0.0267, 0.0266)**

1. Freshness and latency meet the service levels in the contract.
2. Availability meets its target.
3. Monitoring and alerting cover failures, quality breaches and service-level breaches.

Performance decides whether the product can be depended on at the moment it is needed.

### 8. Accessibility and Interoperability

**Weight: 12% (0.04 per criterion)**

1. Governed access methods are documented and tested.
2. People and systems, including AI agents, can consume the product through a machine-readable contract and standard interfaces.
3. The product joins to other Foundational Data Products™ through shared, governed identifiers.

A foundational product exists to be reused. This dimension measures whether reuse is practical, for people and for agents.

## Why the weighting is opinionated

The weights are not equal. They reflect a structural argument about what trust in data requires.

The four trust-critical dimensions, Data Quality, Semantic Coherence, Lineage Transparency, and Security and Compliance, each carry 15%. Together they account for 60% of the certification percentage. They answer four questions every consumer asks: is the data sound, what does it mean, where did it come from, and is it protected.

Accessibility and Interoperability carries 12%, because reuse is the reason a product is foundational.

Metadata Completeness and Governance each carry 10%. They make trust durable: one carries it to the consumer, the other keeps it intact as the product changes.

Performance carries 8%. It matters at the moment of use and is the dimension platforms monitor continuously.

An equal-weight version would hide the argument: trust in data is built from soundness, meaning, origin and protection first.

## Certification levels and conditions

The certification percentage places a product in a band. The level also depends on conditions that a weighted average cannot express.

| Level | Percentage | Conditions |
| --- | --- | --- |
| **Gold** · seal active | 80–100 | Tier 1 and Tier 2 checks complete · three-owner sign-off · Security and Compliance ≥ 80 · Lineage Transparency, Governance and Semantic Coherence ≥ 70 · portability condition met |
| **Silver** | 60–79 | Tier 1 and Tier 2 checks complete · Security and Compliance ≥ 60 |
| **Bronze** | 40–59 | Tier 1 checks complete |
| **Registered** | 0–39 | Registered in the catalog with a passport |

**Tier 1 checks.** The source data is validated for completeness, correctness, traceability to its source system, and timeliness against each source's contracted refresh.

**Tier 2 checks.** The data is clean and ready to consume: fields formatted, columns from multiple sources reconciled to single definitions and names, the full data preserved and loaded into the data model.

**Three-owner sign-off.** The business owner, the product owner and the data owner confirm the product meets the domain's requirements, with the domain's business rules applied. The sign-off records the uses the owners approved. A new use, or a change to the product's meaning, requires a new sign-off even when the score is unchanged. Routine score updates do not.

**Portability condition.** The product's contract, semantic definitions, certification record and passport exist in enterprise-owned form and export without loss of meaning. A product whose meaning can only be read inside one vendor's platform does not earn the seal.

**Dimension floors.** A weighted average lets a strong dimension cover a weak one. Floors prevent that where the weakness cannot be absorbed: exposed data, untraceable origin, absent ownership, and meaning that disagrees with the rest of the enterprise. Exposed data blocks Silver. Untraceable origin, absent ownership and conflicting meaning block the seal.

**Expired readings.** Every certification carries a re-scoring date. Re-scoring is due whenever a source system, a governance policy or a regulation changes, and at least quarterly. A reading past its re-scoring date shows as expired on the passport, the seal is suspended, and uses released on that reading are held until the product is re-scored.

A product that reaches the Gold band without meeting every condition is certified at the highest level whose conditions it meets. The workbook shows which condition holds it there.

## Reading the result

The certification level summarizes the product. The dimension percentages tell each consumer whether it can rely on the product for its purpose.

A consumer, human or agent, states the minimum percentage its purpose needs on the dimensions that matter to it, and leaves the rest open. The owner of each use sets the minimum and records it with the use, so the fit check can be repeated and audited. Below Gold, the product owner confirms each use the fit check releases. The Consumer Fit tab in the workbook performs this check. A product below Gold can be fit for many uses. A product at Gold can still fall short of an unusually demanding one.

Treat the level as the summary. Treat the dimension profile as the decision.

## What this framework does not measure

- **Enterprise readiness for AI.** Covered by the Enterprise Identity Readiness Assessment.
- **Whether a candidate qualifies as foundational.** That is decided by the three criteria, enterprise-critical, enterprise-reusable and enterprise-certifiable, before certification begins.
- **The business value of the product.** Measured separately, through adoption and outcome measures.
- **Model or agent performance.** Agents carry their own requirements and passports.

---

*© 2026 Anna Jibgashvili | Foundeon | Foundational Data Products™*
