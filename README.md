# emojiRecommendation
The emoji recommendation system shortens the amount of time spent on inputting emoticons, leading users to more frequently use emoticons in instant messengers thus to deliver nonverbal cues in efficient ways.

I collected 1,578,612 Twitter data containing facial emojis and separated sentences from emojis. 
Then, I used the VADAR package to quantify three traits of the sentiment for each sentence: negative, neutral, and positive. 
I used sentiment scores of each sentence as features and its emojis as targets and applied them to Decision Trees, Support Vector Machine, and Gaussian Naive Bayes.
I confirmed that the algorithm can suggest contextually suitable emojis for any random sentence.
