# breast-cancer-admet-ml-dataset
Machine learning–ready ADMET dataset of anticancer compounds used in breast cancer research. Includes preprocessing scripts, ordinal encoding of solubility classes, and curated pharmacokinetic, toxicity, and drug-likeness features for computational drug discovery.
Breast Cancer ADMET Machine Learning Dataset
Project Overview

This repository contains a curated ADMET dataset of anticancer compounds relevant to breast cancer research. The dataset includes physicochemical properties, pharmacokinetic parameters, toxicity predictions, and drug-likeness metrics used in computational drug discovery.

The project focuses on transforming raw ADMET prediction results into a structured machine-learning ready dataset through preprocessing and encoding techniques. The final dataset can be used for predictive modeling, drug screening, and computational analysis in bioinformatics and cheminformatics studies.

This repository provides the complete workflow from raw ADMET results to a clean encoded dataset suitable for machine learning applications.

Objectives

The primary objectives of this project are:

• Prepare and curate ADMET data for anticancer compounds
• Convert categorical solubility classes into numerical representations
• Generate a machine learning ready dataset
• Enable downstream computational analysis such as drug screening and predictive modeling

Dataset Description

The dataset contains ADMET profiles of multiple anticancer compounds. Each compound is characterized by a wide range of pharmacological and chemical descriptors including:

• Molecular properties
• Drug-likeness parameters
• Pharmacokinetic features
• Toxicity predictions
• Synthetic accessibility scores
• Solubility classification

These features are commonly used in computational drug discovery pipelines.

Data Preprocessing

The preprocessing workflow includes the following steps:

Loading the ADMET dataset using Python and pandas

Identifying categorical solubility classes

Applying ordinal encoding to convert solubility categories into numerical values

Generating a final machine learning ready dataset

Exporting the processed dataset for further analysis

Three solubility classification systems were encoded:

ESOL Class
Ali Class
Silicos-IT Class

Each solubility class was mapped into an ordinal numerical scale ranging from insoluble to very soluble.

Repository Structure

Final_encoding.ipynb
Python notebook containing the preprocessing workflow and encoding procedure used to transform the dataset.

Encoded_Master_ADMET_Results.csv
Original processed ADMET dataset containing multiple pharmacological and physicochemical descriptors.

Final_ML_Ready_ADMET.csv
Final encoded dataset suitable for machine learning and statistical analysis.

Technologies Used

Python
Pandas
Jupyter Notebook

These tools were used for data preprocessing, encoding, and dataset preparation.

Potential Applications

The dataset generated in this project can be used for:

Machine learning models for drug property prediction
Drug candidate prioritization
Computational drug discovery workflows
Bioinformatics and cheminformatics research
Pharmacokinetic and toxicity modeling

How to Use the Dataset

Clone the repository

Open the Jupyter notebook

Run the encoding workflow

Use the final dataset for machine learning or statistical analysis

The final dataset can directly be imported into Python, R, or other machine learning frameworks.

Future Work

Possible future improvements include:

Integration with molecular descriptors and fingerprints
Development of predictive models for drug activity
Integration with docking or virtual screening results
Expansion of the dataset with additional anticancer compounds

Author

Dr. Nagendra
Clinical Data Science | Bioinformatics | Computational Drug Discovery

License

This project is intended for academic and research purposes.
