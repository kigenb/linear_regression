PREDICTING HOUSE PRICE USING LIUNEAR REGRESSION

BUSINNESS UNDERSTANDING

Stake holder: Emarld City Realators

Business problem: Emarld City Realators need to provide prospective home seller with guidance improve the values of their homes through using machine learning to estimate the sale  of their properties.

Problem Statement: I will use house data set from King House Sales dataset to build a linear regression model that best predict sales  price  for properties.

DATA UNDERSTANDING

The project uses the king County House Sales dataset.The data set include all data of home sales from 2014 to 2015.
The data  can be found kc_house_data.csv in the folder along with descritpion of feature found in  column_names.md
The original data include sale data for 21,597homes with 20 different features which includes

date - Date house was sold.

price - Sale price (prediction target)

bedrooms - Number of bedrooms

bathrooms - Number of bathrooms

sqft_living - Square footage of living space in the home

sqft_lot - Square footage of the lot

floors - Number of floors (levels) in house

waterfront - Whether the house is on a waterfront

view - Quality of view from house

condition - How good the overall condition of the house is. Related to maintenance of house

grade - Overall grade of the house. Related to the construction and design of the house

sqft_above - Square footage of house apart from basement

sqft_basement - Square footage of the basement

yr_built - Year when house was built

yr_renovated - Year when house was renovated

zipcode - ZIP Code used by the United States Postal Service

DATA PROCESSING

We had to clean daata bbefore making predictive models


Droppind some of the column that were not realting to our  business  question such has the zip code, longitude , lattitude and view.

Dummy encode categeorical variable(Grade)

Modeling

We are showing correlation and using regression coefficients in this analysis to be able to show the relationship between one or more features with sale price.

Using regression and interpreting correlation coefficients is effective for this business problem because it will allow for us to determine how sale price is impacted by different features and to what degree.

Buildng complex models with multiple features allows for us to be able to make more accurate, data-driven predictions.

Regression Results

In our final model comprising all features,our model performance based on the R squared improved from 38% to 47%. 

Our Model Absolute Error improved which is reduced from the base model to 119321 whichh is good.

In our final model, all feature hhave signicantly linear relationship with sale price.

With holding variable constant, the addition of bathroom increase sale by 30000 dollars .

With holding variabble constant,the addition of floor is projected increase sale by 10000 dollars.


![b25680b0-3de0-47a8-aafc-448584188482](https://user-images.githubusercontent.com/104420862/177187548-107e6925-e452-49f9-a173-326dc091a833.png)

 From plot shows that  ncrease number of floors  increases the price of  by 10,000 dollars
 
 

![375b1392-4d8d-4f8a-bb7c-8a00254c8915](https://user-images.githubusercontent.com/104420862/177189960-5ef15b96-950c-4a96-8462-996e0ee2ec66.png)

From the plot above  increase number of bedrooms in house leads to increase price of house bby 30000 dollars

Recommendations

With holding variable constant, the addition of bathroom increase sale by 30000 dollars .

With holding variabble constant,the addition of floor is projected increase sale by 10000 dollars

limitation: Our model only explains 
47 percent of the variation in sale price, so we ought to be cautious with our predictions and conclusions. Further, our final model does have high levels of heteroscedasticity, which violates one of the assumptions of linear regression, such that our conclusions may be premature without additional manipulation of the data.

Next Steps:

Collect more recent sales data for more accurate representation of the market
Investigate influence of zipcode on sale price








