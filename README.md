# Kévin Boutillier

**Research engineer · semantic web · authority metadata · regulatory knowledge graphs**

Co-founder @ [Verisav](https://www.verisav.fr) & [Daremeet](https://www.daremeet.com) · Bordeaux, France  
[ORCID](https://orcid.org/0009-0001-0356-4421) · [Website](https://www.kevinboutillier.com/) · [LinkedIn](https://www.linkedin.com/in/k%C3%A9vinboutillier)

[![ORCID](https://img.shields.io/badge/ORCID-0009--0001--0356--4421-green?logo=orcid&logoColor=white)](https://orcid.org/0009-0001-0356-4421)
[![LOV](https://img.shields.io/badge/LOV-validated-brightgreen)](https://lov.linkeddata.es/dataset/lov/agents/Verisav)
[![W3ID](https://img.shields.io/badge/W3ID-persistent%20URI-blue)](https://w3id.org/verisav)
[![DOI](https://img.shields.io/badge/Zenodo-10.5281%2Fzenodo.18016853-blue)](https://doi.org/10.5281/zenodo.18016853)
[![Schema.org](https://img.shields.io/badge/Schema.org-contributor-0066CC)](https://github.com/schemaorg/schemaorg/pull/4663)

> I work on **machine-readable identity and product metadata** — how authority records, linked data, and LLM-generated citations can be modeled, validated, and evaluated with reproducible protocols rather than anecdote.

---

## Research focus

| Line | Core question | Approach |
|------|---------------|----------|
| **Authority metadata & KG pipelines** | How can federated person metadata be reconciled across autonomous registries with auditable provenance? | Evidence-typed assertions, deterministic crosswalks, SHACL gates, replayable manifests |
| **Regulatory semantic resources** | How should EU Digital Product Passport data be expressed as FAIR, interoperable RDF/OWL? | LOV-validated vocabularies, W3ID namespaces, SHACL + JSON Schema, GS1 / UNTP alignment |
| **LLM citation reliability** | When models cite authority identifiers, are IDs valid, resolvable, and entity-consistent? | Deterministic benchmark, explicit failure taxonomy, per-model breakdown |

---

## Reproducible artifacts

| Repository | Description |
|------------|-------------|
| [**hn-llm-authority-audit**](https://github.com/kevinbouti/hn-llm-authority-audit) | Runnable benchmark for LLM authority-reference reliability — metrics, error classes, CSV outputs |
| [**NDL-authority-dossier-public**](https://github.com/kevinbouti/NDL-authority-dossier-public) | Public technical dossier on authority-data interoperability (National Diet Library correspondence) |
| [**Verisav/vocabularies**](https://github.com/Verisav/vocabularies) | Open RDF/OWL vocabularies (**DPP · RMA · WTY**) — ESPR-aligned, LOV · W3ID · SHACL |
| [**Verisav/gs1-dpp-utils**](https://github.com/Verisav/gs1-dpp-utils) | GTIN / GLN / GS1 Digital Link validation for DPP implementers (zero deps, production-tested) |
| [**Verisav/dpp-verifiable-credentials**](https://github.com/Verisav/dpp-verifiable-credentials) | Issue & verify W3C Verifiable Credentials for Digital Product Passports |
| [**Verisav/graphql-rdf-vocabularies**](https://github.com/Verisav/graphql-rdf-vocabularies) | GraphQL layer over RDF/OWL vocabularies |

All artifacts aim for **inspectable data, deterministic evaluation, and citable releases** (Zenodo DOI where applicable).

---

## Semantic resources (DPP · RMA · WTY)

Three complementary RDF/OWL vocabularies for after-sales and EU Digital Product Passport interoperability:

| Vocab | Role | Namespace |
|-------|------|-----------|
| **DPP** | Product passport · ESPR · traceability · VC-ready | `https://w3id.org/verisav/dpp#` |
| **RMA** | Returns & service tickets | `https://w3id.org/verisav/rma#` |
| **WTY** | Machine-readable warranties | `https://w3id.org/verisav/wty#` |

**Live publication:** [ns.verisav.fr](https://ns.verisav.fr/) · **Registry:** [LOV / Verisav](https://lov.linkeddata.es/dataset/lov/agents/Verisav) · **Archive:** [doi.org/10.5281/zenodo.18016853](https://doi.org/10.5281/zenodo.18016853)

```bibtex
@dataset{boutillier2026verisav,
  author       = {Boutillier, K{\'e}vin},
  title        = {Verisav Semantic Vocabularies: DPP, RMA, WTY},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.18016853},
  url          = {https://doi.org/10.5281/zenodo.18016853}
}
```

---

## Upstream open source

| Project | Contribution | Status |
|---------|--------------|--------|
| [**Schema.org**](https://schema.org) | [PR #4663](https://github.com/schemaorg/schemaorg/pull/4663) — Product & SoftwareApplication examples | **Merged** |
| [**react.dev**](https://react.dev) | [PR #8342](https://github.com/reactjs/react.dev/pull/8342) — props reference formatting | Open |
| [**Next.js**](https://nextjs.org) | [PR #91055](https://github.com/vercel/next.js/pull/91055) — Contributing docs wording | Open |
| [**w3id.org**](https://w3id.org) | Persistent URI redirects for Verisav namespaces | [PR](https://github.com/perma-id/w3id.org) (community) |

---

## npm libraries

[@verisav/gs1-dpp-utils](https://www.npmjs.com/package/@verisav/gs1-dpp-utils) · [@verisav/dpp-verifiable-credentials](https://www.npmjs.com/package/@verisav/dpp-verifiable-credentials) · [@verisav/graphql-rdf-vocabularies](https://www.npmjs.com/package/@verisav/graphql-rdf-vocabularies)

---

## Industry applications

| | |
|---|---|
| **[Verisav](https://www.verisav.fr)** | B2B2C after-sales & warranty platform — DPP-ready (ESPR EU 2024/1781) |
| **[Daremeet](https://www.daremeet.com)** | Real-world meetups via challenges & map (iOS / Android) |

Research outputs inform production systems; production constraints inform the research agenda.

---

## Methods & stack

`RDF/OWL` · `JSON-LD` · `SHACL` · `GraphQL` · `Schema.org` · `W3C VC` · `Python` · `TypeScript` · `Next.js` · `Supabase`

---

## Identity & contact

- **Email (research & standards):** k.boutillier@verisav.fr
- **ORCID:** [0009-0001-0356-4421](https://orcid.org/0009-0001-0356-4421)
- **Keyoxide:** [D25C29F4786871D16AD0927CCB9AC163A71E1C95](https://keyoxide.org/D25C29F4786871D16AD0927CCB9AC163A71E1C95)
- **Founder profile:** [verisav.fr/en/founders/kevin-boutillier](https://www.verisav.fr/en/founders/kevin-boutillier)

---

*Pinned repositories reflect the research artifacts above — not upstream forks.*
