# lead_scoring
A good example of detailed data exploration with plenty of graphs<br>
Some features were bucketed instead of using continuous features.

dummify function - To create dummy for a categorical feature and return with dummy features.
Countplots and binary maps
Manual Bucketing using pd.cut and Usage of WOE technique although it was not useful in this problem.
Using group by to get useful information on features and data.
sns.lineplots, Mean target encoding using dictionary map.
Custom bucketing with details in dense area of dist plot and less deatiled buckets in light areas.
pd.merge usage, sns.heatmap with custom cmap = YlGnBu.

Using statsmodels.api for logistic regression and code to check VIFs (Multicollinearity) easily.

## Model Evaluation
Draw roc function, the precision recall plot, confusion matrix with full specificity, sensitivity and TPR, FPR etc...
