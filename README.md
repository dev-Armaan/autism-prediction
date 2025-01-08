# Autism Diagnosis Prediction Model :brain:

This project leverages supervised learning algorithms such as `Decision Tree Classifier` and `Random Forest Classifier` to develop a predictive model capable of determining whether an individual is likely to have autism based on around 20 related parameters.

Autism Spectrum Disorder (ASD) is a developmental condition that affects communication and behaviour. Early and accurate prediction of autism can lead to timely intervention and support. The primary goal of this project is to build a reliable and efficient model that can assist in identifying autism by analyzing patterns in the data.

A recent [study](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2800726?utm_source=For_The_Media&utm_medium=referral&utm_campaign=ftm_links&utm_term=012523) by the Journal of the American Medical Association found that medical teams could accurately diagnose ASD in children 60-89% of the time. This best model generated had a `93% Cross-Validation Accuracy` on the test data.

## Previews :eyes: 

<img width="749" alt="correlation-heatmap" src="https://github.com/user-attachments/assets/60530b8e-9f89-400b-94bc-cde0d89af4b9" />

<img width="749" alt="model-accuracy" src="https://github.com/user-attachments/assets/a8b5d87b-b963-48d7-8bf5-b365fffe3329" />

## Tools & Technologies Used :wrench:

* `python`
* `google colab`
* `numpy` for numerical computations
* `pandas` for data manipulation
* `matplotlib` and `seaborn` for data visualization
* `sklearn` for preprocessing, modelling, and evaluation
* `imblearn` for handling imbalanced data with `SMOTE`
* `pickle` for model persistence

## Training and Test Data Sources :mag:

The test and training data used came from Kaggle, specifically a previous [community prediction competition](https://www.kaggle.com/competitions/autismdiagnosis/rules#7-competition-data). The creator has the moniker [Tensor Girl](https://kaggle.com/usharengaraju) and they did not provide a license for the usage policy.

## Installation and Usage :arrow_down:

1. Download the file `ASD_prediction_model.ipynb` and open it in your desired environment.

2. Download the file `train.csv` and add it to the same folder as the ipynb.

3. (Optional) Experiment with the `hyperparameter grid variables` (as shown below) and see if you can achieve a higher cross-validation accuracy.

<img width="454" alt="hyperparameter grid variables" src="https://github.com/user-attachments/assets/405cbf3e-73d9-4190-9ded-c89df129b936" />

4. Add additional data to the folder and use the model to make predictions or play around with the `train-test split` to test the model's accuracy.
