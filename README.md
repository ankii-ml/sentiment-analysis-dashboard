# Sentiment Analysis Dashboard [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/) [![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)

## Overview
This project implements a Streamlit dashboard designed to classify review sentiment using a lexicon-based model and visualize the sentiment distribution. It's built to be lightweight, avoiding heavyweight dependencies.

## Features
- **Lexicon-based Sentiment Classification:** Utilizes a lexicon model to classify review sentiment as positive, negative, or neutral.
- **Interactive Dashboard:** Provides an interactive Streamlit interface for sentiment analysis and visualization.
- **Sentiment Distribution Visualization:** Visualizes the distribution of sentiments to offer quick insights into the overall sentiment trends.
- **Lightweight Dependencies:** Designed to operate without requiring extensive or complex external libraries, focusing on efficiency.

## Tech Stack
- Python
- NLP (Natural Language Processing)
- Streamlit
- pandas
- Data Analysis

## Setup
To set up the project, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [repository-url]
    cd sentiment-analysis-dashboard
    ```

2.  **Create a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To run the Streamlit dashboard:

```bash
streamlit run app.py

Access the dashboard in your web browser, typically at `http://localhost:8501`.

## Project Structure
```
. (root)
├── app.py              # Main Streamlit application file
├── sentiment.py        # Contains the sentiment classification logic
├── sample_reviews.csv  # Sample dataset of reviews for analysis
├── test_sentiment.py   # Unit tests for the sentiment classification logic
└── requirements.txt    # List of project dependencies

## Interview Questions
1.  How would you enhance the accuracy of the lexicon-based sentiment model without introducing complex machine learning models?
2.  Describe a scenario where a lexicon-based model might perform poorly, and what steps you would take to diagnose and potentially mitigate the issue.
3.  How does Streamlit facilitate rapid prototyping and deployment of data applications like this dashboard, compared to traditional web frameworks?
