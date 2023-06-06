# Sentimental_Analysis
Analysing sentiment using movie review
This sentiment analysis project focuses on analyzing movie reviews to determine the sentiment expressed in each review. The project utilizes a combination of clustering, semi-supervised learning, and classification techniques to achieve accurate sentiment classification.

The project begins with a clustering phase, where unsupervised clustering algorithms, such as K-means, are applied to group similar movie reviews together. This clustering step helps in identifying patterns and similarities among the reviews.

Next, a semi-supervised learning approach is employed to leverage the labeled data available(around 80 entries from the 40,000 entries). The initial labeled data, consisting of a subset of movie reviews with sentiment labels, is used to train a sentiment classification model. This model is then applied to assign sentiment labels to the remaining unlabeled data.

In the final step, a supervised classification algorithm, such as Naive Bayes, Logistic Regression, and Support Vector Machines (SVM), is trained using the labeled data and the assigned sentiment labels from the semi-supervised learning phase. This trained classifier can then be used to predict the sentiment of new, unseen movie reviews.
