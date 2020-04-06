# NLP
NLP

    import pandas as pd
    import string

    import nltk
    nltk.download('stopwords')
    nltk.download('wordnet')
    nltk.download('punkt')
    
    from nltk.tokenize import sent_tokenize, word_tokenize
    from nltk.corpus import stopwords
    stopwords.words('english')[0:10]
    
    # Stemming
    from nltk.stem import PorterStemmer
    
    #Lemmatization
    from nltk.stem.wordnet import WordNetLemmatizer
    lem = WordNetLemmatizer()
    
    
    #Feature Extration with CV
    from sklearn.feature_extraction.text import CountVectorizer
    from sklearn.metrics.pairwise import cosine_similarity
    cv = CountVectorizer()
    
    #Feature Extration with Tf-Idf
    from sklearn.feature_extraction.text import TfidfVectorizer
    tf=TfidfVectorizer()

    from sklearn.model_selection import train_test_split
    from sklearn.metrics import classification_report, confusion_matrix, accuracy_score
