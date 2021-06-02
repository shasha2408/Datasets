Multi variate time series analysis - outlier / anomaly identification.<br>
There are 509k samples with 11 features.<br>
Each instance / row is one moment in time.
0.09% of rows are identified as events, basically rare, outliers / anomalies
An event is actually a series of time steps around it…approx 10 before and 10 after
Task is to identify these events in this time series - time series classification 
As dataset is unbalanced, the metric to use is **F1 score**(not accuracy, nor ROC AUC)
