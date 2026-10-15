# learned-hybrid-summary-evaluation
Implementation of a Learned Hybrid metric for reference-based evaluation of AI-generated text summaries
# Learned Hybrid Metric for Reference-Based Evaluation of AI-Generated Summaries

This repository contains the REALSumm experiment for the research project:

**A Learned Hybrid Metric for Reference-Based Evaluation of AI-Generated Text Summaries**

The study investigates whether lexical, semantic, NLI-derived factuality, and structural features can be combined into a learned evaluation metric that aligns more strongly with human summary-quality judgments.

## REALSumm Experiment

The notebook includes:

- REALSumm dataset preparation and validation
- document-grouped development and locked holdout splitting
- structural feature extraction
- NLI-derived factuality features
- individual automatic-metric baselines
- fixed-weight Manual Hybrid evaluation
- Learned Hybrid model comparison and selection
- feature-family ablation
- locked holdout evaluation
- document-level bootstrap confidence intervals
- system-level evaluation
- error analysis
- within-document pairwise ranking evaluation
- final frozen model specification

## Notebook

- `REALSumm_GitHub.ipynb` — complete REALSumm experimental workflow

## Dataset

The REALSumm dataset file is not currently included in this repository.

The notebook expects:

```text
REALSumm_data.csv
