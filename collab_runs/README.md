# Colab Experiments (A100 GPU)

This directory contains Google Colab-based experimental runs for replicating and adapting the methods in the `llm-adaptive-attacks` repository.

## Environment
- **Platform:** Google Colab Pro
- **GPU:** NVIDIA A100
- **Dependencies:** Installed via `requirements.txt` from the root directory

## Contents
- `run_llama2_best_prompt.ipynb`: Example attack run using `llama2-13b` with the `refined_best` prompt template.
- `output_logs/`: Logs and outputs generated from each Colab run.
- `wandb_configs/`: W&B offline configurations for local experimentation.

## Notes
- All runs utilize HuggingFace-hosted models and external judge APIs (OpenAI GPT-4) where applicable.
- Offline tracking is used for reproducibility (`WANDB_MODE=offline`).