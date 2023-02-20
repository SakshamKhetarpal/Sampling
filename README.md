# Sampling (Credit Card Fraud Detection)
## Problem Statement : 
1) Download the dataset - https://github.com/SakshamKhetarpal/Sampling/blob/main/Creditcard_data.csv
2) Convert this data-set into balanced class data-set.
3) Create five samples using different techniques.
4) Apply these five different sampling techniques ( Sampling1, Sampling2, Sampling3, Sampling4, Sampling5) on five different ML models (M1, M2, M3, M4 and M5).
5) Determine which sampling technique gives highest accuracy on which model.

   ![image](https://user-images.githubusercontent.com/91868707/219940974-89d3ccfa-9a58-4e69-adbc-e6c6fb3bbfa2.png)

## Solution : 
### Step 1:
Load the dataset and analyse it.

![image](https://user-images.githubusercontent.com/91868707/220164138-a626b291-132b-43be-901b-0cbe25218f58.png)

### Step 2: Resampling
Balance the dataset using resampling techniques:
1) Random over sampling
2) Synthetic minority over-sampling technique

### Step 3: Sampling
Generate 5 samples using different sampling techniques:
1) Random Sampling
2) Stratified sampling
3) Systematic sampling
4) Cluster sampling
5) Convenience sampling

### Step 4: Model Evaluation
Evaluate the samples on different models to see the performance:
1) Logistic Regression
2) Support Vector Machines
3) Decision Trees
4) Random Forest
5) Naive Bayes
6) K-Nearest Neighbor

### Step 5: Metrics Comparison
Compare the metrics of all the models.

![image](https://user-images.githubusercontent.com/91868707/220166468-08779971-60e3-470f-a796-f97d40bdad01.png)

### Step 6: Conclusion
K-Nearest Neighbor gives the highest accuracy (0.956897) while using sample 2 (Stratified sampling).

![image](https://user-images.githubusercontent.com/91868707/220166552-662dd25a-804d-4b63-b12b-d4e9301870e5.png)
