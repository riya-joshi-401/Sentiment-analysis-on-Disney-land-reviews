# Sentiment-analysis-on-Disney-land-reviews

- The dataset includes 42656 reviews of 3 Disneyland branches - Paris, California and Hong Kong, posted by visitors on Trip Advisor.

<ins>Column Description:</ins>

<li>Review_ID: unique id given to each review</li>
<li>Rating: ranging from 1 (unsatisfied) to 5 (satisfied)</li>
<li>Year_Month: when the reviewer visited the theme park</li>
<li>Reviewer_Location: country of origin of visitor</li>
<li>Review_Text: comments made by visitor</li>
<li>Disneyland_Branch: location of Disneyland Park</li>
<br>
On this dataset I have performed EDA and sentiment analysis of review using metrics like <b>Sentiment Polarity</b> and <b>VADER Polarity</b> in <b>NLP</b> and created <b>wordclouds</b> for better visulaization.This processed data is then feeded to different classifier models to get trained and predict the sentiment of the test reviews.
<br>
<br>
<ins>Models used</ins>
<li>XGBoost - Extreme Gradient Boost alsorithm is based on the Gradient Boosting model which uses the boosting technique of ensemble learning where the underfitted data of the weak learners are passed on to the strong learners to increase the strength and accuracy of the model.</li>
<li>Decision Tree - This algorithm works on the basis of creating tree structures to take decisions</li>
<li>Random Forest - This algorithm works on the concept of emsemble learning.It used bagging technique to train multiple predictors on the same sampled instances to achieve a higher degree of accuracy.</li>
