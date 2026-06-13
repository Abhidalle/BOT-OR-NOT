# BOT or NOT
Bot or Not model will instantly tell if the email you were send is spam or ham. Which meand if it is was actually sent by a real person or by automated bots. This model has an accuracy of 96%(and f1 score of 94% as well for the nerds). This model was deployed using the streamlit and used the random forest classifier model to effectively identify bots. I trained this model using dataset that has over  5000 rows of datasets and 1 million different words for the Ai to see.

## Data Extraction 
I found this clean dataset form kaggle, to follow along you can download this from the link given below:
https://www.kaggle.com/datasets/venky73/spam-mails-dataset/data
(Note: This link takes you to the kaggle website)

## System Architecture & Project Structure
1. Text Preprocessing: Cleans up the text by removing useless words like "the" or "is" and cutting words down to their root form (like turning "running" into "run").
2. Vectorization: Translates human words into a list of numbers so the computer can actually run math equations on the sentence.
3. Classifier: An AI brain(THE MODEL) made of 50 mini-decision charts that look at the numbers, vote together, and calculate the exact confidence percentage.
4. Frontend & Deployment: Streamlit runs the Python AI logic on a live server, while Vercel hosts a clean HTML front door page with a launch button that i built.
## AI Use Declaration
I havent really used any AI in this project but on times when i was stuck and wasnt able to debug the issues. But i did use some AI when i was looking for ways to make it a bit more functional(By asking it to suggest me 10 more ways this can be better and etc)


]


