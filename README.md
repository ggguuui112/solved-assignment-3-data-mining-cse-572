Download Link: https://assignmentchef.com/product/solved-assignment-3-data-mining-cse-572
<br>
Given: Meal Data of 5 subjects

Amount Of carbohydrates in each meal

<ol>

 <li>a) Extract features from Meal data</li>

 <li>b) Cluster Meal data based the amount of carbohydrates in each meal</li>

</ol>

First consider the given Meal data. Take first 50 rows of the meal data. Each row is the meal amount

Of the corresponding the mealDataXcsv of every subject. So mealAmountDataI.csv corresponds

to the first subject. The first 50 rows of the mealAmountData1.csv corresponds to the first rows of

mealDataX.csv in Assignment 2.

Extracting Ground Truth: Consider meal amount to range from O to 100. Discretize the meal amount in

bins of size 20. Consider each row in the mealDataX.csv and according to their meal amount label put

them in respective bins. There will be 6 bins starting from O. •O to 20, 21 to 40, 41 to 60, 61 to 80.81

to 100.

Now ignore the mealAmountData. Without using the meal amount data use the features in your

assignment 2 to cluster the mealDataX.csv into 6 clusters. use DESCAN or KMeans. Try these two.

your of clustering based on SSE and supervised cluster validity metrics.

Grading: I will give you a set Of Meal data that is not included in the training Set.

50 snints for developing a in Python or Matlab that takes the dataset and performs clustering

20 ‘X)ints for developing a code in or Matlab that irnplernents a functR•n to take a test input and

run the clustering algorithm to ;xovide the clustering result

30 points will be evaluated the supervised cluster validation results obtained by your rmachine. This

will be compared against class av«age to determine the final score.

Example:

20

40

1,6910

11, 12 13

2.7,8, 1415

1-349,11.12.15 •0&lt;-20

2-1, 2, 10+0

3-5, 6,

Classification error supervised cluster validity metric

241+2-5