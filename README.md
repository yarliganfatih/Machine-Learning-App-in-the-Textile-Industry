# Machine-Learning-App-in-the-Textile-Industry

## ABSTRACT
In this study, it was tried to calculate the amount of fabrics to be used during that year by estimating the annual sales amounts of the clothes offered for sale by a company providing services in the textile industry in the locations where it is located. In order to create sales forecasts, XGBoost Regression Algorithm modeling is based on machine learning algorithms. The elaboration of this algorithm is the location of the store, the visibility of the product, the amount of fabric, the cut of the product, the amount of the product in the warehouse, etc. parameters are based on. All these parameters and modeling results will help companies with material resource planning.

**Key Words:** MRP, Material Resource Planning, Sales Prediction, Textile Industry, Fabric

## OVERVIEW
In this study, we will use a sales forecasting algorithm for institutions and organizations serving in the textile industry using a machine learning algorithm. With this algorithm, we will help material resource planning by calculating the stock for the fabrics from which the products are produced.
     
Our system will generally collect data from the textile industry and use machine learning to perform optimization etc. for the companies. After the parameters and data are determined and processed into the system, the system will run continuously and fast. It will improve itself by processing the collected data one after another. It’s going to reduce the workforce and save costs for companies. As ‘Management Engineering’ students (Cem, Aysu, Eda) we will take over the strategies, analysis, data collection and operation (etc.) of the project. As ‘Computer Engineering’ students (Sedef, Fatih) we will take over collecting data, processing the collected data, creating the system, etc.

## How to Run?
- Download latest version of Anaconda.
- Run Anaconda Navigator and start Jupyter Notebook
- Open modelling.ipynb file and run script

### Importing Dependencies
```
conda install pickle
```

## Algorithms
### Modelling
- Data Collection
- Data Exploration
  - Data Visualization
- Data Preprocessing
  - Data Manipulation
  - Data Cleaning
  - Data Conversion
  - Data Splitting (Test and Train)
- Machine Learning Model Training
  - randomForest Regressor
  - XGBoost Regressor
  - DecisionTree Regressor
- Saving Models
- Model Comparison
### Prediction
- Loading a Model
- Prediction with inputs