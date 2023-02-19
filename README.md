# Sampling-methods
In this python code, we have used sampling techniques on a credit card fraud detection dataset and then applied various ML models on the dataset to find out which Model,sampling technique combination gives us the best accuracy.<br>

Following 5 sampling Techniques were used:<br>

1.Simple Random <br>
2.Systematic <br>
3.Cluster <br>
4.Stratified <br>
5.Convenience <br>
The Sample size was calculates using the following formula: n = Z^2(p(1 – p)/m^2) where: n = sample size Z = z-value (for 99% confidence interval, Z = 2.576) p = proportion of the minority class (taken as 0.5 for a balanced dataset) m = margin of error (taken as 0.05 for a sample size of 1000)<br>

Following 5 models were applied on the sampled dataset:<br>

1.Logistic Regression (M1)<br>
2.Support Vector Machine (M2)<br>
3.KNN (M3)<br>
4.XGBoost Classifier (M4)<br>
5.Gradient Boosting Classifier(M5)<br>

On execution of the code, following results were obtained: The cells of the table represent accuracy of the applied model using the respective sampling technique.<br>
![Screenshot](screenshot.png)<br>
