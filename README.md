Name:-SUNILVARMA VEERABATTHINI
Company:-CODETECH IT SOLUTIONS
ID:-CT4AI3053
Domain:-ARTIFICAL INTELLIGENCE
Duration:-JUNE 25th,2024 to JULY 25th, 2024
Mentor:-Neela Santhosh Kumar

OVERVIEW OF THE PROJECT TASK1:-
Data preprocessing is a crucial step in the machine learning pipeline, as it ensures that the data is clean and suitable for modeling. Here's a breakdown of the preprocessing steps included in the code:

LOADING THE DATASET:

Reads the dataset from a CSV file into a pandas DataFrame.
Checking for Missing Values:

Identifies missing values in the dataset.

HANDLING MISSING VALUES :

Fills missing values in the 'Age' column with the mean of the column.
Drops any remaining rows with missing values.
Identifying and Encoding Categorical Features:

Identifies categorical features in the dataset.
Applies one-hot encoding to convert categorical features into numerical format.
Splitting Data into Features and Labels:

Separates the dataset into features (X) and labels (y).
SCALING FEATURES!
:

Uses Min-Max Scaler to scale the features to a range between 0 and 1.
Splitting Data into Training and Testing Sets:

Divides the data into training and testing sets for model training and evaluation.
These preprocessing steps are essential to ensure that the data is in the right format and scale, and that it is free of missing values and properly encoded for use in machine learning models.
![Screenshot 2024-07-17 185621](https://github.com/user-attachments/assets/1121e542-453a-4938-bc3d-a1f42dd7db78)



OVERVIEW OF THE PROJECT TASK2:-
NATURAL LANGUAGE PROCESSING (NLP)


Objective
Build a program that determines if a movie review is positive or negative using a machine learning model.

Steps
GET DATA:

Use the movie_reviews dataset from NLTK, which has labeled reviews (positive or negative).
PREPARE DATA:

Shuffle the reviews to mix them up.
Remove common words that don’t help much in sentiment analysis (like "the", "is").
EXTRACT FEATURES:

Pick the most common words from the reviews to use as features.
TRAIN MODEL:

Use the Naive Bayes classifier to learn from the reviews and their labels.
TEST MODEL:

Check how well the model works by seeing how accurately it predicts the sentiment of new reviews.
Classify New Reviews:

Use the trained model to predict whether new movie reviews are positive or negative.
Outcome
The program will print:

ACCURACY: How well the model did on test reviews.
Sentiment: Whether new reviews are positive or negative.

![Screenshot 2024-07-19 132733](https://github.com/user-attachments/assets/4d21a11c-1428-4261-b106-c8079ab8d889)











