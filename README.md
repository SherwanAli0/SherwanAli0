# Hi, I'm Sherwan Ali

Python developer building reliable AI and data systems, with projects in automation, reproducible ML, and LLM evaluation.

## Main projects

| Project | What it is |
|---|---|
| [job-intelligence-pipeline](https://github.com/SherwanAli0/job-intelligence-pipeline) | A daily job-search pipeline: it collects postings from company job boards and public job APIs, filters them, ranks them with an LLM, and emails a digest. Runs on AWS Fargate, with a regression test suite and a scoring-calibration check. |
| [csrboost-audit](https://github.com/SherwanAli0/csrboost-audit) | My undergraduate thesis: an independent reproducibility study of a published imbalanced-classification method (CSRBoost, IEEE Access 2025) across 15 datasets and 10 algorithms. It documents what reproduces under one protocol and what does not. |
| [HalluScope](https://github.com/SherwanAli0/HalluScope) | A five-author replication of an entropy-based sentence-level hallucination score for large language models (IEEE BigComp 2025). |
| [Recommender-System-Paper-Replication](https://github.com/SherwanAli0/Recommender-System-Paper-Replication) | A four-author replication of a fuzzy-signature recommender system (IEEE Access 2026) on MovieLens 100k. |

## Related to the audit

After the audit I explored an experimental ensemble extension of CSRBoost, an unpublished research prototype, and built a small web app around it.

- [ERF-CSRBoost](https://github.com/SherwanAli0/erf-csrboost): the extension's code and documented evaluation, kept separate from the audit. The audit's results do not include it. Its November evaluation adds 2,000 verified fits on five tasks; combined with 15 historical tasks, ERF has higher mean AP than reimplemented CSRBoost on 16/20. Ordinary-forest comparisons are mixed and compute cost is higher. [Results and limits](https://github.com/SherwanAli0/erf-csrboost/tree/main/research/results/november2026_aligned_extension).
- [FixYourDataset](https://fixyourdataset.fly.dev): a web app for examining class imbalance and comparing model behavior on your own data.

## Also public

Course projects from the IBM AI Engineering Professional Certificate: rainfall prediction, waste classification, aircraft damage detection, plus small data-mining exercises.

## What I care about

Checking that results actually reproduce, writing down what was and was not verified, and keeping code tested.
