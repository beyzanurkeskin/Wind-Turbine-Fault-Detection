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


## Usage
1. Download the Dataset:
   ```
   [https://drive.google.com/drive/folders/1x8znRCDLU_i7m5WmKqC_xjEyDXnNW3yR?usp=sharing](https://www.kaggle.com/datasets/azizkasimov/wind-turbine-scada-data-for-early-fault-detection)
   ```
3. Clone the repository:
   ```bash
   git clone https://github.com/beyzanurkeskin/Wind-Turbine-Fault-Detection.git  
   ```
   
4. Install dependencies:
   You can install the required Python packages using the following command
   ```
   pip install pyspark tensorflow scikit-learn keras Pillow numpy matplotlib seaborn visualkeras opencv-python joblib dask time 
   ```

6. Run Jupyter Notebooks:
  Open the notebooks (eda.ipynb, pca_lstm.ipynb, rf_gbt_lstm.ipynb) and run the cells sequentially to execute the code.
