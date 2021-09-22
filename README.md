# Amazon-Alexa-Reviews---Sentiment-Analysis

## Project Goal
Amazon needs to understand customer satisfaction and sentiment for their Alexa products as of July 2018 so they can take decisions related to product and assortment. 
This sentiment analysis project extracts and analyzes sentiment of Alexa's customer reviews to answer the following questions:

1.Which are the most reviewed product variations?

2.Which words are the most used by customers to describe their satisfaction w/Alexa?

3.Which are the products with most positive reviews and highest ratings?

4.Which are the products with most negative reviews and lowest ratings?

5.Which are the most popular benefits of Alexa that customers enjoy and which ones they dislike?

6.Which is the most accurate and appropriate model to classify reviews sentiment moving forward?

## Approach: The analytics tasks

1.Data Pre-processing

2.Finding the most reviewed Alexa variations

3.Finding the variations with the highest and lowest ratings

4.Finding the most used words – Cloud, frequency of words

5.Understanding context of reviews - Concordance and Collocations

6.Sentiment Analysis: The most negative and most positive reviews

7.Sentiment Analysis: Finding sentiment polarity and relationship with ratings

8.Classifying reviews: Creating models & selecting the best fit

## Findings and Conclusions

1.The variations with the most negative reviews are Black spot, Black and Black Plus. The most negative reviews focus on speaker volume, privacy and general quality.

2.The most popular Alexa’s benefits that customers enjoy are easiness to set up and use, size of echo, the turning-lights-off feature. Lastly, they “just love it!” “Its exactly how its expected”.

3.Alexa’s difficulty to understand voice and reply back  with correct responses is one of the drawbacks that customers have commented the most.

4.The logistic regression model presents the highest accuracy to classify sentiment in customer reviews for Alexa, at 96.15%. Therefore, it is, so far, the most appropriate model that Amazon can use to classify reviews moving forward

5.Black Dot, Charcoal, Fire TV stick, Black Plus and Black Snow are the most reviewed products. 

6.The most used words to describe Alexa variations by customers are positive or neutral, being the top ten: Love, echo, great, alexa, music, like, use, works, easy and sound

7.The variations that have the most positive reviews are Heather Grey and Charcoal mainly, due to speaker volume and quality as well as easiness to set up

8.The variations with highest ratings that have a significant number of reviews are Charcoal, Heather Grey and FireTV Stick

## Recommendations 

1.Charcoal, Heather Grey and Fire TV Stick are the products with most positive reviews and highest ratings. They are the most loved products out of the entire variations, and it could even add to good sales. Hence, its recommended that Amazon should focus in marketing and sales efforts for the product with most positive reviews

2.White, Black and White Snow are products with most negative reviews and lowest ratings. These variations are the least popular and the sales for these could also be low. Hence it could be recommended that Amazon discontinues the production for these least likeable variations as these products could damage Alexa's line brand image

3.Amazon is doing great in terms of its sound quality and easy to set up features. However, the natural language processing(NLP) feature needs to improved for future Alexa releases

4.Based on the high accuracy results for both the models, the dataset must be reviewed to find if there is any bias or problem that occurred during the data processing step

5.To enhance the validation process of the model, it is recommended to split the dataset into 3 parts ie., train, validation and test set

6.Additional models should be created and evaluated to ensure that the model with the best fit will be used by Amazon

