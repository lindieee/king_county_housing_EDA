
# Small EDA project analyzing house sales data 

## Dataset
https://www.kaggle.com/datasets/harlfoxem/housesalesprediction


## Dataset Summary

- about 21.000 entries (= house descriptions)
- The dataset contains features like house size, number of bathrooms, buidling year, quality of neighborhood, price, etc.

<br>

<div style="text-align: left"><img src="images/df_head.png" width="700" height="150" /></div>

<br>
<br>

## Interesting insights

### Correlation heatmap

<img src="images/corr_heatmap.png" width="500" height="350">

- There are some strong feature correlations, e.g. between price and sqft_living (the bigger the house the higher the house price) or price and sqft_living15 (the better the neighborhood the higher the house price).

<br>
<br>

### Real estate market around Seattle in 2014/2015
<img src="images/real_estate_market.png" width="500" height="270">

<br>
<br>

### Number of historic* houses for sale per zipcode

<img src="images/historic_houses_per_zipcode.png" width="500" height="300">

<br>
<br>

### Price range for historic* houses

<img src="images/historic_houses_prices.png" width="500" height="230">

<br>
<br>

### Median house prices per building year

<img src="images/median_prices_for_all_houses.png" width="400" height="250">

<br>
<br>

### Median house prices for historic houses per building year

<img src="images/median_prices_for_historic_houses.png" width="400" height="250">