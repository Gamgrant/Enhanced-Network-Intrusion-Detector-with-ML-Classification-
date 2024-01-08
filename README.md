# Enhanced-Network-Intrusion-Detector-with-ML-Classification-

## Overview
In this project, I tackled a multi-class classification problem using SparkML, aiming to predict not just the presence of an attack but also its type. There were five possible categories: normal, DOS, R2L, U2R, and probing.

# Section 1: Data Preprocessing and Pipeline Creation
1.1 Pipeline and Data Engineering
I created a preprocessing pipeline that incorporated standard data engineering steps. This included data cleaning, normalization, and feature engineering. Additionally, I formulated an 'outcome' column to categorize each record into one of the five classes.

# Section 2: Model Selection and Evaluation
2.1 Model Training
I chose two different machine learning models for this task. For each model, I trained it on the training dataset, and then evaluated its performance in terms of training and testing accuracy.

2.2 Confusion Matrix
To further assess the model performance, I plotted confusion matrices for the predictions made on the test dataset.

# Section 3: Hyper-Parameter Tuning and Cross-Validation
3.1 Hyper-Parameter Identification
For each model, I identified key hyper-parameters that could significantly influence model performance.

3.2 Cross-Validation
I constructed a parameter grid for each model and conducted hyper-parameter tuning using cross-validation, focusing on accuracy as the evaluation metric.

3.3 Test Accuracy Post-Tuning
I recalculated the test accuracy after the hyper-parameter tuning to assess the improvements.

# Section 4: Model Selection Rationale and Comparison
4.1 Choice of Models and Hyper-Parameters
I explained my rationale for selecting the two machine learning models, the specific hyper-parameters chosen for tuning, and the design of the parameter grids.

4.2 Comparative Analysis
I included a discussion comparing the two models, focusing on their performance, suitability for the task, and the impact of hyper-parameter tuning.

# Section 5: Distributed Training on Google Cloud DataProc
5.1 Training on DataProc
I chose one of the two models and ran the training process on the Google Cloud DataProc cluster. This involved utilizing worker nodes for distributed training.

5.2 Spark History Server Screenshots
I captured and included screenshots of the Spark history server, showcasing the Jobs page and the Executor page.

