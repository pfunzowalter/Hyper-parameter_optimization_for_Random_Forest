# Hyper-parameter_optimization_for_Random_Forest
In this repository we optimize the random forest (RF) hyper-parameters for the dataset; DR16 cross-matched with the WISE catalogue. In this case, we trained the algorithms on about 80% of the dataset to find the best parameter settings for the algorithms to best estimate the photometric redshifts using the sk-learn RandomisedSearchCV. We used the "neg_mean_squared_error", "neg_median_absolute_deviation" and both "neg_mean_squared_error" and "neg_median_absolute_deviation"  as a scoring metrics. The "neg_median_absolute_deviation" yields best results for this project. The full python script "final_rf_optimization_reviewed.ipynb"



![picture](https://github.com/pfunzowalter/Hyper-parameter_optimization_for_Random_Forest/blob/main/sample_data.png)
