**TASK** 
**Age Prediction in Humans**

The Instructions were to:
Study the data given
There are 1000 CpG sites to be used to determine the age of 108 individuals (Homo sapiens)
Using any regression model, predict the age of the patients (last columns)
In your feature selection step, reduce the number of features to select to 90, 80, 70, 60, 50, 40, 30, 20 and 10. How does the MSE behave with the reducing number of features?
Generate a plot of the number of features against the mse values

**SOLUTION** 
I loaded the dataset using Pandas to access the features (CpG sites) and the target variable (age).
I calculated the correlation between each feature and the target (age). I then selected the top k features with the highest absolute correlation to reduce dimensionality.
I implemented a simple linear regression model.
I plotted the number of features against the MSE to understand how the error changes as the feature count decreases.


**OUTPUT** 
Uploaded the output
