# UnstructuredDataAnalyticis_for_Craft_Beer_Recommendations

## Introduction
This project focuses on building the foundational components of a recommender system for craft beer enthusiasts. Leveraging a dataset of beer reviews, the system aims to recommend beers based on user-specified attributes.

## Technical Overview

### Libraries and Setup
The project employs a variety of Python libraries to perform web scraping, data manipulation, and analysis:
- `selenium` for automated web browser interaction
- `pandas` for data structuring and manipulation
- `matplotlib` and `seaborn` for data visualization
- `nltk` for natural language toolkit, including stopwords for text analysis
- `scikit-learn` for implementing machine learning algorithms and data processing techniques such as `TfidfVectorizer` and `cosine_similarity`
- `scipy` for scientific and technical computing

### Web Scraping
A Selenium WebDriver is configured to run in headless mode, enabling automated navigation of beeradvocate.com and extraction of detailed beer reviews. The script captures various elements such as beer names, user ratings, and review text.

### Data Collection and Preprocessing
The data is structured into a CSV file containing pertinent review details. Preprocessing steps involve cleaning the text data and converting it into a suitable format for analysis.

### Analysis
The analysis consists of:
- Frequency analysis of words within the reviews to identify key beer attributes.
- Cosine similarity calculations to match user preference vectors with beer review vectors.

## Usage
The system is designed to be interactive, accepting user preferences and providing beer recommendations based on review analysis.
