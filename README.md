# ShoePrices
![image](https://github.com/masonlonoff/ShoePrices/assets/117112918/f95c8965-c707-4e7e-a1e9-417a872f542f)


## Description
This dataset contains information about the sales of shoes in a particular region. The data includes information on the brand, model, type of shoe, gender, size, color, material, and price.

Column Details:

**Brand**: The brand of the shoe, such as Nike, Adidas, or Reebok.\
**Model**: The specific model name or number of the shoe, such as Air Jordan 1, Ultra Boost 21, or Classic Leather.\
**Type**: The type of shoe, such as running, casual, or skate. This column describes the intended use or function of the shoe.\
**Gender**: The gender the shoe is designed for, such as men, women, or unisex. This column specifies the target demographic for the shoe.\
**Size**: The size of the shoe, using US sizing. This column indicates the length of the shoe in inches or centimeters.\
**Color**: The color of the shoe's exterior. This column describes the predominant color or color combination of the shoe.\
**Material**: The primary material of the shoe, such as leather, mesh, or suede. This column indicates the material that comprises the majority of the shoe's construction.\
**Price**: The price of the shoe, in US dollars. This column specifies the cost of purchasing the shoe.\

## Acknowledgement
The dataset that I completeted analysis on is the "Shoe Prices dataset" created by KIATTISAK RATTANAPORN on Kaggle.

https://www.kaggle.com/datasets/rkiattisak/shoe-prices-dataset

There are two files in this repository:

      1: Shoes.ipynb - This file contains initial EDA, data cleansing, and data visualizations based on the dataset.
      
      
      2: ShoesML.ipynb - This file contains ML algorithms that attempt to accurately predict shoe prices. I used Multiple Linear Regression, Polynomial Regression, Support Vector Regression, Decision Trees, and Random Forest models. The SVR and Random Forest models performed the best, so I used add hyperparameters and cross-validation to try to find the best accuracy.     
      
      
      

      
### R^2 Scores for the Base Models:
1) Support Vector Regression: 0.7759174402010507
2) Random Forest: 0.7584145984167422
3) Polymomial Regression (degree = 2): 0.7107181316046094
4) Decision Tree: 0.7021171286922909
5) Polymomial Regression (degree = 4): 0.9157295890970683
6) Polymomial Regression (degree = 3): -4.891521464605143e+18
7) Multiple Linear Regression: -8.259361539486923e+22
