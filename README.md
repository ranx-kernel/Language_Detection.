# 🌍 Language Detection

A Natural Language Processing and Machine Learning mini-project that identifies the language of a given text.

## 🎯 Objective

To develop a system that automatically detects the language of input text using Natural Language Processing and Machine Learning techniques.

## 🧠 Algorithms

- Character-level TF-IDF
- Logistic Regression

## 📊 Dataset

Language Detection dataset containing text samples from multiple languages.

## 🛠️ Technologies

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Gradio
- Google Colab

## ⚙️ System Architecture

```text
                 User Text
                     │
                     ▼
             Text Preprocessing
                     │
                     ▼
             Character TF-IDF
                     │
                     ▼
            Logistic Regression
                     │
          ┌──────────┼──────────┐
          ▼          ▼          ▼
       English     French     Spanish
          │          │          │
          └──────────┼──────────┘
                     ▼
           Language + Confidence
