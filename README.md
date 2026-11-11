# Hi, I'm Sherwan Ali

Python developer building reliable AI and data systems, with projects in automation, reproducible ML, and LLM evaluation.

## Main projects

| Project | What it is |
|---|---|
| [FixYourDataset](https://fixyourdataset.fly.dev/?utm_source=github&utm_medium=referral&utm_campaign=portfolio&utm_content=readme) | An evaluation workbench for imbalanced classification: a reusable Python package, validation-selected policies, bounded private jobs and downloadable evidence. [Source and engineering case study](https://github.com/SherwanAli0/erf-csrboost). |
| [job-intelligence-pipeline](https://github.com/SherwanAli0/job-intelligence-pipeline) | A daily job-search pipeline: it collects postings from company job boards and public job APIs, filters them, matches each requirement to cited profile evidence with BM25 retrieval (RAG), ranks them with an LLM, and emails a digest. Runs on AWS Fargate, with a regression test suite and a scoring-calibration check. |
| [csrboost-audit](https://github.com/SherwanAli0/csrboost-audit) | My undergraduate thesis: a reproducibility study, carried out independently of the CSRBoost authors, of a published imbalanced-classification method (CSRBoost, IEEE Access 2025) across 15 datasets and 10 algorithms. It documents what reproduces under one protocol and what does not. |
| [HalluScope](https://github.com/SherwanAli0/HalluScope) | A five-author replication of an entropy-based sentence-level hallucination score for large language models (IEEE BigComp 2025). |
| [Recommender-System-Paper-Replication](https://github.com/SherwanAli0/Recommender-System-Paper-Replication) | A four-author replication of a fuzzy-signature recommender system (IEEE Access 2026) on MovieLens 100k. |

## Related to the audit

After the audit I built ERF-CSRBoost, an experimental ensemble extension of CSRBoost (not peer reviewed), and the FixYourDataset evaluation workbench.

- [ERF-CSRBoost](https://github.com/SherwanAli0/erf-csrboost): a resampled forest extension of CSRBoost, kept separate from the audit.
  - Across 20 datasets ERF exceeds a reimplemented CSRBoost on 16 (+0.0685 mean AP; lower on 4) and is within 0.001 mean AP of a plain random forest (higher on 12 datasets, tied on 2, lower on 6).
  - All 2,000 new fits completed with zero failures, and every table of the November record is covered by a SHA-256 manifest and a read-only checker.
  - Scope: counts of datasets, not significance tests; the near-tie with a plain random forest does not show equivalence; the gain over CSRBoost is concentrated in four datasets. [Results and limits](https://github.com/SherwanAli0/erf-csrboost/tree/main/research/results/november2026_aligned_extension).
- [FixYourDataset](https://fixyourdataset.fly.dev/?utm_source=github&utm_medium=referral&utm_campaign=portfolio&utm_content=readme): compare explicit model recipes on held-out data, evaluate saved predictions in the browser and export reports. The application procedure is separate from the historical research tables.

## Also public

Course projects from the IBM AI Engineering Professional Certificate: rainfall prediction, waste classification, aircraft damage detection, plus small data-mining exercises.

## What I care about

Checking that results actually reproduce, writing down what was and was not verified, and keeping code tested.
