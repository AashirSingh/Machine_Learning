# Machine_Learning

CA03: Decision Tree Algorithm
The dataset is obtained from the Census Bureau and represents salaries of people along
with seven demographic variables. The following is a description of our dataset:

Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ]
Number of attributes (Columns): 7
Number of instances (Rows): 48,842

#1. Data Sources
"https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true"
 
 Questions to think about
Q.1 Why does it makes sense to discretize columns for this problem?
Q.2 What might be the issues (if any) if we DID NOT discretize the columns.
Q.3 Decision Tree Hyper-parameter variation vs. performance
Q.4 How long was your total run time to train the best model?
Q.5 Did you find the BEST TREE?
Q.6 Write your observations from the visualization of the best tree
Q.7 Will this Tree “overfit”? (Hint: Is this tree “fully grown”)
Q.8 What is the probability that your prediction for this person is correct?

Part 2: Data Quaility Report
Peform data cleaing by finding outliers, NaN, and missing values
Display Descriptive statistics for each variable

Part 3: Building the decision tree
Decisoon tree is simple to understand and can handle both numerical and categorical data

Part 4:
Calculate recall, precision, F1 score, accuracy
Confusion matrix

Part 5: Tune Decison tree performance
4 Hyperparmaeters to modify
1. Split Criteria – ‘Entropy’ or ‘Gini Impurity’
2.Maximum Features – The number of features to consider when looking for the best split
3.Minimum Sample Leaf – Minimum of samples in a leaf node to stop further splitting (becomes a leaf node)
4.Maximum Depth – Maximum depth of the tree allowed

Part 6:
Once you have the best hyper-parameters from 4 runs, you will know the hyper-parameter combination of your BEST-performing Tree with respect to “accuracy”. Use these set of hyper-parameters to build the BEST Tree, record it’s performance parameter (all of them) and then “visualize” this best tree:

Part 7:
Answer some concluding questions

Part 8:
Based on the Performance Tuning effort in the previous section, pick your BEST PERFORMING TREE. Now make prediction of a “new” individual’s Income Category ( <=50K, or >50K ) with the following information.

Hours Worked per Week = 48
Occupation Category = Mid - Low
Marriage Status & Relationships = High
Capital Gain = Yes
Race-Sex Group = Mid
Number of Years of Education = 12
Education Category = High
Work Class = Income
Age = 58
