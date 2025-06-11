**Flipkart Reviews Sentiment Analysis**

This project performs sentiment analysis on customer reviews from Flipkart using Natural Language Processing (NLP) techniques and machine learning. The goal is to classify reviews as positive or negative based on their content and associated rating.

**🧠 Project Summary**

1. The project follows these steps:

2. Load and clean Flipkart review data.

3. Preprocess text data by removing stopwords and converting to lowercase.

4. Generate visual insights including sentiment distribution and word cloud.

5. Convert text to numerical form using TF-IDF Vectorization.

6. Train a Decision Tree Classifier to predict sentiment.

7. Evaluate model using accuracy score and confusion matrix.

**🧰 Libraries Used and Library	Purpose:**

The following Python libraries are used:

**pandas**                      -         Data loading and manipulation

**nltk** 	                       -        Text preprocessing, stopwords removal

**matplotlib.pyplot**	             -      Data visualization

**seaborn**                  -        Enhanced plotting and heatmaps

**wordcloud**                   -       	Generate word clouds

**sklearn.model_selection**        -  	Splitting data into train/test sets

**sklearn.feature_extraction.text.TfidfVectorizer**  -	Convert text to features

**sklearn.tree.DecisionTreeClassifier**      -    	Train the model

**sklearn.metrics**	                  -            Evaluate model performance


**📊 Visualizations**

**Bar Plot**     -  Shows distribution of positive and negative sentiments.

**Word Cloud** -    Shows most frequent words in positive reviews.


**Sentiment prediction:**  1 (Positive), 0 (Negative)

**Model evaluation using accuracy_score and confusion_matrix**

