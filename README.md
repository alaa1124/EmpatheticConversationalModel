# Emapathetic Chatbot 
>  **There are challenges in Natural Language Understanding regarding Arabic language, and this is due to the lack of appropriate datasets available for training. So, our goal for this project is to develop an empathetic Arabic conversational chatbot.**

## Installation
> Note: use python 3.8 or later
Install the dependencies if not available.

_for EmpatheticChatbotModel.ipynb_
```sh
pip install langdetect
```
```sh
pip install pyarabic
```
```sh
pip install tashaphyne
```
```sh
!pip install FarasaPy
```
```sh
pip install arabic_reshaper
```
```sh
pip install python-bidi
```
```sh
!git clone https://github.com/aub-mind/arabert.git
```
include this font within the code folder
```sh 
karim-lt-regular.ttf
```


## Roadmap
- **Data Preparation and Exploration**
-- Emotion Grouping
-- Handling Duplicates
-- Standardize text (tashkeel)
-- Normalize Arabic text to standard form
-- Remove non-Arabic characters, numbers, and extra spaces
-- Remove Arabic Stopwords
-- Distribution of Emotions Visualization
-- WordCloud Visualization
- **Feature Engineering**
-- Term Frequency Inverse Document Frequency of records (TFIDF)
-- Bag of Words (BoW)
--Visualization using t-SNE
- **Clustring**
-- K-means
- **Classification**
-- Naive Bayis
-- Support Vector Machine
-- Logistic Regression
- **Error Analysis**
-- Models Performance Measures
- **Deployment**
_in app.py_
-- Model Deployment on Dialog-Flow Conslole




## License
Group 17- oUttawa University, Data Science Application Course Term Project
