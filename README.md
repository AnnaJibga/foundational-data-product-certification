# Foundational Data Product™ Progressive Certification

*A weighted certification framework for trusted, AI-ready data, by [Anna Jibgashvili](https://www.linkedin.com/in/annajibgashvili/).*

*Part of the [Foundeon](https://foundeon.com) methodology and the Foundational Data Products™ framework.*

---

## What this is

The Foundational Data Product™ Progressive Certification framework measures how much trust a data product has earned, dimension by dimension, and makes that trust visible to every person and system that consumes it.

It is built on a structural premise: **trust is a signal that travels with the data.** A pass-or-fail gate tells a consumer only whether a product cleared a bar on the day it was reviewed. Progressive certification tells every consumer, including AI agents, where the product is strong, where it is still building, and whether it can be relied on for a specific purpose today.

A product does not wait for full certification before it can be used. It earns trust in the open, with a certification percentage and a profile that improve as the work progresses.

## What a Foundational Data Product™ is

> A certified, semantically coherent unit of data that serves as a trusted building block for enterprise decision-making and intelligent systems. Not a container of data, but a commitment to decision-grade context, traceability, governance readiness, and institutional meaning.

Three criteria qualify a data product as foundational: it is **enterprise-critical**, **enterprise-reusable**, and **enterprise-certifiable**. This framework measures the third.

## Who this is for

- Chief Data Officers, Chief AI Officers and heads of data products
- Data governance, data quality and data platform leaders
- Chief Risk Officers and Chief Compliance Officers who need evidence that data relied on by AI was trustworthy when it was used
- Architects designing how AI agents consume enterprise data
- Transformation leaders in regulated industries (financial services, insurance, healthcare, public sector)

## How to use it

1. **Download** the Excel workbook from this repository (`foundational-data-product-certification-v1.0.xlsx`).
2. **Score each of the 24 criteria** from 0 to 100 against current evidence. 0 means no evidence; 100 means fully evidenced and monitored. Score what is in place today.
3. **Answer the four certification conditions**: Tier 1 checks, Tier 2 checks, three-owner sign-off, and portability.
4. **Read the result.** The workbook calculates every dimension percentage, the certification percentage, the certification level, and whether the certification seal is active.
5. **Check fitness for each consumer.** On the Consumer Fit tab, enter what each consumer needs and see whether the product meets it.

## The eight dimensions

| # | Dimension | Weight | What it measures |
| --- | --- | --- | --- |
| 1 | **Data Quality** | 15% | Completeness, correctness and timeliness of the data, at the source and in the product. |
| 2 | **Semantic Coherence** | 15% | Whether every critical data element carries an approved meaning that agrees with the meaning used across the enterprise. |
| 3 | **Metadata Completeness** | 10% | Whether the product's contract, field descriptions, classifications and catalog entry are complete. |
| 4 | **Lineage Transparency** | 15% | Whether the data's origin and every transformation are traceable through to consumption. |
| 5 | **Security and Compliance** | 15% | Whether access, protection and regulatory obligations are built into the product. |
| 6 | **Governance** | 10% | Whether ownership, decision rights, change control and escalation are explicit and working. |
| 7 | **Performance** | 8% | Whether freshness, latency and availability meet the product's commitments, with monitoring in place. |
| 8 | **Accessibility and Interoperability** | 12% | Whether people and systems, including AI agents, can reach and use the product and join it to other foundational products. |

Each dimension is assessed through three criteria. Weights and the full scoring formula are documented in [SCORING_METHODOLOGY.md](./SCORING_METHODOLOGY.md).

## Certification levels

| Level | Certification percentage | Also required |
| --- | --- | --- |
| **Gold** · seal active | 80–100 | Tier 1 and Tier 2 checks complete; three-owner sign-off; Security and Compliance at 80 or above; Lineage Transparency, Governance and Semantic Coherence at 70 or above; portability condition met |
| **Silver** | 60–79 | Tier 1 and Tier 2 checks complete; Security and Compliance at 60 or above |
| **Bronze** | 40–59 | Tier 1 checks complete |
| **Registered** | 0–39 | The product is in the catalog with its passport and a visible trust profile |

The certification seal activates at Gold. Below Gold, the product stays registered, visible and usable wherever its dimension profile meets the consumer's need.

## Trust as transparency

Every certified product carries its trust profile in its passport: the certification percentage, the level, and the percentage for each of the eight dimensions.

A consumer reads the profile against its own purpose. An agent answering servicing questions may depend heavily on data quality and performance and little on lineage. An agent recommending credit decisions depends heavily on lineage and security. Both read the same product; each judges fitness for its own use.

The framework does not tell people to stop working. It shows them where the trust is.

A worked example is available in [EXAMPLE_OUTPUT.md](./EXAMPLE_OUTPUT.md).

## Where this fits in the methodology

- **Enterprise Identity Readiness Assessment (EIRA)** reads whether the enterprise has articulated its institutional logic clearly enough for AI. [Repository](https://github.com/AnnaJibga/enterprise-identity-readiness-assessment).
- **DSIL™ (Digital Substrate Identity Layer)** documents the enterprise's identity, including the information that becomes candidate Foundational Data Products™.
- **Progressive Certification** (this repository) measures and publishes the trust each Foundational Data Product™ has earned.
- **Passports** carry that trust to every consumer, and AI agents inherit what they need from the passports of the products they consume.

Related artifacts, including the Foundational Data Product Domain Map, are available in the [toolkit](https://foundationaldataproducts.com/toolkit).

## What this framework is not

- **Not a one-time audit.** Scores are meant to be refreshed as data, systems and obligations change. A certification is a current reading. A reading past its re-scoring date shows as expired, and the seal is suspended until the product is re-scored.
- **Not a tool selection.** The framework is tool-agnostic. Any platform can implement the measurements.
- **Not an enterprise readiness assessment.** It certifies individual data products. EIRA covers institutional readiness.
- **Not a substitute for regulatory review.** It organizes evidence; it does not replace legal or compliance judgment.

## Citing this framework

A formal citation file is provided ([CITATION.cff](./CITATION.cff)). GitHub renders this as a "Cite this repository" button.

Suggested citation:
> Jibgashvili, A. (2026). *Foundational Data Product™ Progressive Certification* (v1.1). Foundeon. <https://foundeon.com>

## License

This work is licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](./LICENSE.md).

In plain language: you may share this framework with attribution. You may use it internally as-is. You may not use it for commercial purposes without permission, and you may not distribute modified versions. For commercial licensing or advisory engagement, contact `anna@foundeon.com`.

## Canonical references

- **Methodology home:** [foundeon.com](https://foundeon.com)
- **Toolkit:** [foundationaldataproducts.com/toolkit](https://foundationaldataproducts.com/toolkit)
- **Methodology writing:** [Trust Is Not a Gate. It Is a Signal That Must Travel.](https://annajibgashvili.substack.com/p/coming-soon) on Substack
- **Author:** [Anna Jibgashvili on LinkedIn](https://www.linkedin.com/in/annajibgashvili/)

## Contact

For consultation on certifying Foundational Data Products™, designing passports, or commercial licensing of this framework: `anna@foundeon.com`

---

*© 2026 Anna Jibgashvili | Foundeon | Foundational Data Products™*
