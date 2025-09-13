# Why Both Accuracy and Interpretability Matter: Machine Learning for Nowcasting Thai GDP

Pseudo real-time framework for GDP nowcasting in Thailand using machine learning, with a focus on accuracy and interpretability.

---

## Repository Structure

```
├── README.md
├── requirements.txt
├── 01-data-collection/
│ ├── data/ # Datasets used for data collection
│ └── data-collection-thai-gdp-nowcasting.ipynb
├── 02-data-preprocessing/
│ ├── data/ # Datasets after preprocessing
│ └── data-preprocessing-nowcasting-thai-gdp.ipynb
├── 03-modelling/
│ ├── data/ # Datasets used for modelling
│ └── modelling-nowcasting-thai-gdp-dec.ipynb
│ └── modelling-nowcasting-thai-gdp-jan.ipynb
├── 04-evaluation/
  ├── data/ # Datasets used for evaluation
  └── evaluation-nowcasting-thai-gdp.ipynb
```

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

### Data Acquisition API Key (01-data-collection)

The data acquisition notebook (`data-collection-thai-gdp-nowcasting.ipynb`) requires an API key from the Bank of Thailand (BOT) to access the official API.

#### How to get the API key:

1. Navigate to the official BOT API Portal: https://apiportal.bot.or.th/bot/public/
2. Register for an account and subscribe to the "BOT Public API" product.
3. Generate your API key.

#### how to use the API key in the notebook:

Simply insert your actual API key directly into the code where the placeholder text is located within the headers dictionary.

### Data Preprocessing (02-data-preprocessing)

This notebook requires the X-13ARIMA-SEATS program for seasonal adjustment. It must be downloaded and installed separately.

#### How to download and install X-13ARIMA-SEATS:

1. Download the program from the official U.S. Census Bureau website: https://www.census.gov/data/software/x13as.html
2. Follow the detailed installation instructions provided on the same page for your specific operating system (Windows, macOS, or Linux).

---

## Citation

If you use this repository or the methods presented herein, please cite:

Stefano Grassi, (2025). *Why Both Accuracy and Interpretability Matter: Machine Learning for Nowcasting Thai GDP*. [GitHub Repository](https://github.com/stevefatz95/acc-int-ml-nowcasting-thailand-gdp/).



