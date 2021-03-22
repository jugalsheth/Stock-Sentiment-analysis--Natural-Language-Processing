![image](https://user-images.githubusercontent.com/49743328/111950312-78c93580-8ab8-11eb-8ee3-432bc39af2fa.png)

# Stock-Sentiment-analysis
Performed a Stock sentiment analysis classification problem with News headline data

# Motivation
My choice of getting into the realm of Data was because of Finance, after reading the book Rich Dad Poor Dad, and learning about investment from family, relaives and looking at trends, reading about stock market scams which changed the whole finance landscapes of countires, swayed me into dabbling my hands on NLP with data

# Process
- Pandas to load the csv
- Splitting data into train and test based on dates
- used regex to replace all the unnecessary symbols with space keeping only a-zA-Z
- Lowered the letters in data in order to avoid duplication while performing NLP
- Combined the sentences on all columns for same rows in order to form sentences 
- This time intead od using NLTK , we used sklearn to call CountVectorizer, in order to convert the sentences to vectors
- Performed classification using RandomForest Enseble
- metrics like confusion matrix, accuracy_Score and classification_report gives us a good idea of performance

