# Machine_Learning_Preprocessing_and_Basic_Analysis
Preprocessing and Analysis of Bank Data using Python, Pandas, NumPy, Matplotlib


Assignment 1: Preprocessing and Data Analysis
Depaul University 
DSC 478 Programming Machine Learning Applications
Professor Aleksandar Velkoski
Fall 2018

You will work with a modified subset of a real data set of customers for
a bank (provided in CSV).
Must only use: Python, NumPy, Pandas, Matplotlib.

1.	Explore general characteristics:
	-	Means, standard deviations, etc. for numerical attributes
	-	Distributions etc. for categorical attributes

2.	Suppose that the hypothetical bank is particularly interested in
	the customers who buy the Personal Equity Plan.
	-	Compare and contrast the subsets of customers who do and do
		not buy the PEP product.
	-	Compute summaries of selected data with respect to all other
		attributes. Discuss observations

3.	Use z-score normalization to standardize the values of the income
	attribute.

4.	Discretize the age attribute into 3 categories (corresponding to
	'young', 'mid-age', and 'old')

5.	Use Min-Max Normalization to transform the values of all numeric 
	attributes.

6.	Convert the table into the standard spreadsheet format. Note that
	this requires converting each categorical attribute into multiple
	binary attributes. Save this new table into a file called bank_numeric.csv

7.	Using the standardized data set, perform basic correlation analysis among
	the attributes.
	-	Discuss your results by indicating any significant positive
		or negative correlations among pairs of attributes.
	-	Construct a complete Correlation Matrix

8.	Using Matplotlib and/or Pandas, create a scatter plot of the non-normalized
	income attribute relative to Age
	-	Be sure that your plot contains appropriate labels for the axes
	-	Do these variables seem correlated?

9.	Create histograms for non-normalized income (using 9 bins) and age (using 15 bins)

10.	Using a bar graph, plot the distribution of the values of the region attribute

11.	Perform a cross-tabulation of the region attribute with the PEP attribute
	-	This requires the aggregation of the occurrences of each PEP value
		separately for each value of the region attribute.
	-	Show the results as a 4x2 table with entries representing counts
