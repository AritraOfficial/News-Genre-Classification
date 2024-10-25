# News-Genre-Classification
This project focuses on classifying news headlines into various genres, such as Politics, Business, and Sports, using Natural Language Processing (NLP) techniques. The dataset used for this project was collected through web scraping from The Times of India and Hindustan Times.

## Project Overview
The primary objective of this project is to build a machine learning model that can accurately predict the genre of a news headline. Various classifiers are evaluated, and ensemble learning methods are implemented to improve performance.

## Key Features
Data Collection: Web scraping from news sources like Times of India and Hindustan Times.
Data Preprocessing: Tokenization, removing stop words, and transforming text into numerical vectors using TF-IDF and CountVectorizer.
Modeling: Multiple classifiers, including ensemble learning techniques, are used to boost accuracy.
Evaluation: An accuracy score is used as the evaluation metric.
Dataset
Dataset Name: TOI_News.csv
Columns:
Headline: The news headline text.
Genre: The genre/category of the headline (e.g., Politics, Business, Sports).

## Installation
# Clone the repository
git clone "https://github.com/username/news-genre-classification.git"

# Change directory
cd news-genre-classification

# Install dependencies
pip install -r requirements.txt

# Project Structure
news-genre-classification/
├── data/
│   └── TOI_News.csv              # Dataset file
├── notebooks/
│   └── exploratory_analysis.ipynb # Exploratory Data Analysis notebook
├── src/
│   ├── preprocess.py              # Data preprocessing script
│   ├── train_model.py             # Model training script
│   └── evaluate.py                # Evaluation script
├── requirements.txt               # Dependencies
└── README.md                      # Project documentation

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
