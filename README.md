##  1. Anomaly Time series :   
- Multi variate time series analysis - outlier / anomaly identification.<br>

- There are 509k samples with 11 features.<br>

- Each instance / row is one moment in time.<br>

- 0.09% of rows are identified as events, basically rare, outliers / anomalies<br>

- Task is to identify these events in this time series - time series classification<br> 

- As dataset is unbalanced, the metric to use is **F1 score**(not accuracy, nor ROC AUC)

## 2. Wafer Manufacturing :
- Dataset Description: The analysis of data concerning the wafer production process with the goal of determining possible causes for errors, resulting in lots of faulty wafers.<br>

- Train.csv - 1763 rows x 1559 columns

- Test.csv - 756 rows x 1558 columns

  __Attribute Description:__

- Feature1 - Feature1558 - Represents the various attributes that were collected from the manufacturing machine

- Class - (0 or 1) - Represents Good/Anomalous class labels for the products

- optimizing Area under the curve(AUC) to generalize well on unseen data
