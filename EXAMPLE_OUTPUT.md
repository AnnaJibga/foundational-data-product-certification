# Example Output

*A fully completed sample certification, showing what running the Foundational Data Product™ Progressive Certification produces.*

---

## Context for the example

The organization in this example is a fictional mid-size financial services firm. It has built its first Foundational Data Product™, **Customer Core**: one governed identity for every customer, used by onboarding, servicing, risk and compliance. Three AI use cases want to consume it. Leadership asked for a certification reading before approving them. The firm is a composite and is not based on any real organization.

## Completed certification

### Dimension 1: Data Quality

| Criterion | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Critical data elements meet completeness and correctness targets at the source and in the product | 90 | 0.05 | 4.50 |
| Data arrives within each source's contracted refresh frequency | 85 | 0.05 | 4.25 |
| Duplicates and cross-source conflicts are identified and resolved against a declared authoritative source per attribute | 78 | 0.05 | 3.90 |
| **Dimension subtotal** | | | **12.65 / 15.00 (84.3%)** |

### Dimension 2: Semantic Coherence

| Criterion | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Every critical data element carries an approved business definition | 88 | 0.05 | 4.40 |
| Definitions are reconciled with the enterprise-level meaning used by other products, with no open conflicts | 62 | 0.05 | 3.10 |
| Each concept resolves to a single column definition and name across the sources that feed the product | 80 | 0.05 | 4.00 |
| **Dimension subtotal** | | | **11.50 / 15.00 (76.7%)** |

### Dimension 3: Metadata Completeness

| Criterion | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| The product contract states purpose, scope, ownership, permitted use and prohibited use | 92 | 0.0334 | 3.07 |
| Every field carries a description, data type and classification | 80 | 0.0333 | 2.66 |
| The product is registered in the enterprise catalog with its passport | 95 | 0.0333 | 3.16 |
| **Dimension subtotal** | | | **8.90 / 10.00 (89.0%)** |

### Dimension 4: Lineage Transparency

| Criterion | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| The origin of every attribute is documented | 75 | 0.05 | 3.75 |
| Transformations from source to product are documented and versioned | 70 | 0.05 | 3.50 |
| Lineage is traceable through to consumption and has been audited | 60 | 0.05 | 3.00 |
| **Dimension subtotal** | | | **10.25 / 15.00 (68.3%)** |

### Dimension 5: Security and Compliance

| Criterion | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Access controls enforce the permitted uses stated in the contract | 90 | 0.05 | 4.50 |
| Sensitive data is masked, encrypted or minimized as policy requires | 88 | 0.05 | 4.40 |
| Applicable regulatory obligations are mapped to the product and evidenced | 85 | 0.05 | 4.25 |
| **Dimension subtotal** | | | **13.15 / 15.00 (87.7%)** |

### Dimension 6: Governance

| Criterion | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| A named owner and steward, held as roles, hold explicit decision rights over the product | 90 | 0.0334 | 3.01 |
| Changes to meaning, permitted use or authority follow approved change control, with each approval recorded | 72 | 0.0333 | 2.40 |
| Incident and escalation paths are defined and have been tested | 80 | 0.0333 | 2.66 |
| **Dimension subtotal** | | | **8.07 / 10.00 (80.7%)** |

### Dimension 7: Performance

| Criterion | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Freshness and latency meet the service levels in the contract | 92 | 0.0267 | 2.46 |
| Availability meets its target | 95 | 0.0267 | 2.54 |
| Monitoring and alerting cover failures, quality breaches and service-level breaches | 88 | 0.0266 | 2.34 |
| **Dimension subtotal** | | | **7.33 / 8.00 (91.7%)** |

### Dimension 8: Accessibility and Interoperability

| Criterion | Score | Weight | Weighted Score |
| --- | --- | --- | --- |
| Governed access methods are documented and tested | 85 | 0.04 | 3.40 |
| People and systems, including AI agents, can consume the product through a machine-readable contract and standard interfaces | 80 | 0.04 | 3.20 |
| The product joins to other Foundational Data Products™ through shared, governed identifiers | 70 | 0.04 | 2.80 |
| **Dimension subtotal** | | | **9.40 / 12.00 (78.3%)** |

## Conditions

| Condition | Answer |
| --- | --- |
| Tier 1 checks complete | Yes |
| Tier 2 checks complete | Yes |
| Three-owner sign-off complete | Yes |
| Portability condition met | Yes |

## Result

| | |
| --- | --- |
| **Certification percentage** | **81.25 / 100** |
| **Score band** | Gold band (80–100) |
| **Floor: Lineage Transparency ≥ 70** | Not met (68.3) |
| **Certification level** | **Silver** |
| **Certification seal** | Not yet active |

## Interpretation

### What the result means

Customer Core scores 81.25, inside the Gold band. Every condition is met except one floor: Lineage Transparency stands at 68.3, below the 70 that Gold requires. The product is certified at Silver, and the seal is not yet active.

This is the case the floors exist for. Strong quality, security and performance lift the average above 80. Averaging alone would award the seal to a product whose lineage has not been audited end to end. If an AI-supported decision built on this product were challenged, the firm could not yet show the full path from source to consumption.

### What each consumer sees

The passport shows all eight dimension percentages. Each consumer reads them against its own purpose.

| Dimension | Product | Servicing assistant agent | Credit decisioning agent | Regulatory reporting |
| --- | --- | --- | --- | --- |
| Data Quality | 84.3 | needs 80 · meets | needs 85 · **below** | needs 80 · meets |
| Semantic Coherence | 76.7 | needs 75 · meets | needs 75 · meets | not relevant |
| Metadata Completeness | 89.0 | not relevant | not relevant | needs 80 · meets |
| Lineage Transparency | 68.3 | not relevant | needs 80 · **below** | needs 85 · **below** |
| Security and Compliance | 87.7 | needs 80 · meets | needs 85 · meets | needs 80 · meets |
| Governance | 80.7 | not relevant | not relevant | needs 80 · meets |
| Performance | 91.7 | needs 85 · meets | not relevant | not relevant |
| Accessibility and Interoperability | 78.3 | needs 70 · meets | needs 70 · meets | not relevant |
| **Fit for this purpose** | | **Yes** | **Not yet** | **Not yet** |

The servicing assistant can proceed today. Its purpose depends on quality, meaning, protection and speed, and the product meets all four. The credit decisioning agent and the regulatory filing wait for lineage, and the credit agent also waits for one data quality criterion.

One product. Three readings. Each one honest.

### What to act on

1. **Close the lineage gap first.** Audit lineage through to consumption (criterion 4.3, scored 60). Lifting Lineage Transparency to 70 releases the Gold seal. Reaching the 85 that regulatory reporting needs also requires stronger origin and transformation documentation (criteria 4.1 and 4.2).
2. **Resolve the open meaning conflict** (criterion 2.2, scored 62). Another product defines "active customer" differently; agree the enterprise-level meaning with both owners.
3. **Tighten cross-source conflict resolution** (criterion 1.3, scored 78) to lift Data Quality above the credit agent's 85.

### Re-certification cadence

Scores are a current reading. Refresh them whenever a source system, a governance policy or a regulatory requirement changes, and at least quarterly while the product is moving toward Gold.

---

## How to read your own results

1. **Look at the certification level** to see where the product stands overall.
2. **Look at the dimension percentages**, because that is what consumers and agents act on.
3. **Check the floors and conditions.** A product in the Gold band held at Silver tells you exactly which gap to close.
4. **Run the Consumer Fit check** for each intended use. Release the uses the product already supports.

For consultation on certifying your products or designing passports, contact `anna@foundeon.com`.

---

*© 2026 Anna Jibgashvili | Foundeon | Foundational Data Products™*
