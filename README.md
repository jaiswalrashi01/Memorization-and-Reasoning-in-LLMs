# Memorization-and-Reasoning-in-LLMs
Investigate memorization and reasoning abilities of LLMs 

Part 1: MEM_RSN_LLM_11Jun25_16Aug25
This Colab notebook documents the full workflow for reproducing the “On Memorization of Large Language Models in Logical Reasoning” setup. It includes data generation using data_gen_kk and prompt_kk to build perturbed Knight–Knave puzzle datasets. Both Direct and Chain-of-Thought (CoT) fine-tuning pipelines are implemented on the Phi-3 model family. Adapter weights are then merged into standalone models for each task size (n=2–8). The notebook serves as a reproducible pipeline from dataset creation through fine-tuned reasoning model checkpoints.
