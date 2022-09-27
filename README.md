# **diabetes_classification**

**DATASET:**

I took the PIMA Indian Diabetes Dataset, which is originally from the National Institute of Diabetes and Digestive and Kidney Diseases.It contains information about 768 women,atleast 21 years of age of PIMA Indian heritage.
The outcome tested was Diabetes,for which 258 tested positive and 500 tested negative.

**EDA**:

Checking the data for null values and the descriptive statistics for the data which include summary such as the central tendency, dispersion and shape of a dataset's distribution

**TREATING MISSING VALUES:**

I treated missing values by various methods including mean(for normal data), median(for skewed data) ,KNN imputer(for data with a large no. of missing values) and then checked for outliers and treated them using mean,median

**DATA VISUALIZATION:**

I plotted various plots such as -

(i)Correlation matrix(to check for correlation between each pair of variabes)

(ii)histogram (to see distribution of each variable)

(iii)Pairplots (to see both distribution of single variables and relationships between two variables )

(iv)Line plots(for displaying data using a number line)

(v)Bar graphs (to compare the data)

(vi)Joint plots for data visualization and a better understanding of data

**CLASSIFICATION:**

Checked for importance of each feature using Extra Tree Regressor and applied PCA for dimensionality reduction 

For fitting the model, i used Grid Search CV to check for best model (out of logistic regression ,SVM, Gradient Boost , Rabdom forest and Decision Tree classifier ) and best parameters  and chose the model with the best accuracy(Random Forest Classifier) as the final model

For more details about the dataset and methodology, you can visit my medium blog from [here](https://medium.com/p/e4c649a666e9/edit)
