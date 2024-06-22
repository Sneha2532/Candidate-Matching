# Candidate-Matching
The candidate matching project uses machine Learning to pair candidate with jobs. It involves loading &amp; preprocessing data, combining job attributes, filtering candidate &amp; vectorizing text using TF-IDF. Cosine similarity calculate the match between resumes and job descriptions, identifying the best job for each candidate efficiently and accurately.

# Project involves extensive use of NLP features as in:

- tokenization
- lemmatization 
-	Count Vectorization
-	TF-IDF
# Usage
1. First, ensure you have all dependencies installed by running:

    pip install -r requirements.txt

2. Then, run the main script:

    main.ipynb
# Dependencies:

- pandas: Used to load and manipulate job and candidate data from CSV files.
- re: Used for preprocessing text data by removing unwanted characters and cleaning text.
- nltk: Utilized for natural language processing tasks like removing stopwords.
- WordNetLemmatizer: Used to reduce words to their base forms, improving text normalization.
- TfidfVectorizer: Converts text data into numerical features for similarity calculations.




