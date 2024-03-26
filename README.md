# Online-Toxic-Comment-Classification
This NLP project aims to create a deep learning-based classification model to tackle online toxicity in comments. The objective is to develop a robust model capable of accurately detecting various types of toxicity, such as threats, obscenity, insults, and identity-based hate.

# Overview
The project aims to develop a multi-label classification model using Natural Language Processing (NLP) with Deep Learning techniques to detect different types of toxicity in online comments, such as threats, obscenity, insults, and identity-based hate. The model's purpose is to contribute to a more productive and respectful online discussion environment.

# Dataset
The dataset has 159571 text records obtained by asking 5000 crowd-workers to rate Wikipedia comments according to their toxicity with 6 attributes(toxic, severe_toxic, Obscene, insult, threat, identity_hate(1 for toxic, 0 for non-toxic). Among those, the clean comments are 143346, which is about 90% of the total records. After check, there is no missing values in the columns.

# Approach
* Data loading
* EDA and Visualization
* Cleaning and preprocessing
* Training the Model
* Evaluation
* Conclusion

## NLP Pipeline
Raw Text --> Text Cleaning (Removing punctuations, stop words, notalpha, convert lowercase) --> Lemmatization --> Tokenization --> Vectorization (TF-IDF vectorizer) --> Deep Learning Models

# Dependencies
* Python 3.9 version
## Installations
* NumPy
* Pandas
* matplotlib
* seaborn
* scikit-learn
* Keras
* WordCloud
* NLTK

Have software installed to run and execute a Jupyter Notebook(Anaconda)

# Contributors
Deepak Bhadouria - db3533@drexel.edu

Surendra Pothuri - sp3796@drexel.edu
