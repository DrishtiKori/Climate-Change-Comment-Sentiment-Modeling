# Climate Change Sentiment Analysis (NASA Social Media)

## Project Overview

This project analyzes public comments on NASA's climate change posts to understand audience sentiment and build a machine learning model that classifies comments as **Positive, Neutral, or Negative**.

Using **Natural Language Processing (NLP)** techniques and machine learning, the project explores patterns in public engagement and sentiment toward climate-related discussions.

---

# Problem Statement

Public discussions around climate change often generate large volumes of comments and opinions. Analyzing these comments manually is difficult and time-consuming.

The goal of this project is to build a **sentiment classification system** that automatically identifies the tone of comments posted on climate-related social media content.

---

# Business Understanding

Understanding public sentiment can help:

- Identify how audiences react to climate content
- Detect negative or controversial discussions
- Monitor public opinion trends over time
- Support communication strategies for climate awareness campaigns

---

# Dataset Description

The dataset contains **522 comments** collected from NASA’s climate change social media posts.

### Features

| Feature | Description |
|-------|-------------|
| date | Date of the comment |
| likesCount | Number of likes received |
| commentsCount | Number of replies |
| profileName | User identifier |
| text | Comment text |

---

# Project Workflow

The project follows a standard data science workflow:

1. Data Loading  
2. Data Cleaning  
3. Exploratory Data Analysis  
4. Text Preprocessing  
5. Feature Engineering (TF-IDF)  
6. Train-Test Split  
7. Model Training  
8. Model Evaluation  

---

# Exploratory Data Analysis

Exploratory analysis was conducted to better understand the dataset and identify patterns in user engagement.

Key insights explored include:

- Distribution of comment sentiment
- Engagement levels across comments
- Comment length analysis
- Relationship between engagement and sentiment

---

# Feature Engineering

Text data was transformed into numerical features using **TF-IDF Vectorization**, a commonly used technique in NLP for representing text data.

Additional features used in the model include:

- `likesCount`
- `commentsCount`
- `text_length`

These features help capture both **textual information and engagement signals**.

---

# Modeling

Several machine learning models were explored using **Scikit-learn pipelines**.

Models evaluated include:

- Logistic Regression
- Random Forest Classifier

Model performance was evaluated using:

- **Accuracy**
- **F1 Score**
- **Confusion Matrix**

---

# Results

The trained model successfully learns patterns in text to classify sentiment categories.

Key observations:

- Engagement features contribute moderately to sentiment prediction.
- Text-based features remain the strongest predictors.
- Most comments fall into **neutral or positive sentiment categories**.

---

# Key Visualizations

The project includes several visualizations to support analysis and model evaluation:

- Sentiment Distribution
- Comment Engagement vs Sentiment
- Word Cloud of Most Common Terms
- Model Confusion Matrix

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Natural Language Processing (TF-IDF)
