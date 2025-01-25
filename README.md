# Wind Turbine Fault Detection  
This project focuses on detecting faults in wind turbines using machine learning techniques implemented with PySpark. The goal is to identify early signs of potential failures in wind turbine systems by analyzing SCADA (Supervisory Control and Data Acquisition) data. The project includes exploratory data analysis (EDA), dimensionality reduction using PCA, and predictive modeling using Random Forest, Gradient Boosted Trees, and LSTM neural networks.

## Authors  
- Zeynep Begüm Baş  
- Ezgi Aslan  
- Beyza Nur Keskin  

## Objective  
Develop a scalable machine learning pipeline using Apache Spark to detect faults in wind turbines based on SCADA data.  

## Methods  
- **Model Training**: Implemented various models, including Random Forest, Gradient-Boosted Trees, and Logistic Regression, to identify potential faults.  
- **Scalability Testing**: Evaluated the pipeline's performance with large datasets to ensure robustness and efficiency.

## Project Structure
The project is organized into the following files:

eda.ipynb:
This Jupyter notebook contains the Exploratory Data Analysis (EDA) for the wind turbine dataset. It includes data cleaning, visualization, and statistical analysis to understand the dataset's structure and identify patterns or anomalies.

pca_lstm.ipynb:
This notebook implements Principal Component Analysis (PCA) for dimensionality reduction, followed by an LSTM (Long Short-Term Memory) model for fault detection. PCA is used to reduce the number of features while retaining the most important information, and LSTM is applied to capture temporal dependencies in the data.

rf_gbt_lstm.ipynb:
This notebook compares the performance of three machine learning models:

Random Forest (RF)
Gradient Boosted Trees (GBT)
Long Short-Term Memor (LSTM)

The models are evaluated based on their ability to predict faults in the wind turbine data.

##Installation
### 1. Clone the Repository  
Clone this repository to your local machine:  
```bash  
git clone https://github.com/beyzanurkeskin/Wind-Turbine-Fault-Detection.git  
cd Wind-Turbine-Fault-Detection  
```

### 2. Dowload Dataset

You can download the SCADA dataset from Kaggle:https://www.kaggle.com/datasets/azizkasimov/wind-turbine-scada-data-for-early-fault-detection

### 3.Run Jupyter Notebooks
Open the Jupyter notebooks and execute the code:


```bash
jupyter notebook eda.ipynb  
jupyter notebook pca_lstm.ipynb  
jupyter notebook rf_gbt_lstm.ipynb  

```

