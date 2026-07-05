# PEFT for AI-Generated Image Detection: LN-tuning vs. LoRA

**Area:** Computer Vision · Parameter-Efficient Fine-Tuning (PEFT)
**Type:** Course Project — Computer Vision (Year 3)
**Status:** Completed

> ⬅️ [Back to portfolio home](../../README.md)

---

## Overview
A comparative study of **parameter-efficient fine-tuning (PEFT)** methods — specifically **LN-tuning vs. LoRA** — for the task of **detecting AI-generated images**.

## Problem
Fully fine-tuning large vision models to detect AI-generated images is costly; PEFT promises comparable accuracy at a fraction of the trainable parameters, but the trade-offs between methods on this task are unclear. *[Add specific problem framing.]*

## Method
- Fine-tune a pretrained vision backbone for real-vs-AI-generated classification.
- Compare **LN-tuning** (tuning normalization-layer parameters) and **LoRA** (low-rank adapters).
- *[Add backbone architecture, PEFT configuration — rank, target layers, trainable-parameter counts.]*

## Dataset
- *[Add dataset name / source — real vs. AI-generated images]*
- *[Add dataset description — size, generators covered, splits]*
- *[Add preprocessing / augmentation]*

## Experiments
- Compare LN-tuning vs. LoRA (and *[Add: full fine-tuning / other baselines]*).
- *[Add evaluation metrics — accuracy / F1 / AUC]*
- *[Add efficiency comparison — trainable params, training time]*

## Results
- *[Add result — accuracy comparison LN-tuning vs. LoRA]*
- *[Add result — efficiency comparison]*
- *[Add figure]*

## My Contribution
- *[Add your specific role]*
- *[Add collaborators if any]*

## Tech Stack
- Python, PyTorch *[Verify]*
- Hugging Face `transformers` / `peft` *[Verify]*

## Files
- *[Add code / notebook links]*
- *[Add report / slides link]*
- *[Add figures in ../../assets/figures/]*

## Notes
- *[Add limitations and future directions]*
