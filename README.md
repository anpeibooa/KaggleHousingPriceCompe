# KaggleHousingPriceCompe
My first attempt of a kaggle competition. This version is a refined version after a brute force solution. 
## Brute force solution： Random Forest Regressor
The brute force solution achieved a score of 0.167ish on the test set. All missing values were filled with 0, no outliers were thrown away and the Prices were not log1p adjusted.
## Refined version: Gradient Boosting Regressor
The refined version achieved 0.146ish to 0.155ish depending on my luck.

## Some thoughts
I did some searches on model improvement and found that using stacking and blending is really beneficial. However, this repo is about my own approach to the problem so I will not apply what I learned from other authors. Also it's interesting that many people are able to get a near perfect score with only one attempt. 


