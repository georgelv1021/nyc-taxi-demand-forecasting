# nyc-taxi-demand-forecasting

## Taxi Demand Prediction on hourly basis for different geographical zones

## Table of Contents  
1. [Cluster & Environment Setup](#Cluster-Environment-Setup)  
2. [Basic Data Resource and Utilization](#Basic-Data-Resource-and-Utilization)
   - [Data Resource](#Data-Resource)
   - [Data Split](#Data-Split)
   - [Modeling](#Modeling)
3. [Resource](#resource)

---

## Cluster & Environment Setup
1. Microsoft Azure
2. Node Type: Standard_DS3_V2 (14GB; 4Cores)
   
## Basic Data Resource and Utilization

### Data Resource
1. NYC TLC data center: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Parquet file
3. Azure Operated

### Data Split:
1. Training Data: 2017/1/1 12 AM – 2018/5/26 1 PM
2. Validation Data: 2018/5/25 2PM – 2018/9/13 4AM
3. Testing Data: 2018/9/13 5AM  – 2018/12/23 11PM

### Modeling
1. Linear (Baseline)
2. Random Forest
3. XGBoost

   
