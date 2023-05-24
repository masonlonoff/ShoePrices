# ShoePrices

The dataset that I completeted analysis on is the "Shoe Prices dataset" created by KIATTISAK RATTANAPORN on Kaggle.

https://www.kaggle.com/datasets/rkiattisak/shoe-prices-dataset

There are two files in this repository:

      1: Shoes.ipynb - This file contains initial EDA, data cleansing, and data visualizations based on the dataset.
      
      
      2: ShoesML.ipynb - This file contains ML algorithms that attempt to accurately predict shoe prices. I used Multiple Linear Regression, Polynomial Regression, Support Vector Regression, Decision Trees, and Random Forest models. The SVR and Random Forest models performed the best, so I used add hyperparameters and cross-validation to try to find the best accuracy.     
      
      
      
[Shoes.ipynb](https://github.com/masonlonoff/ShoePrices/blob/main/Shoes.ipynb)
      
      
R^2 Scores for the Base Models:
1) Support Vector Regression: 0.7759174402010507
2) Random Forest: 0.7584145984167422
3) Polymomial Regression (degree = 2): 0.7107181316046094
4) Decision Tree: 0.7021171286922909
5) Polymomial Regression (degree = 4): 0.9157295890970683
6) Polymomial Regression (degree = 3): -4.891521464605143e+18
7) Multiple Linear Regression: -8.259361539486923e+22
