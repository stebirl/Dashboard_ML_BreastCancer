# Machine learning for the early detection of breast cancer 

## Project work for the Data Analytics course at alfatraining
Stella Birlo, Alena Rzaeva, Elena Busam 

### Summary:
This project aims to use the dataset of breast cancer diagnoses described below to train several machine learning algorithms. 
These models will then be incorporated into a dashboard that automatically outputs a diagnosis of “malignant” or “benign” based on the input of cell description values.
 - In the first step, the data is loaded, viewed, cleaned and the most important features are selected using feature engineering. (Elena Busam)
 - In the second step, the selected features are divided into test and training data in order to train XGBoost, neural networks and random forests. (Alena Rzaeva)
 - In the third step, the models are then built into a dashboard that can be used like an app for diagnostic output. (Stella Birlo)

### Data Description 
The Breast Cancer Wisconsin (Diagnostic) Data Set contains 569 samples of breast tissue analyzed for various characteristics. The data set includes 33 columns describing different characteristics of the samples. The aim of the data set is to differentiate between benign (B) and malignant (M) tumors. The 30 numerical features used to describe the tissue samples include tumor size, texture, symmetry and the number of cell nuclei. 
Three statistical values are provided for each of these features: 
- Mean: The average value of the respective feature. 
- Standard Error: A measure of the variability of the trait within a sample. 
- Worst: The highest measured value of the trait in the sample. 

The dataset was originally created by W. Wolberg, O. Mangasarian, N. Street, W. Street at the University of Wisconsin-Madison and is available via the UCI Machine Learning Repository on Kaggle. 
Quelle: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data 

## Dashboard:
### Dataset Overview Page
- inteactive scatterplot and Dropdown x and y selection:
![grafik](https://github.com/user-attachments/assets/887051dd-8072-4c12-975a-381c1db848fa)

- Interactive selection of datapoints:
![grafik](https://github.com/user-attachments/assets/d0dfb213-fd83-4c37-b163-0c34fa33ae5b)

### Machine Learning Diagnosis Page:
- Example: Random Forest - Benign Diagnosis:
![grafik](https://github.com/user-attachments/assets/0069f32b-34e1-403c-b431-397b9e1146b5)

- Example: XGBoost - Malignant Diagnosis:
![grafik](https://github.com/user-attachments/assets/aeccec40-e679-419d-8085-0d190a068072)

- Machine Learning Metrics:
![grafik](https://github.com/user-attachments/assets/b2d7f8b6-522a-4bd4-bb83-30354bb71b4d)

