# Age Estimation from Mandibular Measurements Using Machine Learning

## Overview
This project explores the use of supervised machine learning techniques to estimate chronological age based on mandibular morphometric features. The goal is to support forensic identification processes by providing an alternative approach when traditional dental-based methods are not applicable.

## Objective
To develop and validate machine learning models capable of predicting chronological age from skeletal measurements, specifically focusing on mandibular structures in children and adolescents.

## Dataset
- Orthodontic records of individuals aged 6 to 16 years.
- Lateral cephalometric radiographs were used to extract mandibular measurements.
- Ethical approval was obtained, and informed consent was secured for all participants.

## Methodology
- Extraction of linear and angular mandibular measurements from radiographic images.
- Selection of relevant features based on statistical correlation with chronological age.
- Construction of predictive models using multiple supervised machine learning algorithms.
- Data normalization and random partitioning into training and testing sets.
- Model evaluation through stratified cross-validation to ensure robustness and minimize overfitting.
- Hyperparameter tuning to optimize model performance.
- Assessment of model accuracy using standard regression metrics, with confidence intervals estimated through bootstrapping.

## Tools and Technologies
- Python programming language
- Machine learning libraries such as scikit-learn
- Data processing and visualization libraries including NumPy, Pandas, and Matplotlib
- Google Colaboratory as the development environment

## License
This project is intended for academic and research purposes only.
