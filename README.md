# AnomalyDetection

The dataset comprises multiple experiments, each consisting of a series of time series data. Examples of the data are as follows:


![image](https://github.com/iwkkk/AnomalyDetection/assets/77448166/9e812813-d369-48cb-bc28-d91f53c50375)

If an experiment encounters errors during the middle process, it is considered a failure for the remainder of the time. Here is an example of the failure record.


{"exp_id": [59, 60, 61, 77, 78, 79], 
"failure_time": ["2021-07-24 12:55:00", "2021-08-03 17:29:00", "2021-08-01 05:12:00", "2023-08-17 02:38:00", "2023-08-20 03:59:00", "2023-08-25 14:29:00"], 
"failure_type": ["failure_1", "failure_1", "failure_1", "failure_0", "failure_0", "failure_0"]}


The objective is to classify “normal” VS “failure” cases.
