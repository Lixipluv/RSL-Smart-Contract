````markdown
# RSL Smart Contract

This repository contains the replication package for a **Systematic Literature Review (SLR)** on **smart contract security**, with emphasis on vulnerability detection approaches, analysis techniques, algorithms, evaluation metrics, and emerging research trends.

The repository was created to improve the **transparency, reproducibility, and traceability** of the review process by making the supporting datasets and research artifacts publicly available.

## Research Scope

The review investigates the evolution of smart contract security research and organizes the selected studies according to their main characteristics.

The analysis includes:

- Smart contract vulnerability detection approaches;
- Static, dynamic, symbolic, formal, and hybrid analysis techniques;
- Machine learning and deep learning methods;
- Blockchain and EVM-based security analysis;
- Vulnerability categories and attack classes;
- Detection algorithms and tools;
- Evaluation datasets;
- Performance and security metrics;
- Emerging approaches involving artificial intelligence and quantum computing;
- Research gaps and future directions.

## Systematic Review Process

The study selection follows a structured systematic review protocol inspired by the **PRISMA methodology**.

The review process includes the following phases:

1. Definition of research questions;
2. Definition of search strings;
3. Selection of digital libraries;
4. Identification of candidate studies;
5. Removal of duplicate studies;
6. Title and abstract screening;
7. Full-text eligibility assessment;
8. Application of inclusion and exclusion criteria;
9. Data extraction;
10. Study classification;
11. Quantitative and qualitative synthesis.

## Repository Structure

The repository is organized to contain the main artifacts produced during the systematic review.

```text
RSL-Smart-Contract/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── final/
│
├── studies/
│   ├── included/
│   └── excluded/
│
├── prisma/
│   └── selection-process/
│
├── classification/
│   ├── approaches/
│   ├── algorithms/
│   ├── vulnerabilities/
│   └── metrics/
│
├── figures/
│
├── tables/
│
├── scripts/
│
├── LICENSE
└── README.md
````

The directory structure may evolve as additional replication artifacts are added.

## Data Available

The replication package may include:

* Initial search results;
* Duplicate-removal records;
* Selected and excluded studies;
* Inclusion and exclusion decisions;
* Study metadata;
* Publication year;
* Publication venue;
* Blockchain platform;
* Smart contract language;
* Vulnerability categories;
* Security analysis techniques;
* Detection approaches;
* Algorithms;
* Tools and frameworks;
* Datasets;
* Evaluation metrics;
* Experimental results;
* Classification tables used in the manuscript.

## Study Classification

The selected studies are categorized according to dimensions such as:

| Dimension         | Examples                                                   |
| ----------------- | ---------------------------------------------------------- |
| Analysis Approach | Static, Dynamic, Symbolic, Formal, Hybrid                  |
| Detection Method  | Rule-based, ML, DL, GNN, LLM                               |
| Target            | Source Code, Bytecode, Transaction, Execution Trace        |
| Blockchain        | Ethereum, EVM-compatible, Other                            |
| Vulnerability     | Reentrancy, Access Control, Arithmetic, DoS, Front-running |
| Evaluation        | Accuracy, Precision, Recall, F1-score, PR-AUC              |
| Artifact          | Dataset, Tool, Framework, Model                            |

The exact classification follows the taxonomy defined in the associated manuscript.

## Reproducibility

The purpose of this repository is to allow researchers to inspect the evidence supporting the conclusions presented in the systematic review.

The available artifacts can be used to:

* Verify study-selection decisions;
* Reproduce quantitative analyses;
* Inspect the classification taxonomy;
* Recreate tables and figures;
* Compare security techniques;
* Extend the review with future publications;
* Conduct secondary analyses using the extracted dataset.

## Citation

If you use the dataset, classifications, or other materials from this repository, please cite the corresponding paper.

```bibtex
@article{carrera2026smartcontract,
  author  = {Lívia Carrera and others},
  title   = {Systematic Literature Review on Smart Contract Security},
  year    = {2026},
  note    = {Manuscript citation information will be updated after publication}
}
```

The BibTeX entry will be updated when the final publication metadata becomes available.

## Replication Package

The complete replication package is available at:

**GitHub:**
https://github.com/Lixipluv/RSL-Smart-Contract

## Research Use

This repository is intended primarily for academic and research purposes.

Researchers are encouraged to:

* Reuse the classification framework;
* Extend the dataset;
* Replicate the analysis;
* Compare new smart contract security approaches with the reviewed literature;
* Report inconsistencies or missing studies through GitHub Issues.

## Contributions

Suggestions, corrections, and improvements are welcome.

If you identify:

* A missing relevant study;
* An incorrect classification;
* A duplicated publication;
* An inconsistent metadata entry;
* A problem with the replication artifacts;

please open an **Issue** describing the proposed correction.

## License

A license will be specified for the repository to define the permitted use and redistribution of the dataset and supporting artifacts.

For academic reuse, please provide proper attribution to the authors and associated publication.

## Author

**Lívia Carrera**

Research areas:

* Smart Contract Security
* Blockchain Security
* Application Security
* Vulnerability Detection
* Artificial Intelligence for Cybersecurity
* Quantum Computing

GitHub: [@Lixipluv](https://github.com/Lixipluv)

---

If you use this repository in academic work, please cite the associated publication and reference this replication package.

```
```
