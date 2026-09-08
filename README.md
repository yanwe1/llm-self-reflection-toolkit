# LLM Referral Toolkit

A toolkit for detecting psychological/mental wellbeing signals in longitudinal AI chatbot conversation logs.

## Data handling

Code and config only — **no participant data in this repo.** All participant data lives in Cornell Box only.


## Basic Structure: open notebooks below for more detailed structural info

* `01_llm_prep_logs.ipynb`: Preprocessing, PII redaction, Box upload
* `02_llm_compute_metrics_meta.ipynb`:   Signal scoring
* `03_llm_visualize_measures.ipynb`:     Visualization and trajectory analysis
* `config/`:                             Signal definitions and method mapping
