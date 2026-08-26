# RA-SMOGN-QSAR-XAI

## Enhancing QSAR-Based Prediction of Acetylcholinesterase Inhibitors via RA-SMOGN Data Augmentation and Explainable Machine Learning

This repository contains the computational implementation associated with the study on QSAR-based prediction of acetylcholinesterase (AChE) inhibitors using Residual-Adaptive Synthetic Minority Over-sampling with Gaussian Noise (RA-SMOGN), machine learning, and explainable artificial intelligence (XAI).

## Repository Contents

### Dataset

The `Dataset` folder contains information and resources related to the bioactivity data used in this study.

The dataset was obtained from the **ChEMBL database** using the target identifier:

* **Target:** Acetylcholinesterase
* **ChEMBL Target ID:** CHEMBL220
* **ChEMBL database:** https://www.ebi.ac.uk/chembl/
* **Activity dataset:** https://www.ebi.ac.uk/chembl/explore/activities/STATE_ID:egauoFyoeGb-enimdM_05w%3D%3D

The original data are publicly available from ChEMBL.

### RA-SMOGN-QSAR-XAI

The `RA-SMOGN-QSAR-XAI` folder contains the main Jupyter Notebook implementing the computational workflow, including:

* Data preprocessing
* Molecular descriptors and MACCS fingerprints
* Feature selection
* RA-SMOGN data augmentation
* Machine learning modelling
* Model validation
* Final test evaluation
* Performance visualization
* SHAP-based explainable machine learning
* SHAP feature importance
* SHAP dependence analysis

### Figures

The `Figures` folder contains the figures generated during the analysis and used to visualize model performance and explainable machine learning results.

## Methodology

The overall computational workflow consists of:

1. ChEMBL data collection
2. Data preprocessing and cleaning
3. Molecular descriptor and fingerprint generation
4. Feature selection
5. RA-SMOGN data augmentation
6. Machine learning model development
7. Validation-based model selection
8. Independent test evaluation
9. Model performance visualization
10. SHAP-based explainable machine learning

## Machine Learning

The notebook includes the machine learning models evaluated for QSAR prediction and selects the best-performing model based on validation performance before final evaluation on the test set.

## Explainable Machine Learning

SHAP (SHapley Additive exPlanations) is used to investigate feature contributions and identify the molecular descriptors with the greatest influence on model predictions.

## Reproducibility

The main computational workflow is provided in the Jupyter Notebook in the `RA-SMOGN-QSAR-XAI` folder.

The original bioactivity data can be obtained directly from ChEMBL using the target identifier **CHEMBL220 (Acetylcholinesterase)** and the activity dataset link provided above.

## Code Availability

The code is provided to support reproducibility of the computational analysis and can be accessed by the Editorial Board and peer reviewers during the peer-review process.

## Citation

If you use this code or the associated methodology, please cite the corresponding research article:

> Ayyad et al. Enhancing QSAR-Based Prediction of Acetylcholinesterase Inhibitors via RA-SMOGN Data Augmentation and Explainable Machine Learning.

## Data Source

ChEMBL database:

https://www.ebi.ac.uk/chembl/

