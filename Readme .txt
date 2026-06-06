# Sentiment Analysis Dashboard

An NLP-powered sentiment analysis dashboard that analyzes user-provided text and social media content to classify sentiments as Positive, Negative, or Neutral.

## Overview

This project combines Natural Language Processing (NLP), Machine Learning, and an interactive web interface to provide real-time sentiment analysis.

Users can:

- Analyze custom text
- Analyze Twitter/X content using keywords
- Visualize sentiment distribution
- View sentiment insights through an interactive dashboard

---

## Features

- Real-time sentiment prediction
- Twitter keyword-based sentiment analysis
- Custom text sentiment analysis
- Interactive web dashboard
- Sentiment distribution visualization
- Data preprocessing pipeline
- Transformer-based NLP model

---

## Tech Stack

### Backend
- Python
- Flask
- TensorFlow
- Hugging Face Transformers
- Pandas
- NumPy

### Frontend
- HTML
- CSS
- JavaScript
- Chart.js

---

## Project Structure

```text
Sentiment_analysis/
│
├── app.py
├── preprocess.py
├── data_preprocessing.py
├── finetuning.py
├── save_model.py
├── requirements.txt
│
├── index.html
├── styles.css
├── script.js
│
├── sample_data1combined_dataset.csv
├── sample_datacombined_dataset.csv
│
├── twitter-icon.png
├── instagram-icon.png
└── text-icon.png
```

## Installation

Clone the repository:

```bash
git clone https://github.com/dhriti-29/Sentiment_analysis.git
cd Sentiment_analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

---

## Supported Analysis Types

### Twitter Sentiment Analysis

Analyze tweets based on:

- Keyword
- Tweet limit
- Language selection

### Custom Text Analysis

Enter custom text and instantly receive sentiment predictions.

---

## Future Enhancements

- Instagram sentiment analysis
- BERT fine-tuning
- Multi-language support
- Advanced analytics dashboard
- Cloud deployment

---

## Author

Developed as a Machine Learning and NLP project focused on social media sentiment intelligence and text analytics.
