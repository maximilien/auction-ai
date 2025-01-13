### Exploring Luxury Auction 

**E. M. Maximilien**

#### Executive summary

In this project we are exploring luxury auction data and attempt to answer the question:

`What are the key factors that help increase selling prices of luxury auction items?`

#### Rationale

During the pandemic, the luxury industry saw a radid increase in luxury purchases and collecting, e.g., wristwatches. While this lasted a few years, the rapid decline in interst and increase in prices (inflation) caused a reverse. These twin facts imply that there will be an increase of luxury items on the market and at auctions houses.

#### Research Question

What are the key factors that help increase selling prices of luxury auction items?

#### Data Sources

[CSV](luxury_auction.csv) file from [Kaggle](https://www.kaggle.com/datasets/onlineauctions/online-auctions-dataset)

#### Methodology

* Use basic explorary data analysis
* Build regression and classifier models
* Hyperparameter tuning of models

#### Results

* `SVC` had the best accuracy to predict which item would sell and price but took long time to improve
* `LinearRegression` was good enough with accuracy score close to the best models
* Most important features were `bidder_rate` and rhe `price`
* The `auction_type` also helped determine the `price` and likely the `bidder_rate`
* The `bidder_rate` increase correlated with `price` increase
* The `bidder` had little impact on resulting `price`

#### Next steps

* Explore what features we could discard
* Explore the most important features in the best models
* Explore whether bid time impact sell price
* Explore if bidder had impact on sell price

#### Outline of project

- [Link to notebook](auction-ai.ipynb)

##### Contact and Further Information

[mmaximilien at Gmail](mailto:mmaximilien+auction-ai@gmail.com)
