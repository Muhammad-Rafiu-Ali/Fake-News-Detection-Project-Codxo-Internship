# Fake-News-Detection-Project-Codxo-Internship
During my data science internship at Codex, I successfully completed a project focused on Fake News Detection using machine learning techniques. The project involved analyzing two datasets downloaded from Kaggle: `fake.csv` and `true.csv`. 

**Dataset Description and Exploration:**
The `fake.csv` and `true.csv` files contained news articles labeled as either fake or true, encompassing features such as `title`, `text`, `subject`, and `date`. I conducted thorough data exploration, examining the structure and content of each dataset. This included displaying initial rows, summarizing data types and statistics, and ensuring data cleanliness by checking for missing values (none were found).

**Data Visualization and Analysis:**
To gain insights into the datasets, I employed various visualization techniques. I visualized the distribution of news subjects (`subject`) using count plots for both fake and true news categories. Additionally, I analyzed the most frequent words in the articles using bar plots, highlighting the top 20 words in each category. Furthermore, I compared the article lengths between fake and true news using histograms.

**Model Building and Evaluation:**
For predictive modeling, I implemented a pipeline that utilized a `TfidfVectorizer` for feature extraction and a `MultinomialNB` (Multinomial Naive Bayes) classifier for predicting the authenticity of news articles. The model achieved an impressive **accuracy of approximately 93.6% on the test dataset**. I evaluated the model's performance using a confusion matrix to analyze true positives, true negatives, false positives, and false negatives, and generated a comprehensive classification report that included precision, recall, and F1-score metrics for both fake and true news categories.

**Conclusion and Future Steps:**
In conclusion, the project successfully demonstrated the application of machine learning in detecting fake news with high accuracy. Moving forward, I plan to explore additional text preprocessing techniques and alternative models to further enhance performance. This project not only honed my technical skills but also deepened my understanding of data science methodologies in addressing real-world challenges.

#DataScience #MachineLearning #FakeNewsDetection #InternshipProject
