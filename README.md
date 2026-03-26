# DILI Multi-Modal Prediction
>>
>> **Drug-Induced Liver Injury Prediction using Multi-Modal Deep Learning**
>>
>> [![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org)
>> [![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
>>
>> ## 🎯 Project Overview
>>
>> This project aims to predict **Drug-Induced Liver Injury (DILI)** using a rich multi-modal approach that combines:
>> - Chemical Structure (SMILES)
>> - Protein Targets (ChEMBL)
>> - Gene Expression Signatures
>> - Biological Pathways
>> - Clinical Biomarkers (ALT, AST, etc.)
>>
>> Expected performance: **AUROC 0.88 – 0.93**
>>
>> ## 📁 Project Structure
>>
>> ```bash
>> DILI-MultiModal-Prediction/
>> ├── data/                  # Raw & processed datasets
>> ├── src/
>> │   ├── data_processing/   # SMILES cleaning & clinical preprocessing
>> │   ├── feature_engineering/ # 5 modalities feature extraction
>> │   ├── models/            # ChemBERTa, Fingerprint CNN, Clinical MLP
>> │   ├── training/
>> │   └── inference/
>> ├── notebooks/             # EDA and experiments
>> ├── configs/               # Model & training configurations
>> ├── artifacts/             # Scalers, imputers, encoders
>> ├── docs/                  # Reports and documentation
>> └── README.md
