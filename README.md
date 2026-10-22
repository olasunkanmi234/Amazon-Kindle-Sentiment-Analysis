# Amazon Kindle Store Review Sentiment Analysis

## Project Overview
In this project, I use Python, Natural Language Processing (NLP), and machine learning to analyze Amazon Kindle Store customer reviews and classify sentiment as positive or negative based on customer ratings. The goal is to explore customer opinions, identify sentiment patterns and evaluate how effectively machine learning models can classify reviews.

## Dataset
The dataset contains approximately 982,619 Amazon Kindle Store reviews, covering the period from 2000 to 2014, according to the original project report.

**Dataset sources:**
- [UCSD Amazon Product Data](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon/links.html)
- [Kaggle – Amazon Kindle Reviews](https://www.kaggle.com/code/akashbangalkar3/amazon-kindle-reviews-acc-score-93/data)
- [Related GitHub Project](https://github.com/dillon-quan/Amazon-Kindle-Reviews---Sentiment-Analysis)

Sentiment labels:
- Ratings of 3–5: Positive
- Ratings of 1–2: Negative

## Tools and Technologies
- Python, Pandas and NumPy
- Scikit-learn and NLTK
- Matplotlib and Seaborn
- Jupyter Notebook

## Methodology
1. Data exploration and cleaning
2. Text preprocessing
3. Text vectorisation using CountVectorizer and TF-IDF
4. Machine learning model training
5. Model evaluation

## Results

The original report records approximately **91% accuracy** for the initial Multinomial Naive Bayes model and **87%** for the tuned model on test data. These results have not been independently reproduced.

### Customer Rating Distribution

![Customer Rating Distribution](sentiment_distribution.png)

This chart visualises the distribution of customer ratings in the dataset. It helps show how customer feedback is distributed across rating levels.

### ROC Curve

![ROC Curve](images/roc_curve.png)

The ROC curve illustrates the model's ability to distinguish between positive and negative reviews at different classification thresholds. A curve closer to the top-left corner generally indicates better classification performance.

## Project Files
- [Jupyter Notebook](sentiment_analysis.ipynb)
- [Project Report](reports/project_report.pdf)
- [Project Presentation](reports/project_presentation.pdf)

## Author
**Olasunkanmi David Adisa**
