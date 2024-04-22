# CS982

This report is for performing in-depth analysis on the [Home Credit]([url](https://www.kaggle.com/code/phamdinhkhanh/home-credit-default-risk/notebook)) dataset, with the aim to provide understanding into the dataset and create a model to predict the default rate of clients using just the application data (This mean the prediction process will not include the payment behavior data after the line of credit has been issued) 

The main metric for the model would be AUC - Area Under Curve to measure to measure the discrepency between prediction and the actual behavior of the customers - 
Just using the data from the Application dataset, the report achieved a result of  **0.68**

If using lightGBM, as showcased in the full_main jupyter file, the model can achieve AUC of **0.75**

The winner of the original competition achieved a result of **0.80570**
