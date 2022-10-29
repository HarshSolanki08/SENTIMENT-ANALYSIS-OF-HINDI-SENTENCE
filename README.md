
# SENTIMENT ANALYSIS OF HINDI SENTENCE

Our proposed system for sentiment analysis of Hindi sentence
review uses HindiSentiWordNet (HSWN) to find the overall sentiment associated
with the document; polarity of words in the review are extracted from HSWN and
then final aggregated polarity is calculated which can sum as either positive,
negative or neutral. Synset replacement algorithm is used to find polarity of those
words which don’t have polarity associated with it in HSWN. In addition to this,
impact of the negation and discourse rules are investigated for Hindi sentiment
analysis.

## NLP Techniques Used 

- Word tokenization 
- POS Tags
- Stop Word Removal
- Lexicon Based Approach

## Tech Stack

**Client:** Streamlit

**Server:** Python


## Installation

Following are the steps to Installation and setup

```bash
install requirements 
    - nltk==3.7
    - pandas==1.3.2
    - pandas-datareader==0.10.0
    - pandas-ods-reader==0.1.4
    - sklearn==0.20
    
To run the project follow the steps:
    - Open the project in any code editor (VS Code)
    - Open new terminal and type command
    - streamlit run app.py

Local Host server will start
```

## Screenshots

![image](https://user-images.githubusercontent.com/72189356/198843732-855ddfd0-008e-4ed2-b27a-c1dceff5b496.png)

![image](https://user-images.githubusercontent.com/72189356/198843757-acb2b43b-119d-4923-8464-08f79bd7a92e.png)

## Documentation

[Project Report](https://drive.google.com/file/d/1MJyrunFod00fsa8-JlhnZ0_hosHT1pGd/view?usp=share_link)

[Source Code](https://github.com/HarshSolanki08/SENTIMENT-ANALYSIS-OF-HINDI-SENTENCE)

## Authors & contributor

- Harshbhai Solanki
- Nirav Satra
- Abdul Qadir
