# NLP
NLP

    import pandas as pd
    import string

    import nltk
    nltk.download('stopwords')
    nltk.download('wordnet')
    nltk.download('punkt')

    from nltk.corpus import stopwords
    stopwords.words('english')[0:10]

    from sklearn.model_selection import train_test_split
    from sklearn.metrics import classification_report, confusion_matrix, accuracy_score
