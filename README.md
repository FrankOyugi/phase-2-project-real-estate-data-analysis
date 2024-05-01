## Real Estate Development For King County, Washington

![alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/silviagworit/Desktop/images.jpg?version%3D1714502309504)

## Business Overview
The real estate market in King County is characterized by its dynamic nature, driven by factors such as population growth, economic trends, and housing demand. The county's diverse geography offers a wide range of housing options, from townhouses to suburban single-family homes and waterfront properties. The King County Housing Data Set provides information about houses in King County, including their size, location, condition, and other features. The objective of this project is to create multiple regression models that can accurately predict the price of a house.

The project is commissioned by a commercial real estate agaency interested in assisting homeowners to buy or sell homes within specific areas. Their main concerns revolve around obtaining predicted prices for homes in the area based on renovation and further assessing any notable disparities between the actual prices and our model's predicted prices.

## Business Understanding 
The primary goal of the client is to create a platform that delivers accurate estimates of house prices which are crucial for both buyers and sellers in King county. To achieve this objective we need to develop a model that can identify the key factors influencing house prices. To effectively train this model the client requires precise and representative data related to the real estate market in king county, including historical sales, current listings, property size, and other relevant features.

Once trained successfully the model will be capable of providing accurate estimations of house values based on their features. It can then seamlessly integrate into the platform offering reliable price estimates to both buyers and sellers.

This information derived from the model will empower buyers and sellers to make informed decisions regarding property transactions. By leveraging technology to provide a dependable and precise platform for buying and selling houses in king county, the client aims to esgablish themselves as a trusted authority in the local real estate market thus attracting a loyal customer base.

QUESTIONS

1. To find which features have the highest correlation to the home price
2. To find out if the view of a home affects its value
3. To discover which combination of features leads to the highest values of homes.

## Data Understanding and Analysis
For this project, we will be using the King County House Sales dataset, which contains 20 columns and over 21500 records, covering house sales between May 2014 and May 2015. The data is suitable for the project as it provides relevant information about the features that affect the house prices in King County.

The King County House Sales dataset contains the following columns;

Price - Sale price (prediction target)

bedrooms - Number of bedrooms,

bathrooms - Number of bathrooms,

sqft_living - Square footage of living space in the home,

sqft_lot - Square footage of the lot,

floors - Number of floors (levels) in house,

view - Quality of view from house,

condition - How good the overall condition of the house is. Related to maintenance of house,

grade - Overall grade of the house. Related to the construction and design of the house,

sqft_above - Square footage of house apart from basement,

sqft_basement - Square footage of the basement,

yr_built - Year when house was built,

yr_renovated - Year when house was renovated,

zipcode - ZIP Code used by the United States Postal Service,

sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors,

sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors, and

sell_yr - Date house was sold.

Some limitations of the data that may have implications for the project are:

The data may not reflect the current market conditions as it was collected from 2014 to 2015.

The data may not capture all the factors that affect the house prices such as the interest rates and the economic situation.

The data may have some outliers or errors that need to be handled carefully during the analysis. For example, there is a house with 33 bedrooms which seems unrealistic.

## Regression Results
From our models it will be in our best interest to pick the Model offerring the lowest error and the Highest R-squared value.

This model is model 4 with Hence, we picked model 4 with an R squared of 0.678 and an Error of 208713 which is the least error among our models.

## Recommendations 
1. The client should focus on homes with views, more bedrooms, bathrooms and even larger square feet when trying to earn high commission during sale of homes.
2. Client should encourage homeowners to expand the squarefootage during construction to maximize their selling prize.
3. The client needs to focus on homes that are average and above to sell quick and earn higher commissions.

## Conclusion
1. Key factors in determining prices are Bedrooms
Bathrooms, Square foot-living, Year built, Year renovated, Grade and
view.
2. Regular retraining of the model with updated data is necessary to capture any market trends.