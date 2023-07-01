# Data Analyst Associate Practical Exam Submission

# TASK 1 

### To check whether values match the description given, count number of missing values and to match the values to the description.

**Step 1** : Importing the Dataset and creating a DataFrame

**Step 2** : Checking for null values

**Step 3** : Checking and Counting for inconsistent values as per dataset description and criteria.

**Step 4** : Replacing values as per the criteria given.

**Step 5** : Final check to see whether the criteria is satisfied.

## TASK 1 SOLUTION:

For every column in the data:

- product_id: Values match the description: Yes Number of missing values: 0 No changes were made to this column.

- category: Values match the description: Yes Number of missing values: 25 The missing values were replaced with "Unknown" to match the description.

- animal: Values match the description: Yes Number of missing values: 0 No changes were made to this column.

- size: Values match the description: Yes Number of missing values: 0, Values Not matching the description: 1050. The strings were converted to Capitalize case so it can be categorised properly in further stages. 

- price: Values match the description: Yes Number of missing values: 150 The missing values, represented as "unlisted", were replaced with the overall median price to match the description. And entire column was converted to float type rounded to 2 digits. 

- sales: Values match the description: Yes Number of missing values: 0 No changes were made to this column.

- rating: Values match the description: Yes Number of missing values: 150 The missing values, represented as "NA", were replaced with 0 to match the description.

- repeat_purchase: Values match the description: Yes Number of missing values: 0 No changes were made to this column.


## TASK 2 SOLUTION:
## 
**A.** State which category of the variable repeat purchases has the most observations: **Equipment** has the most repeat purchases as per the output plot. 

**B.** Explain whether the observations are balanced across categories of the variable repeat purchases: The number of repeat purchases across categories is **not evenly balanced**. The 'Unknown' category has the lowest repeat purchases, likely due to products that are uncategorized. Among the categorized products, accessories have the lowest repeat purchases. **The categories of food, housing, medicine, and toys show relatively balanced** repeat purchase observations. However, equipment stands out with the highest number of repeat purchases. 

![download](https://github.com/Ronit11246/DataCampAssociateProject/assets/108767208/ccbfc56c-ad95-4512-b83d-21fb696d6577)


# TASK 3
### Graphical Distribution of all of the sales

## TASK 3 SOLUTION:

The distribution of sales shows a **partially right-skewed pattern**, with the most frequent sales falling within the bins of 1000 to 1100 and 600 to 900. There are also some outliers with exceptionally high sales values, but they are rare occurrences. As an Analyst, **I recommend that the team pays attention to sales in the 600-900 and 1000-1100 range**, as they appear to be the most common and significant. 


![download (1)](https://github.com/Ronit11246/DataCampAssociateProject/assets/108767208/439d447b-6f21-4d8a-84c0-31cff2acf280)


# TASK 4
### Relationship between repeat purchases and sales

## TASK 4 SOLUTION:

**Median Sales:** The median sales for non-repeat purchases (labeled as 0) appear to be slightly higher compared to repeat purchases (labeled as 1). This suggests that customers who do not repeat purchases tend to have slightly higher sales on average.

**Variability:** The size of the boxes for repeat and non-repeat purchases is similar, indicating that the variability in sales is comparable between the two categories. This suggests that there is no significant difference in the spread of sales values between customers who repeat purchases and those who do not.

**Outliers:** The presence of more outliers in the repeat purchases category indicates that there are some instances where customers who repeat purchases have exceptionally high sales. These outliers may represent a specific segment of customers who contribute significantly to the overall sales in the repeat purchases category.

**Maxima:** Additionally, it can be observed from the box plot that the non-repeat purchase category (labeled as 0) has a larger maximum value compared to the repeat purchase category (labeled as 1). However, the lower value, represented by the lower whisker, appears to be similar in both categories. This indicates that while there may be some customers in the non-repeat purchase category who have exceptionally high sales, the majority of sales in that category tend to be lower. On the other hand, the repeat purchase category shows a more consistent distribution of sales, with fewer extremely high sales values.

**25th and 75th percentile:** Furthermore, when comparing the quartiles of the two categories, it is evident that the 25th percentile (lower edge of the box) and the 75th percentile (upper edge of the box) of the non-repeat purchase category are higher than those of the repeat purchase category. This indicates that a larger proportion of non-repeat purchases have higher sales values compared to repeat purchases.

### Overall, the box plot suggests that while the median sales may be slightly higher for non-repeat purchases, there is a wide range of sales values within both categories.


# Final Thoughts

Based on the data analysis, here are some suggestions for PetMind to leverage the impact of repeat purchases on sales:

**Focus on Customer Retention:** Given that customers who do not repeat purchases tend to have slightly higher sales on average, PetMind can focus on strategies to retain these customers. This could include personalized offers, loyalty programs, or targeted marketing campaigns aimed at encouraging repeat purchases.

**Identify and Cater to High-Spending Customers:** The presence of outliers in the repeat purchases category suggests the existence of a segment of customers with exceptionally high sales. PetMind can identify and analyze the characteristics and preferences of these high-spending customers. By understanding their needs and preferences, PetMind can tailor its offerings and marketing efforts to specifically target and engage this valuable customer segment.

**Enhance Customer Experience:** Since there is no significant difference in the spread of sales values between repeat and non-repeat purchases, PetMind should focus on providing an excellent customer experience to encourage repeat purchases. This includes ensuring product quality, timely delivery, responsive customer service, and convenient shopping experiences.

**Promote Everyday Items:** Given that PetMind aims to increase sales of everyday products, such as food, it should prioritize promoting these items to customers. This can be done through targeted marketing campaigns, product bundling, discounts, or incentives for repeat purchases of everyday items.

**Analyze Non-Repeat Purchase Segment:** While the repeat purchase category shows a more consistent distribution of sales, PetMind should also analyze the characteristics and behavior of customers in the non-repeat purchase category with exceptionally high sales. Understanding why some customers make high-value one-time purchases without repeating can provide insights into potential strategies to convert them into repeat customers.


![download (2)](https://github.com/Ronit11246/DataCampAssociateProject/assets/108767208/6547b6d7-89c7-4ea2-8ca8-236aebeab2cc)

![newplot](https://github.com/Ronit11246/DataCampAssociateProject/assets/108767208/735faeb2-425d-4862-b25c-426a82323661)



