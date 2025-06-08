1. Data Loading
Read the dataset using Pandas.

2. Exploratory Data Analysis (EDA)

   
3. Text Preprocessing

        Convert text to lowercase.
        Remove punctuation and special characters.
        Remove stopwords using NLTK.
        Apply lemmatization (using WordNetLemmatizer).

4. Feature Engineering

       TF-IDF Vectorization with max 1000 features to transform text into numerical form.

5. Label Encoding
Map Product labels to integers.

        Credit reporting → 0
        Debt collection → 1
        Consumer Loan → 2
        Mortgage → 3

6. Model Training
Train multiple models:

        Logistic Regression
        Decision Tree
        SVM (Support Vector Machine)

7. Evaluation

       Accuracy Score
       F1 Score (weighted)
