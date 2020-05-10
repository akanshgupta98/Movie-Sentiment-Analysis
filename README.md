# Movie-Sentiment-Analysis
The dataset used for this project is IMDB 50K dataset from kaggle. This dataset contains 50K instances of movie reviews labeled
as positive and negative. This is very well balanced. 25K instances of positive reviews and 25K instances of negative reviews.
Dataset when analysed was completey pre-processed, no missing value or no blank review. So nothing was done in cleaning of the dataset.
Models used in this project are:
SVM:                accuracy obtained: Training: 98.90 % .  Testing: 89.496 %
Naive-Bayes:        accuracy obtained: Training: 90.82 %    Testing: 86.384 %
Logistic-Regression:accuracy obtained: Training: 92.89 %    Testing: 89.384 %
SGDC:               accuracy obtained: Training: 92.89 %    Testing: 89.384 %

After this, the model SVM was tested on original movie reviews picked from websites.
The model performed as expected labelling positive review and negative. 
1-star review was marked as negative & 5-star review was marked as positive.
3-star review was marked as positive. 
