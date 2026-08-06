# Customer Satisfaction Analysis

## Project Overview
This Natural Language Processing (NLP) project examines 1,500+ Amazon product reviews to analyze customer sentiment, evaluate satisfaction scores, and classify user feedback using machine learning techniques in Python.

## Tools & Technologies
* **Language:** Python
* **NLP Libraries:** NLTK (WordNet Lemmatizer, VADER Sentiment Analyzer, Stopwords)
* **Data Manipulation:** Pandas, NumPy, Re
* **Machine Learning:** Scikit-Learn (TF-IDF Vectorizer, Logistic Regression)
* **Visualization:** Matplotlib

## Key Milestones & Workflow
1. **Text Preprocessing Pipeline:** Cleaned raw review text by removing URLs, punctuation, and digits, followed by tokenization, stop-word removal, and WordNet lemmatization.
2. **Sentiment Analysis:** Utilized NLTK's VADER Sentiment Intensity Analyzer to derive sentiment scores and assign positive, neutral, or negative labels.
3. **Machine Learning Classification:** Applied TF-IDF feature extraction (unigrams/bigrams) and trained a Logistic Regression model to classify customer satisfaction levels.
4. **Keyword & Topic Extraction:** Extracted frequent N-gram word distributions to discover key drivers of positive and negative reviews.

## Business Logic & Analysis

### Key Insights (What the data tells us)
* **Mostly Happy Customers:** Over **81%** of product reviews reflect positive sentiment.
* **What People Love:** Customers frequently praise **sound quality**, **battery life**, and **screen readability** using words like *"great sound"*, *"easy to use"*, and *"love"*.
* **Smart Model:** The Machine Learning model was **87.7% accurate** in reading reviews and predicting whether a customer was satisfied or dissatisfied.

### Underlying Causes (Why this is happening)
* **Hardware & Software Issues:** Unhappy reviews mostly come from physical design flaws (like inconvenient button placements) or software limits on downloading files.
* **Unbalanced Data:** Because most reviews were positive, it was harder for the computer model to spot the small number of unhappy customers.

### Recommended Solutions (What to do next)
* **Fix Hardware Flaws:** Share customer feedback about buttons and battery durability directly with the product design team for future models.
* **Automate Support Alerts:** Set up an automatic alert so customer service can immediately message anyone who posts a negative review.
* **Improve the Model:** Balance the training data in future iterations so the AI gets better at flagging frustrated customers early.
