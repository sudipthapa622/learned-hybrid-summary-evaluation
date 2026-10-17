# Learned Hybrid Metric for Reference-Based Evaluation of AI-Generated Summaries

This repository contains the implementation developed for the research project:

**A Learned Hybrid Metric for Reference-Based Evaluation of AI-Generated Text Summaries**

The study investigates whether lexical, semantic, NLI-derived factuality, and structural features can be combined into a Learned Hybrid evaluation metric that aligns more strongly with human judgments of summary quality and content coverage.

## Experiments

The repository contains implementations for two human-annotated summarisation benchmarks:

### REALSumm

The REALSumm experiment includes:

- dataset preparation and validation
- document-grouped development and locked holdout splitting
- structural feature extraction
- NLI-derived factuality features
- individual automatic-metric baselines
- fixed-weight Manual Hybrid metric
- Learned Hybrid model comparison
- feature-family ablation
- locked holdout evaluation
- document-level bootstrap confidence intervals
- system-level evaluation
- error analysis
- within-document pairwise ranking evaluation
- final frozen model specification

### RoSE

The RoSE CNN/DailyMail experiment includes:

- RoSE dataset preparation and standardisation
- document-grouped development and locked holdout splitting
- structural feature extraction
- ROUGE-L, BERTScore F1, and MoverScore baselines
- source-grounded NLI factuality features
- fixed-weight Manual Hybrid metric
- leakage-safe Learned Hybrid model comparison
- locked holdout evaluation
- pairwise ranking evaluation
- document-level bootstrap confidence intervals
- paired significance testing
- calibration and agreement analysis
- feature-family ablation
- summary-level and system-level evaluation
- final frozen model specification

## Notebooks

- `REALSumm_GitHub.ipynb` — REALSumm experimental implementation
- `RoSE_GitHub.ipynb` — RoSE CNN/DailyMail experimental implementation

## Requirements

Python dependencies used by the experiments are listed in:

`requirements.txt`

## Datasets

The datasets are not redistributed as part of this repository.

The notebooks document the dataset preparation and loading procedures used for the experiments.

## Research Status

This repository accompanies a Master by Research thesis and provides the implementation notebooks used to document the experimental workflow and support inspection and reproducibility of the study.
