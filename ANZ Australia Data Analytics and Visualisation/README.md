# ANZ Dataset EDA and Data Wrangling 
The task is based on a fictional dataset of transactions carried out by 100 customers over the period of 3months. \

Issues with the file have been created in the issue section, help would be appreciated !

Learnt : 
1. Reusing code to find outlier-count as a % of total no. of rows
2. Missing Value Treatment
3. Effect of outliers on mean value.
4. Identifying Log-normal distributions and using log-transformation to reduce bias/variance in values.
5. Extracting month and week from date provided.

Insipiration : ANZ synthesised transaction dataset from Forage (although this program was discontinued by Forage, I learnt a lot)
 _____
Todo :
 * Using the lat_long column to find out which city was the transaction carried out in, preferably using Nominatim from geopy library. 
 * Replace outliers (in columns whose rows couldn't be dropped) with median values
 * Make bar charts to represent top-5 cities based on transaction-amounts and number of transactions (using matplotlib)
 * Visualizing where the richest customers/users reside.