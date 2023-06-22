# DataCamp Data Analyst Associate Practical Exam Submission
## To clean the provided dataset, check any correlation betweek products and purchases and show graphical representations

# TASK 1 
### To check whether values match the description given, count number of missing values and to match the values to the description.

**Step 1** : Importing the Dataset and creating a DataFrame
**Step 2**: Looping through each column to Check whether values match the description and replacing the values with the missing value description from the criteria.


TASK 1 SOLUTION:
For every column in the data:

Column product_id: Values match the description: Yes Number of missing values: 0 No changes were made to this column.

Column category: Values match the description: Yes Number of missing values: 25 The missing values were replaced with "Unknown" to match the description.

Column animal: Values match the description: Yes Number of missing values: 0 No changes were made to this column.

Column size: Values match the description: Yes Number of missing values: 0 No changes were made to this column.

Column price: Values match the description: Yes Number of missing values: 150 The missing values, represented as "unlisted", were replaced with the overall median price to match the description.

Column sales: Values match the description: Yes Number of missing values: 0 No changes were made to this column.

Column rating: Values match the description: Yes Number of missing values: 150 The missing values, represented as "NA", were replaced with 0 to match the description.

Column repeat_purchase: Values match the description: Yes Number of missing values: 0 No changes were made to this column.

In summary, the values in most columns match the description given in the table. The 'category' column had 25 missing values, which were replaced with "Unknown". The 'price' column had 150 missing values represented as "unlisted", which were replaced with the overall median price. The 'rating' column had 150 missing values represented as "NA", which were replaced with 0. No missing values were found in other columns.


# TASK 2 
### Visualization to show how many products are repeat purchases

## TASK 2 SOLUTION:
## 
**A.** State which category of the variable repeat purchases has the most observations: **Equipment** has the most repeat purchases as per the output plot. 

**B.** Explain whether the observations are balanced across categories of the variable repeat purchases: The number of repeat purchases across categories is **not evenly balanced**. The 'Unknown' category has the lowest repeat purchases, likely due to products that are uncategorized. Among the categorized products, accessories have the lowest repeat purchases. The categories of food, housing, medicine, and toys show relatively balanced repeat purchase observations. However, equipment stands out with the highest number of repeat purchases. 

![download](https://github.com/Ronit11246/DataCampAssociateProject/assets/108767208/1b7777f1-ce02-4796-9fc0-cf6c050c6397)


# TASK 3
### Graphical Distribution of all of the sales

## TASK 3 SOLUTION:

The distribution of sales shows a partially right-skewed pattern, with the most frequent sales falling within the bins of 1000 to 1100 and 600 to 900. There are also some outliers with exceptionally high sales values, but they are rare occurrences. As a Data Analyst, I recommend that the team pays attention to sales in the 600-900 and 1000-1100 range, as they appear to be the most common and significant. 

![download (1)](https://github.com/Ronit11246/DataCampAssociateProject/assets/108767208/5ae6cba0-2177-4992-9e02-c96779154a29)


# TASK 4
### Relationship between repeat purchases and sales

## TASK 4 SOLUTION:

**Median Sales:** The median sales for non-repeat purchases (labeled as 0) appear to be slightly higher compared to repeat purchases (labeled as 1). This suggests that customers who do not repeat purchases tend to have slightly higher sales on average.

**Variability:** The size of the boxes for repeat and non-repeat purchases is similar, indicating that the variability in sales is comparable between the two categories. This suggests that there is no significant difference in the spread of sales values between customers who repeat purchases and those who do not.

**Outliers:** The presence of more outliers in the repeat purchases category indicates that there are some instances where customers who repeat purchases have exceptionally high sales. These outliers may represent a specific segment of customers who contribute significantly to the overall sales in the repeat purchases category.

**Maxima:** Additionally, it can be observed from the box plot that the non-repeat purchase category (labeled as 0) has a larger maximum value compared to the repeat purchase category (labeled as 1). However, the lower value, represented by the lower whisker, appears to be similar in both categories. This indicates that while there may be some customers in the non-repeat purchase category who have exceptionally high sales, the majority of sales in that category tend to be lower. On the other hand, the repeat purchase category shows a more consistent distribution of sales, with fewer extremely high sales values.

**25th and 75th percentile:** Furthermore, when comparing the quartiles of the two categories, it is evident that the 25th percentile (lower edge of the box) and the 75th percentile (upper edge of the box) of the non-repeat purchase category are higher than those of the repeat purchase category. This indicates that a larger proportion of non-repeat purchases have higher sales values compared to repeat purchases.

### Overall, the box plot suggests that while the median sales may be slightly higher for non-repeat purchases, there is a wide range of sales values within both categories.

![download (2)](https://github.com/Ronit11246/DataCampAssociateProject/assets/108767208/3b984637-0280-41cc-86a9-e92e343cd7ae)
