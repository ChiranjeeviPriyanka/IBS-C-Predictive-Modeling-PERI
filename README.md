# IBS-C-Predictive-Modeling-PERI
Predicting IBS-C Risk in Sedentary Professionals Using the Psychosocial-Environmental Risk Index (PERI).

## Project Overview
This research introduces a novel computational framework to address the limitations of traditional occupational health models, which often analyze lifestyle risk factors in isolation. By engineering the Psychosocial-Environmental Risk Index (PERI), this study quantifies the cumulative "allostatic load" on the Gut–Brain Axis, integrating sedentary behavior, psychosocial stress, circadian stability, and dietary quality into a single synergistic predictor. Adopting a hybrid research design, the project validates machine learning models trained on archival real-world data against original primary survey response data from contemporary office-based professionals, ensuring both technical rigor and empirical relevance.

**Methodology:** Hybrid Research Design (Archival N=105 / Primary N=45).

**Key Feature:** Psychosocial-Environmental Risk Index (PERI).

**Model Performance:** 86.67% Accuracy, 0.806 AUC-ROC, and 0.926 Prediction Confidence on primary validation.

## Repository Structure
├── Data/
│   ├── Sleep_health_and_lifestyle_dataset.csv   # Raw archival source
│   ├── cleaned_archival_n105.csv                # Processed developmental training set
│   ├── primary_data_survey.csv                  # Raw primary data source (Survey responses)
│   ├── cleaned_primary_data_n45.csv             # Processed primary validation set
│   └── final_master_hybrid_n150.csv             # Unified hybrid dataset
├── Notebooks/
│   ├── Archival_dataset_EDA.ipynb               # Data integrity & filtering
│   ├── Primary_Dataset_EDA.ipynb                # Survey synchronization & mapping
│   ├── Hybrid_Merging_&_DescriptiveStats.ipynb  # Descriptive statistics
│   └── Comparative_ML_Analysis.ipynb            # ML pipeline & SHAP analysis
├── Documentation/
│   └── RESEARCH_QUESTIONNAIRE_Final.docx        # Validated survey instrument
└── README.md

## Implementation & Documentation
The computational pipeline is implemented in the Google Colab notebooks archived in the Notebooks/ folder. The original research instrument (questionnaire) used to collect primary validation data is archived in the Documentation/ folder of this repository.

## Study Phases

**Developmental Phase:** Archival EDA (N=105)

**Validation Phase:** Primary EDA (N=45)

**Integration:** Hybrid Dataset Descriptive Statistics (N=150)

**Analysis:** Comparative Random Forest Supervised Machine Learning Evaluation



