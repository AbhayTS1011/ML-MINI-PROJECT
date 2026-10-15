# QuickDraw Machine Learning Mini-Project

UE24CS352A Machine Learning Mini-Project

## Overview
This repository contains the source code, dataset, write-up, and presentation for the Machine Learning mini-project. The objective is to classify $28 \times 28$ grayscale hand-drawn sketches from Google's **Quick, Draw!** dataset into three classes: **banana**, **hockey stick**, and **mosquito**. We compare classical machine learning models (Logistic Regression and SVMs with four different kernels) against a Convolutional Neural Network (CNN).

## Project Structure
```
.
├── PROJECT/
│   ├── CODE/
│   │   └── QuickDraw_Mini_Project_Submission.ipynb  # Self-contained Jupyter notebook
│   └── DATA/
│       ├── banana.npy
│       ├── hockey_stick.npy
│       └── mosquito.npy
├── QuickDraw_Mini_Project_Writeup.pdf             # Two-page project write-up
├── QuickDraw_Mini_Project_Presentation.pptx         # Presentation slide deck
└── Guidelines and Instructions_Mini Project Assignment.pdf
```

## Requirements & Dependencies
- Python 3.8+
- NumPy
- Pandas
- Scikit-learn
- PyTorch
- Matplotlib

Install dependencies via pip:
```bash
pip install numpy pandas scikit-learn torch matplotlib
```

## How to Run
1. Open Jupyter Notebook or Jupyter Lab:
   ```bash
   jupyter notebook
   ```
   or open `PROJECT/CODE/QuickDraw_Mini_Project_Submission.ipynb` in Google Colab.
2. Ensure `banana.npy`, `hockey_stick.npy`, and `mosquito.npy` are placed in the working directory (or `PROJECT/DATA/` as configured in the notebook).
3. Run all cells sequentially to load data, preprocess, train models (Logistic Regression, SVM kernels, CNN), evaluate on the held-out test split, and generate confusion matrices and metrics.
