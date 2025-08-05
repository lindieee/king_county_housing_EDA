
# Small EDA project analyzing house sales data 

## Dataset
https://www.kaggle.com/datasets/harlfoxem/housesalesprediction


## Dataset Summary

- About 21.000 entries (= house descriptions).
- Each row in the dataset refers to one house. 
- The houses are described by a number of features, like house size, number of bathrooms, buidling year, quality of neighborhood, last time renovated etc., along with a purchase price.

<br>

![](images/df_head.png)
<br>
<br>

## Interesting insights

### Feature correlation heatmap


![](images/corr_heatmap.png)


- There are some strong feature correlations, e.g. between price and sqft_living (the bigger the house the higher the house price) or price and sqft_living15 (the better the neighborhood the higher the house price).

<br>
<br>

### Real estate market around Seattle in 2014/2015

![](images/real_estate_market.png)

<br>
<br>

### Number of historic* houses for sale per zipcode

![](images/historic_houses_per_zipcode.png)

<br>
<br>

### Price range for historic* houses

![](images/historic_houses_prices.png)

<br>
<br>

### Median house prices per building year

![](images/median_prices_for_all_houses.png)

<br>
<br>

### Median house prices for historic houses per building year

![](images/median_prices_for_historic_houses.png)
