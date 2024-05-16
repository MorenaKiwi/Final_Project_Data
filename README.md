### Sentiment Analysis and Text Classification README

#### Question 1:

- **Data Description:**
  - The IMDb dataset "movie_data.csv" file contains 25,000 highly polar 'positive' (12,500) and 'negative' (12,500) IMDB movie reviews.
  - "amazon_data.txt" and "yelp_data.txt" contain 1000 labeled negative and positive reviews each.

- **Tasks:**
  a) Read all data files (.csv and .txt) into Pandas DataFrames, splitting each dataset into 70% training and 30% test sets.
  b) Utilize CountVectorizer and TfidfVectorizer from sklearn library to perform Logistic Regression classification on the IMDb dataset and evaluate accuracies on the test set.
  c) Classify the Amazon dataset using Logistic Regression and Random Forest Classifiers, comparing their performances and displaying confusion matrices.
  d) Generate a classification model for the Yelp dataset using K-NN algorithms. Fit and test the model for different values of K (from 1 to 5) and record and plot the testing accuracy.
  e) Generate predictions for provided reviews using a Logistic regression classifier on the Amazon dataset.

#### Question 2:

- **Data Description:**
  - The 20 Newsgroups dataset comprises approximately 20,000 newsgroup documents, evenly divided across 20 different newsgroups.

- **Tasks:**
  a) Perform Logistic Regression classification on the training set using both CountVectorizer and TfidfVectorizer separately from the sklearn library. Display the confusion matrix and accuracy by predicting class labels in the test set.
  b) Perform Logistic Regression classification and display the accuracy of the test set.
  c) Perform K-means Clustering on the training set with K=20.
  d) Plot the accuracy (Elbow method) of different cluster sizes (5, 10, 15, 20, 25, 30) to determine the best cluster size.

#### Question 3:

- **Data Description:**
  - The Medical dataset "image_caption.txt" contains captions for 1000 images (ImageID).

- **Tasks:**
  a) Read all data files into Pandas DataFrame.
  b) Perform necessary pre-processing tasks (e.g., punctuation, numbers, stop word removal, etc.).
  c) Create a Term-Document Matrix with TF-IDF weighting.
  d) Calculate the similarity using Cosine similarity measure and display the top ten ranked images based on a provided query.
