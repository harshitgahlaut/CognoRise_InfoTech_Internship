# **Big Mart Sales Prediction**

![sales-forecast-3](https://github.com/harshitgahlaut/CognoRise_InfoTech_Internship/assets/142779836/d1fdf6a0-ba01-4cd7-b125-4a197ae24a6e)

## **Objective:**
- The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined.
- The aim is to build a predictive model and find out the sales of each product at a particular store. Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

## **Dataset** : [Kaggle](https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data)

## **Tech Stack Used**

![python-logo-only](https://github.com/harshitgahlaut/CognoRise_InfoTech_Internship/assets/142779836/a7bf9885-e706-4719-abb0-f3d22d924187)

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-Learn

## **Skills Showcased in this Project**

- Data Exploration
- Data Cleaning
- Exploratory Data Analysis - Univariate Analysis, Bivariate Analysis, Multivariate Analysis
- Data Visulisation
- Feature Engineering - Label Encoding and One Hot Encoding
- Model Building - Multiple Linear Regression, Ridge Regression, Lasso Regression, Elastic Net Regression 

## **Observations**
### *Univariate Analysis*
- Item_Outlet_Sales feature is right skewed and it has outliers.
- Item weight has no outliers.
- Item_Visibility is right-skewed and has outliers.
- We can clearly see 4 different distributions for Item_MRP.
- Low Fat content items are more than Regular Fat content.
- Fruits and Vgetables along with Snack Foods are maximum in qunatity.
- Top 5 Items
    - Fruits and Vegetables
    - Snack Foods
    - Household
    - Frozen Foods
    - Canned
- 10 unique outlets are present and OUT019 has the least presence.
- Maximum outlets are of Medium Size.
- Maximum Outets are from Tier 3 location.
- Almost equal presence of stores in terms of Age of stores, maximum stores are of 39 years old.
- Maimum outlets are of Suermarket Type 1.

### *Bivariate Analysis*
- Sales is spread well across the entire range of the Item_Weight without any obvious pattern.
- In the plot of Item_MRP vs Item_Outlet_Sales, we can clearly see 4 segments of prices and Range of 200-250 is having highest Sales.
- Sales is almost equal in both categories of Fat content.
- Top 5 Items as per Sales
    - Starchy Foods
    - Fruits and Vegetables
    - Household
    - Snack Foods
    - Sea Food
- The sale could be imporved by increasing stock of Starchy Foods and Sea Food as rest 3 are already present in stores as Top 5 products by count
- Sale is maximum at Medium and High Size Outlets so the sale can be boosted by increasing the number of High size outlets as presently we have maximum outlets of Medium size.
- Tier 3 and Tier 2 give maximum sales so we can boost the sale by increasing outlets at Tier 2 location as presently we have maximum outlets at Tier 3 location.
- Age of Stores have less impact as the sales is same for almost all the stores except 2, the oldest store is having highest sales and another store established 26 years ago is having least sales.

### *Multivariate Analysis*
- Sales accross Outlet Type is even for both the categories of Fat Content
- Tier 1 and Tier 2 dont have High Size outlets, we can boost the sales by increasing the no of High size outlets in these loctaions, esp Tier 2 as the sales are more in Tier 2 than Tier 1


## **Conclusion**
- Below are the different models as per increasing R2 Score
![Screenshot 2024-05-10 at 13-08-39 Big Mart Sales Prediction](https://github.com/harshitgahlaut/CognoRise_InfoTech_Internship/assets/142779836/af464c28-8857-484b-b3d1-86906c35465d)
- Thus Lasso Regressor is best fit for this dataset with highest R2 Score and minimum Mean Squared Error(MSE) & minimum Mean Absoulute Error(MAE)
 
## End
Thank you for your interest and time. Feel free to give your valuable suggestions and connect with me on https://www.linkedin.com/in/harshitt-gahlaut/
