# COVID-19 Detection from Chest X-Ray Images using InceptionV3

## Overview
This repository contains an academic project that classifies chest X-ray images
as COVID-19 or Non-COVID using transfer learning with the InceptionV3 architecture.

This was a **team project** completed as part of the MA 305 – Data Science course under the guidance of Prof. M. Tanveer at IIT Indore.

---

## Dataset
The dataset used is the **COVID-19 Chest X-ray Dataset**, publicly available at:
https://github.com/ieee8023/covid-chestxray-dataset

The dataset is **not included** in this repository due to its large size.

---

## Model & Approach
- Architecture: **InceptionV3** (pretrained on ImageNet)
- Technique: **Transfer Learning**
- Input size: 299 × 299 (RGB images)
- Binary classification: COVID-19 / Non-COVID
- Multi-phase fine-tuning strategy
- Test-Time Augmentation (TTA) for stable predictions

---

## Results
- Test Accuracy: **88.54%**
- Recall: **0.8854**
- AUC: **0.9696**

---

## Repository Contents
- `MA_305_Project.ipynb` -> Complete implementation (training, evaluation, plots)
- `MA_305_Project_Report.pdf` -> Detailed project report
- `Reproducibility_and_Instructions.pdf` -> Environment setup & execution steps

---

## How to Run
1. Open the Jupyter notebook (`MA_305_Project.ipynb`) in **Google Colab**
2. Set runtime to **GPU**
3. Run all cells sequentially
4. The notebook will automatically:
   - Clone the dataset
   - Preprocess images
   - Train the model
   - Evaluate performance

---

## Notes
This project focuses on the practical application of deep learning techniques using
existing architectures and standard libraries, rather than on developing new models
or theoretical methods.

---

## Team Members
- Anmol Jain
- Nidarsana M
- Salaj Bansal

