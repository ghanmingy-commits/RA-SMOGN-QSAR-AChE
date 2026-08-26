# Enhancing QSAR-Based Prediction of Acetylcholinesterase Inhibitors via RA-SMOGN Data Augmentation and Explainable Machine Learning

This repository contains the source code and computational workflow associated with the study:

**"Enhancing QSAR-Based Prediction of Acetylcholinesterase Inhibitors via RA-SMOGN Data Augmentation and Explainable Machine Learning"**

## Overview

This project presents a QSAR-based machine learning framework for the prediction of acetylcholinesterase (AChE) inhibitor activity. The proposed workflow incorporates Residual-Adaptive Synthetic Minority Over-sampling with Gaussian Noise (RA-SMOGN) for data augmentation and explainable machine learning (XAI) using SHAP.

## Dataset

The bioactivity data analysed in this study were obtained from the **ChEMBL database**.

* **Target:** Acetylcholinesterase
* **ChEMBL Target ID:** CHEMBL220
* **ChEMBL database:** https://www.ebi.ac.uk/chembl/
* **Activity dataset:** https://www.ebi.ac.uk/chembl/explore/activities/STATE_ID:egauoFyoeGb-enimdM_05w%3D%3D

The original ChEMBL data should be retrieved directly from the source. Processed data used during analysis may be generated using the preprocessing workflow provided in this repository.

## Computational Workflow

The main workflow consists of:

1. Data collection from ChEMBL
2. Data cleaning and preprocessing
3. Molecular descriptor generation
4. MACCS fingerprint generation
5. Feature selection
6. RA-SMOGN data augmentation
7. Machine learning model development
8. Model evaluation and validation
9. SHAP-based explainable machine learning analysis

## Repository Structure

```text
RA-SMOGN-QSAR-AChE/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── RA-SMOGN_QSAR_XAI.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── ra_smogn.py
│   ├── models.py
│   └── xai.py
│
├── figures/
│
├── data/
│   └── README.md
│
└── results/
    └── README.md
```

## Software and Libraries

The implementation uses Python and relevant scientific machine learning and cheminformatics libraries, including:

* Python
* RDKit
* scikit-learn
* XGBoost
* SHAP
* pandas
* NumPy
* Matplotlib

The required Python packages are listed in `requirements.txt`.

## Reproducibility

The main computational workflow is provided in the Jupyter notebook located in the `notebooks/` directory.

Users can retrieve the original bioactivity data from ChEMBL using the target identifier **CHEMBL220** and reproduce the preprocessing, RA-SMOGN augmentation, machine learning, and explainable AI workflow using the provided code.

## Code Availability

The code associated with this study is provided for research reproducibility and can be made available to the Editorial Board and peer reviewers during the peer-review process.

## Citation

If you use this repository or the associated methodology, please cite the corresponding research article:

> Ayyad et al. "Enhancing QSAR-Based Prediction of Acetylcholinesterase Inhibitors via RA-SMOGN Data Augmentation and Explainable Machine Learning."

## License

This repository is intended for academic and research purposes.
