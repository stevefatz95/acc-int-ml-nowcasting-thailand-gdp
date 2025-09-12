# Why Both Accuracy and Interpretability Matter: Machine Learning for Nowcasting Thai GDP

Pseudo real-time framework for GDP nowcasting in Thailand using machine learning, with a focus on accuracy and interpretability.

---

## Repository Structure

├── README.md
├── requirements.txt
├── data-collection/
│ ├── data/ # Datasets used for data collection
│ └── data-collection-thai-gdp-nowcasting.ipynb
├── preprocessing/
│ ├── data/ # Datasets after preprocessing
│ └── data-preprocessing-nowcasting-thai-gdp.ipynb
├── modelling/
│ ├── data/ # Datasets used for modelling
│ └── modelling-nowcasting-thai-gdp-dec.ipynb
│ └── modelling-nowcasting-thai-gdp-jan.ipynb
├── evaluation/
  ├── data/ # Datasets used for evaluation
  └── evaluation-nowcasting-thai-gdp.ipynb


---

## Overview

This repository implements a **pseudo real-time nowcasting framework** for Thailand’s GDP using machine learning. It emphasizes the **importance of both accuracy and interpretability** in policy-making contexts.  

Key features:

- **Knowledge-Embedded Nowcasting (KEN):** A method for variable selection ensuring economic interpretability and reduced bias.
- **Level of Alignment in Interpretative Signals (LAIS):** A human-centered approach to evaluating model interpretability.
- Comparison of **traditional econometric methods** and **machine learning algorithms** (e.g., SVR, kNN, RNN).

---

## Requirements

Install the necessary Python packages:

```bash
pip install -r requirements.txt
```

## Usage

Each folder contains a Jupyter notebook for the corresponding step:

1. Acquisition: Load and collect raw datasets.
2. Preprocessing: Clean, transform, and prepare data for modeling.
3. Modelling: Train and test machine learning models for nowcasting GDP.
4. Evaluation: Assess model performance and interpretability; generate figures and tables.
5. Run the notebooks sequentially to reproduce the analysis and results.

---

## Citation

If you use this repository or the methods presented herein, please cite:

Stefano Grassi, (2025). *Why Both Accuracy and Interpretability Matter: Machine Learning for Nowcasting Thai GDP*. [GitHub Repository](https://github.com/stevefatz95/acc-int-ml-nowcasting-thailand-gdp/).



