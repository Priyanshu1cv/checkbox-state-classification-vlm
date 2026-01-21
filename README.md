# Checkbox State Classification using Vision-Language Models

This repository contains the assignment submission for the AI Engineer Intern (R&D) role.

## Problem Statement
The objective is to classify the state of a checkbox from an image into:
- Checked
- Unchecked
- Ambiguous

## Overall Approach
- Synthetic dataset generation for checkbox images
- Instruction-based multimodal inference
- Vision-Language Model (Qwen2-VL)
- Proper image–text alignment using chat templates

## Training Setup
Full fine-tuning was planned; however, due to hardware constraints in a CPU-only environment, the project focuses on:
- Dataset preparation
- Model configuration
- Instruction-based inference
- Evaluation and analysis

## Model Used
- Qwen2-VL-2B-Instruct (Open-source Vision-Language Model)

## Repository Contents
- `short_report.pdf` – 1–2 page project report
- `Checkbox_Classification.ipynb` – Training and inference notebook
- `data/` – Synthetic train and test datasets
- `inference_demo.py` – Simple inference script (optional)

## Results
- Correct classification of clear checked and unchecked cases
- Reasonable handling of ambiguous cases
- Improved stability using instruction-based prompts

## Notes
This project emphasizes correctness, reproducibility, and understanding of multimodal AI systems rather than heavy training.
