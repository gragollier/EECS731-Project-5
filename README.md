# EECS 731 - Project 5: Time Series
*Grant Gollier*

## Dataset

The dataset contains product demand over a span of several years and came from [here on Kaggle](https://www.kaggle.com/felixzhao/productdemandforecasting). I will try to include it in the repository, but if Github doesn't let me upload it just download the dataset and rename the csv to `Historical_Product_Demand.csv` and place it in the `data` directory.

## Analysis

Overall, I think my results were pretty good. However, both models I tried didn't do a great job of handling outliers which I guess is to be expected since those are most likely due to demand spikes that wouldn't be due to date alone, but maybe some other outside factor such as a sale or ad campaign. To see a more indepth discussion please look at the [Time Series Notebook](notebooks/1-Time_Series.ipynb).