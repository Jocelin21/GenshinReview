# Genshin's Review Sentiment Analysis
TASK SPECIFICATION:
- Our task is to use a pre-trained BERT model to conduct Sentiment Analysis of Genshin Impact Game reviews from the Google Play Store.
- The goal is for the model to be able to accurately predict the user sentiment towards the game which can be either negative, neutral or positive.
- The final product will be to provide a comprehensive record for developers, current users, and potential users of the Genshin Impact application. The input to the model will be Genshin Impact Game Reviews stored in csv format.

TRAINING:
- epochs: 10

EVALUATION:
- using matthews correlation coefficient from sklearn
- using accuracy score from sklearn
