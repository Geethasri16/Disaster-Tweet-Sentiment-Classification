🌪️ Disaster Tweet Sentiment Classification  

This project uses Machine Learning and Natural Language Processing (NLP) to classify tweets as disaster-related or non-disaster-related.  
It was developed as part of the APSCHE Major Project in Data Science.


📘 Overview  
During disasters, people often post information and alerts on social media.  
The goal of this project is to automatically detect whether a tweet truly indicates a disaster event.  
By applying machine learning models to real-world Twitter data, this system helps authorities and organizations respond more efficiently during emergencies.


📊 Dataset  
The dataset consists of tweets labeled as “Disaster” or “Not Disaster”.  
Each tweet includes:  
- Tweet text  
- Keywords  
- Location (when available)  
- Label (1 → Disaster, 0 → Not Disaster)

Data preprocessing included:  
- Removing URLs, mentions, hashtags, and punctuation  
- Tokenization and stop-word removal  
- Lemmatization  
- Converting text into numerical features using **TF-IDF Vectorization**


⚙️ Methodology  
1. Data Collection – Imported the tweet dataset from CSV format.  
2. Data Cleaning – Removed noise and handled missing values.  
3. Text Preprocessing – Tokenized, removed stopwords, and lemmatized words.  
4. Feature Extraction – Converted processed text into TF-IDF vectors.  
5. Model Training – Trained multiple ML models.  
6. Evaluation – Compared model accuracy and confusion matrices.  


🧠 Models Used  
- Naive Bayes Classifier
- Logistic Regression 
- K-Nearest Neighbors (KNN)

Each model was evaluated using metrics such as:  
- Accuracy  
- Precision  
- Recall  
- F1-Score  


 📈 Results  
| Model | Accuracy | Precision | Recall | F1-Score |
|--------|-----------|------------|---------|----------|
| Naive Bayes | ~86% | 0.85 | 0.84 | 0.84 |
| Logistic Regression | ~88% | 0.87 | 0.86 | 0.86 |
| KNN | ~80% | 0.78 | 0.77 | 0.78 |

Logistic Regression gave the best overall accuracy and balance between precision and recall.


💡 Future Scope  
- Implement deep learning models like **LSTM** or **BERT** for improved accuracy.  
- Create a **real-time tweet monitoring dashboard** for live disaster classification.  
- Expand the dataset to include regional languages and multilingual tweets.  



 🧰 Tools & Technologies  
- Language: Python  
- Libraries: Scikit-learn, Pandas, NumPy, Matplotlib, NLTK  
- Environment: Jupyter Notebook  



👩‍💻 Author  
Pendyala Geetha Sri 
B.Tech – Computer Science and Engineering (Data Science)  
APSCHE Major Project  



---

