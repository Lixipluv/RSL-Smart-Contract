# Replication Package

## Artificial Intelligence for Security Analysis of Smart Contracts: A Systematic Review

**Authors:** Lívia Carrera; Raquel C. G. Pinto; Anderson Fernandes Pereira dos Santos  
**Affiliation:** Instituto Militar de Engenharia (IME), Rio de Janeiro, Brazil  
**Venue:** WebMedia 2026  
**Paper DOI:** Not assigned/provided

## Purpose

This package consolidates the reproducibility artifacts available from the supplied manuscript, the P1–P93 extraction matrix, and the supplied bibliography source. It distinguishes **documented evidence** from data that still requires an original Parsifal/database export. No missing screening decision, quality score, search date, database-specific query, or inter-rater result has been fabricated.

## PRISMA counts

| Stage | Count |
|---|---:|
| Records identified | 1,903 |
| Duplicates removed | 187 |
| Records screened | 1,716 |
| Records excluded at title/abstract | 1,605 |
| Full texts assessed | 111 |
| Full texts excluded | 18 |
| Included primary studies | 93 |

Full-text exclusion reasons: 9 not AI for smart-contract security; 5 below the quality cut-off; 4 non-security/price-prediction.

## What is fully populated

- Canonical search string and reported post-quantum auxiliary query.
- Selection and quality-assessment criteria.
- PRISMA aggregate counts.
- Complete P1–P93 catalogue with title, year, venue, DOI, detection approach, predominant algorithm, reported metrics, platform, and AI generation.
- Included-studies screening subset (P1–P93).
- Supplied bibliography source.

## What still requires the original Parsifal/database exports

- Exact IEEE/ACM/Springer execution dates and database-specific query variants.
- Raw per-database search exports and per-database counts.
- The 1,903 record-level identification sheet, duplicate mapping, and 1,716 title/abstract decisions.
- The 111 record-level full-text decisions, including identities of the 18 excluded reports.
- Individual five-item quality-assessment scores.
- Extraction fields not present in the supplied P1–P93 matrix (vulnerability classes, input representation, quantum aspects, artifact/dataset availability).
- Inter-rater results (not conducted in the supplied manuscript).
- Scopus, Web of Science, and SOL supplementary-search results (not supplied/performed in the provided artifacts).

See `DATA_GAPS.md` for the exact completion checklist.

## Directory structure

```text
01_search_strategy/
02_search_results/
03_screening/
04_quality_assessment/
05_data_extraction/
06_inter_rater/
07_supplementary_searches/
08_figures/
09_bibliography_source.bib
DATA_GAPS.md
README.md
```

## Quality assessment

Five questions are scored Yes = 1.0, Partially = 0.5, No = 0.0. Maximum score = 5.0; inclusion cut-off = 3.0. The exact criteria are in `04_quality_assessment/QA_criteria.md`.

## License and copyright

This package contains bibliographic metadata and review-derived tabulations only. Copyrighted full-text publications are not redistributed. Before public release, select an appropriate license for the review data and repository documentation.
