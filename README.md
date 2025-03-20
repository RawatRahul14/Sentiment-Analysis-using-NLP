# Sentiment-Analysis-using-NLP

## Content
- [Objective](#objective)
- [Dataset Overview](#dataset-overview)
- [Setup and Installation](#setup-and-installation)

### Objective
The goal of this assignment is to build a sentiment analysis system using the Bag of Words (BoW) and TF-IDF techniques. The task involves preprocessing a dataset, cleaning and tokenizing text using regular expressions (regex) in Python, and applying at least three machine learning models to classify the sentiment of given text data. Finally, the performance of these models will be evaluated and compared to determine the best-performing approach.


### Dataset
A dataset scraped from the internet containing text with missing values, non-character symbols, and ASCII codes will be provided. The dataset must be cleaned and preprocessed before applying sentiment analysis.

### Dataset Overview
- Columns:
    - text: Contains user reviews/comments
    - sentiment: Binary sentiment label (1 for positive, 0 for negative) 

- Issues to Address:
    - Missing values 
    - Special characters, ASCII codes, and non-character data 
    - Tokenization & vectorization using BoW and TF-IDF 

### Setup and Installation

1. Clone the Repository.

```bash
git clone https://github.com/RawatRahul14/Sentiment-Analysis-using-NLP.git
```

2. Open the folder in the VS code.

```bash
cd Sentiment-Analysis-using-NLP
code .
```

3. After opening the folder in the VS code, insert the below code in the terminal.

```bash
python -m venv .venv
```

4. Activate the virtual environment each time.
```bash
.venv\Scripts\activate
```

5. Update the pip using the below command.

```bash
python.exe -m pip install --upgrade pip
```

6. Install the required packages.

```bash
pip install -r requirements.txt
```