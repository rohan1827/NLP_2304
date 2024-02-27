##Abstract  

This project utilizes various Natural Language Processing (NLP) techniques to classify/tag news articles. The project uses classification machine learning models to classify news in one of the 8 categories within our training set, which has about 6400 rows and 8 columns. The data is spread over three years from 2022 to 2024.  

Data preprocessing techniques used are cleaning the text data, fixing spellings, removing stop words and punctuation, tokenizing, and lemmatizing. Multiple classification models are implemented along with vectorization techniques such as TF-IDF (Term Frequency Inverse Document Frequency) & Bag of Words to classify the news in one of the categories. 

The results highlight the effectiveness of using a suitable vectorization technique and a classification model in classifying the news article and giving the user a flexibility to consume the category of news they want and switch between them easily. 

##Context and Setting of the Study: 

The creation of an automated system intended to classify news stories into predetermined categories or subjects serves as the study's framework and setting. The difficulties that news organizations, content aggregators, and online news platforms encounter in effectively arranging and displaying a large volume of news content to readers are addressed by this approach. 

This approach automates the task of category tagging for news articles, which is a labour intensive job that requires human effort if done manually. Moreover, in this digital era of rapid data flow requires a quick and less human induced solution. 

To automatically assign pertinent categories to news stories, the automated categorization system makes use of machine learning algorithms and natural language processing techniques. 

By doing so the system achieves the following: 

1.Streamlining the Categorization Process 
2.Improving Content Discovery 
3.Enhancing User Experience 
4.Enabling Personalization 

##Data Collection: 
The initial phase of this project involved gathering the resources for our project. For this we scraped ‘Google News’ to get latest news articles. 

##Dataset Preview (Exploratory Data Analysis) and Pre-processing: 

The next step in the process involved understanding the dataset we were dealing with to have a holistic understanding of the data.  

This included visualizations and basic descriptive analysis of the dataset. We analyzed various plots to understand the dataset better. 

##Data Pre-processing: To guarantee consistency and relevance, the dataset is pre-processed once it is scraped. This includes resolving missing values, cleaning up the text, and getting rid of duplication. The decision on the independent features was made to include them in the model building, which was the title and summary of the article. This step also covered pre-processing of textual data which implements the NLP disciplines of pre-processing i.e., conversion to white space removal, lower text, tokenization, lemmatization, punctuation removal, stop words removal, spell correction etc. 
We extensively checked for any class imbalance in our dataset as a precautionary step before we proceeded with any other step. 

##Vectorization and Model Training: 
We took a streamlined approach to train 3 models namely, Random Forest Classifier, Logistic Regression and Support Vector Classifier based on 2 different vectorization methods namely, Bag of words (Count Vectorizer) and TF-IDF. We built 6 Pipelines to achieve the task of training each model by adopting both vectorization methods.

##Assessment of the Model:  
Performance indicators including accuracy, precision, recall, F1-score, and confusion matrices on the testing set are used to assess each model-vectorizer combination.  
Using the specified evaluation criteria as a guide, comparative analysis is performed to determine which model-vectorizer combination performs best. 
