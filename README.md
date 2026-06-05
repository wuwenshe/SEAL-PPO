# SEAL-PPO: Segment-Level Rewards with Adaptive Length Penalties for Language Model Alignment

## 📌 Overview
This repository provides the implementation of **SEAL-PPO**, an advanced alignment method that introduces entropy-guided segments for denser credit assignment and adaptive length penalties to reduce reward-seeking verbosity in LLMs.

## 📂 Dataset
Our PPO training is based on the open-source **UltraFeedback** dataset. Specifically, we utilize the `ultrafeedback-binarized-preferences-cleaned` version curated by Argilla. 
To ensure strict reproducibility of the experiments reported in our paper, we have uploaded the exact **2,000 randomly sampled instructions** used for our core PPO training phase.
- **Training Data:** [`data/ultrafeedback_2k_ppo_train.json`](./data/ultrafeedback_2k_ppo_train.json)
- **Original Source:** [Argilla/ultrafeedback-binarized-preferences-cleaned on Hugging Face](https://huggingface.co/datasets/argilla/ultrafeedback-binarized-preferences-cleaned)

## 🚀 Code Release Plan
Currently, this repository is under preparation for peer review. The complete PPO distributed training pipeline (integrated with DeepSpeed and vLLM) and automated evaluation scripts for AlpacaEval 2.0 / Arena-Hard will be fully open-sourced immediately upon paper acceptance.
