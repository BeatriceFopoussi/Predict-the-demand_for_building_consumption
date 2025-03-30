# Predict-the-demand_for_building_consumption


# Anticipate Building Energy Consumption Needs

The city of Seattle aims to achieve carbon neutrality by 2050. To this end, we have been tasked with developing a predictive model for CO₂ emissions and total energy consumption of non-residential buildings, without relying on energy readings, which are costly to obtain.

We have also been asked to assess the utility of the ENERGYSTAR Score, which is also challenging to calculate.

Detailed surveys were conducted by city officials in 2016. The data is available :

 [here](https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/Data_Scientist_P4/2016_Building_Energy_Benchmarking.csv) and its source can be found [here](https://data.seattle.gov/dataset/2016-Building-Energy-Benchmarking/2bpz-gwpy). 
 
 However, these surveys are expensive to obtain, and using the existing data, we aim to predict CO₂ emissions and total energy consumption for non-residential buildings where these measurements have not yet been taken.&#8203;:contentReference[oaicite:0]{index=0}

**Approach: Supervised Learning with Continuous Target Variable**

:contentReference[oaicite:1]{index=1} :contentReference[oaicite:2]{index=2}&#8203;:contentReference[oaicite:3]{index=3}

## 1. Baseline Model: Multivariate Linear Regression

:contentReference[oaicite:4]{index=4} :contentReference[oaicite:5]{index=5}&#8203;:contentReference[oaicite:6]{index=6}

## 2. Linear Models

### 2.1. Support Vector Regression (SVM)

:contentReference[oaicite:7]{index=7} :contentReference[oaicite:8]{index=8}&#8203;:contentReference[oaicite:9]{index=9}

## 3. Non-Linear Models

### 3.1. RandomForestRegressor

:contentReference[oaicite:10]{index=10} :contentReference[oaicite:11]{index=11}&#8203;:contentReference[oaicite:12]{index=12}

### 3.2. XGBoost (eXtreme Gradient Boosting)

:contentReference[oaicite:13]{index=13} :contentReference[oaicite:14]{index=14}&#8203;:contentReference[oaicite:15]{index=15}

### 3.3. Convolutional Neural Networks (CNN)

:contentReference[oaicite:16]{index=16} :contentReference[oaicite:17]{index=17}&#8203;:contentReference[oaicite:18]{index=18}

:contentReference[oaicite:19]{index=19}
