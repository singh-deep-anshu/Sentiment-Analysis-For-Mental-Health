# Sentiment Analysis for Mental Health

This project applies **Natural Language Processing (NLP)** and **Machine Learning** to classify text related to mental health into positive and negative sentiments.  
The goal is to leverage sentiment insights for potential applications in **mental health monitoring, chatbots, and early intervention systems**.

---

## Features
- Data preprocessing with **NLTK** (tokenization, stopword removal, lemmatization).
- **TF-IDF vectorization** for feature extraction.
- Multiple ML classifiers implemented and compared:
  - Logistic Regression
  - Random Forest
  - AdaBoost
  - Decision Tree
- Model evaluation using **accuracy, precision, recall, F1-score, and confusion matrix**.
- Visualizations with **Seaborn, Matplotlib, and Plotly** for data exploration and results.

---

## Tech Stack
- **Languages**: Python
- **Libraries**: Pandas, NumPy, NLTK, Scikit-learn, Seaborn, Matplotlib, Plotly
- **ML Algorithms**: Logistic Regression, Random Forest, AdaBoost, Decision Tree

---

## Workflow
1. **Data Preprocessing**
   - Removed null values and duplicates.
   - Tokenized text and applied stopword removal + lemmatization.

2. **Feature Engineering**
   - Converted text into numerical features using **TF-IDF**.

3. **Model Training**
   - Trained multiple classifiers and tuned hyperparameters with GridSearchCV.

4. **Model Evaluation**
   - Compared models using accuracy, precision, recall, F1-score.
   - Visualized results with confusion matrices.

---

## Results
- Achieved **76% accuracy** with Decision Tree.
- Random Forest and AdaBoost provided robust performance with balanced precision and recall.
- TF-IDF effectively highlighted mental health-related keywords like *“anxiety”*, *“stress”*, *“depressed”*.

---

## Project Structure
```
├── sentimentAnalysis.ipynb   # Jupyter Notebook with code and experiments
├── data/                            # Dataset
└── README.md                        # Project documentation
```

---

## Applications
- Early detection of negative sentiment in online communities.
- Supporting **mental health professionals** with sentiment trends.
- Integrating into **chatbots** for empathetic and context-aware responses.

---

## Author
- **Deepanshu Singh**  
- B.Tech, IIIT Allahabad  
- [GitHub](https://github.com/singh-deep-anshu) | [LinkedIn](https://www.linkedin.com/in/deep-anshu/)
