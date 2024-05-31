# HEART DISEASES PREDICITION
# PROBLEM DEFINITION
The major challenge in heart disease is its detection. There are
instruments available which can predict heart disease but either they are
expensive or not efficient to calculate the chance of heart disease in
humans. Early detection of cardiac diseases can decrease the mortality
rate and overall complications. However, it is not possible to monitor
patients every day in all cases accurately and consultation of a patient
for 24 hours by a doctor is not available since it requires more sapience,
time, and expertise. Since we have a good amount of data in today’s
world, we can use various machine learning algorithms to analyze the
data for hidden patterns. The hidden patterns can be used for health
diagnosis in medical data.

# PREDICITIVE MODEL SELECTION
We have taken 2 machine learning models into consideration:
1. Decision Tree classifier:
DT is a supervised algorithm that creates a classification model
by construction a decision tree. Every hub in the tree determines
a test on a trait, each branch sliding from that hub related to one
of the potential qualities for that property.
2. K Nearest neighbors:
K-nearest neighbors (KNN) is perhaps the most straightforward
calculation utilized in machine learning for relapse and
characterization issues. KNN algorithms use information and
order new information in view of comparability measures.
Categorization is performed by a major support to its neighbors.

# PREPROCESSING OF DATASET:
1. The dataset does not have any null values. But many outliers needed
to be handled properly, and the dataset was not properly distributed.
Two approaches were used.
2. One without outliers and feature selection process and directly
applying the data to the machine learning algorithms, and the results
which were achieved were not promising.
3. But after using the normal distribution of dataset for overcoming the
overfitting problem and then applying Isolation Forest for the
outlier’s detection, the results achieved are quite promising.
4. Various plotting techniques were used for checking the skewness of
the data, outlier detection, and the distribution of
5. the data. All these preprocessing techniques play a key role when
passing the data for classification or prediction purposes.
