# 🧬 Breast Cancer ADMET Machine Learning Dataset

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)]()
[![Pandas](https://img.shields.io/badge/Library-Pandas-green.svg)]()
[![Notebook](https://img.shields.io/badge/Environment-Jupyter_Notebook-orange.svg)]()
[![Status](https://img.shields.io/badge/Project-Research-success.svg)]()
[![License](https://img.shields.io/badge/License-Academic-lightgrey.svg)]()

Machine learning–ready **ADMET dataset of anticancer compounds** used in breast cancer research.  
Includes preprocessing scripts, **ordinal encoding of solubility classes**, and curated **pharmacokinetic, toxicity, and drug-likeness features** for computational drug discovery.

---

# 📌 Project Overview

This repository contains a **curated ADMET dataset of anticancer compounds relevant to breast cancer research**.

The dataset includes:

- Physicochemical properties
- Pharmacokinetic parameters
- Toxicity predictions
- Drug-likeness metrics

These descriptors are widely used in **computational drug discovery pipelines**.

The project focuses on transforming **raw ADMET prediction results** into a **structured machine-learning ready dataset** using preprocessing and encoding techniques.

The final dataset can be used for:

- Predictive modeling
- Drug screening
- Computational analysis in **bioinformatics and cheminformatics**

This repository provides the **complete workflow from raw ADMET results to a clean encoded dataset suitable for machine learning applications.**

---

# 🎯 Objectives

The primary goals of this project are:

- Prepare and curate **ADMET data for anticancer compounds**
- Convert **categorical solubility classes into numerical representations**
- Generate a **machine learning–ready dataset**
- Enable downstream computational analysis such as:

  - Drug screening
  - Predictive modeling
  - Computational drug discovery

---

# 🧪 Dataset Description

The dataset contains **ADMET profiles of multiple anticancer compounds**.

Each compound is characterized by several **pharmacological and chemical descriptors**, including:

- Molecular properties
- Drug-likeness parameters
- Pharmacokinetic features
- Toxicity predictions
- Synthetic accessibility scores
- Solubility classification

These features are **commonly used in computational drug discovery workflows.**

---

# ⚙️ Data Preprocessing Workflow

The preprocessing pipeline includes the following steps:

1️⃣ **Loading the ADMET dataset**

```python
import pandas as pd
df = pd.read_csv("Encoded_Master_ADMET_Results.csv")
```

2️⃣ **Identifying categorical solubility classes**

3️⃣ **Applying ordinal encoding** to convert solubility categories into numerical values

4️⃣ **Generating the final machine-learning ready dataset**

5️⃣ **Exporting the processed dataset for further analysis**

---

# 💧 Solubility Encoding Systems

Three solubility classification systems were encoded:

- **ESOL Class**
- **Ali Class**
- **Silicos-IT Class**

Each solubility class was mapped into an **ordinal numerical scale** ranging from:

```
Insoluble → Poorly Soluble → Moderately Soluble → Soluble → Very Soluble
```

This encoding allows the solubility information to be **used directly in machine learning models.**

---

# 📂 Repository Structure

```
📁 Repository
│
├── Final_encoding.ipynb
│   Python notebook containing preprocessing workflow and encoding procedure
│
├── Encoded_Master_ADMET_Results.csv
│   Original processed ADMET dataset with pharmacological descriptors
│
└── Final_ML_Ready_ADMET.csv
    Final encoded dataset ready for machine learning analysis
```

---

# 🧰 Technologies Used

The following tools were used in this project:

- **Python**
- **Pandas**
- **Jupyter Notebook**

These tools were used for:

- Data preprocessing
- Feature encoding
- Dataset preparation

---

# 🚀 Potential Applications

The dataset generated in this project can be used for:

- Machine learning models for **drug property prediction**
- **Drug candidate prioritization**
- **Computational drug discovery workflows**
- **Bioinformatics and cheminformatics research**
- **Pharmacokinetic and toxicity modeling**

---

# ▶️ How to Use the Dataset

Follow these steps to work with the dataset:

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/repository-name.git
```

### 2️⃣ Open the Jupyter Notebook

Launch:

```
Final_encoding.ipynb
```

### 3️⃣ Run the encoding workflow

Execute the notebook cells to reproduce the **data preprocessing pipeline.**

### 4️⃣ Use the final dataset

The generated dataset:

```
Final_ML_Ready_ADMET.csv
```

can be directly used in:

- Python
- R
- Machine learning frameworks
- Statistical analysis tools

---

# 🔬 Future Work

Possible improvements and extensions include:

- Integration with **molecular descriptors and fingerprints**
- Development of **predictive models for drug activity**
- Integration with **docking or virtual screening results**
- Expansion of the dataset with **additional anticancer compounds**

---

# 👨‍🔬 Author

**Dr. Nagendra**

Clinical Data Science | Bioinformatics | Computational Drug Discovery

---

# 📜 License

This project is intended for **academic and research purposes**.

---

⭐ If you find this dataset useful for your research, consider **starring the repository**.
