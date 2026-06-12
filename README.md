# Constellations Dataset and VLM-CNN Evaluation and Comparison

A comprehensive Machine Learning project that involves creating a custom dataset, training two Convolutional Neural Networks (CNNs) from scratch, and fine-tuning a Vision-Language Model (VLM).

> **📄 Full Documentation:** For the mathematical background, detailed methodology, and all experiments, please **[read the full Report (46 pages) here](Research_Project.pdf)**.

---

## Project Overview

The project is divided into three main stages:
1. **Dataset Generation:** 
2. **CNN Training:** 
3. **VLM Fine-tuning:** 

## Tech Stack & Tools

* **Data Engineering:** MATLAB
* **Deep Learning Frameworks:** [PyTorch, Transformers, PEFT]
* **Execution Environment:** Google Colab

---

## 📂 Repository Structure

\`\`\`text
├── constellation_dataset.mlx       
├── sep.mlx       
├── 01_cnn_training.ipynb        
├── 02_vlm_finetuning.ipynb      
├── report.pdf                   
├── requirements.txt             
└── README.md
\`\`\`

---

## Reproduction

To run the project locally or in your own environment, follow this sequence:

1. **Data Generation:** Open MATLAB and run the `.mlx` script(s) to generate the dataset. (Refer to the report for the exact parameter settings).
2. **Train CNNs:** Open `01_cnn_training.ipynb` in Google Colab. Load the dataset generated in the previous step and run the cells.
3. **Fine-tune VLM:** Open `02_vlm_finetuning.ipynb` in Google Colab and follow the instructions within the notebook.

---
