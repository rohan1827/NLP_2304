Abstract
This project leverages Natural Language Processing (NLP) techniques for the classification of news articles into distinct categories. Utilizing machine learning models, the system classifies news into one of the 8 predefined categories based on a training set comprising approximately 6400 rows spanning three years from 2022 to 2024.

Key data preprocessing steps include text cleaning, spelling correction, stop word and punctuation removal, tokenization, and lemmatization. The project employs various classification models alongside vectorization techniques such as TF-IDF (Term Frequency Inverse Document Frequency) and Bag of Words.

Results underscore the effectiveness of combining a suitable vectorization technique with a classification model, providing users with flexibility in accessing news categories effortlessly.

Context and Setting of the Study
The project addresses the challenges faced by news organizations, content aggregators, and online platforms in effectively categorizing and presenting large volumes of news content. The automated categorization system streamlines the tagging process, offering an efficient solution to the labor-intensive task of manual categorization in the digital age.

Key Objectives:

Streamlining Categorization Process
Improving Content Discovery
Enhancing User Experience
Enabling Personalization
Data Collection
The project initiates with scraping 'Google News' to gather the latest news articles.

Dataset Preview and Pre-processing
Exploratory Data Analysis (EDA) involves visualizing and analyzing the dataset, providing insights for subsequent steps. Pre-processing includes resolving missing values, text cleanup, and deduplication. NLP techniques are applied to preprocess textual data, covering whitespace conversion, lowercasing, tokenization, lemmatization, punctuation removal, stop word removal, spell correction, and addressing class imbalance.

Vectorization and Model Training
Three models (Random Forest Classifier, Logistic Regression, and Support Vector Classifier) are trained using two vectorization methods (Bag of Words and TF-IDF). Six pipelines are constructed to facilitate training for each model-vectorizer combination.

Model Assessment
Performance metrics such as accuracy, precision, recall, F1-score, and confusion matrices are employed to evaluate each model-vectorizer combination. Comparative analysis determines the optimal model-vectorizer combination based on specified evaluation criteria.
