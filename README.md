# -4GB-file-Industrial-process-prediction-

We deal with a large file of 4GB to make predictions on an industrial process.
Here we decide of ways to make the file easier to process by using unstack for example
or plotting certain features with respect to time to visualize the process.
Random forest regression is also used for feature selection. We prefer this method over using 
dask for large file processing. The target value is final_rinse_turbidity and the metric is the mean
absolute percentage error. 
