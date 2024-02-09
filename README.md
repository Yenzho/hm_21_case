# Analytics about some games, Creating of a spam filter for messages
## Project Description

This project involves analyzing video game data and building a basic logistic regression model for classifying text messages as spam.

### Video Game Data Analysis
- Assessing critics' attitudes towards sports games.
- Determining critics' preferences between PC and PS4 games.
- Identifying critics' preferences between shooters and strategies.

### Spam Classification Model
- Converting text to lowercase, removing garbage symbols and stopwords.
- Lemmatizing words and transforming texts into TF-IDF vectors.
- Splitting data into training and testing sets with random_state=42.
- Constructing a logistic regression model and evaluating accuracy on test data.
- Analyzing results using confusion_matrix and creating a dataframe with misclassified messages.
