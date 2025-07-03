# Save a README
readme_text = """# Sentiment Analysis using TF-IDF + Logistic Regression

This project uses the IMDB 50K movie review dataset from Kaggle to build a sentiment classifier.

✅ Uses traditional ML:
- TF-IDF vectorization
- Logistic Regression classifier

🎯 Accuracy: 89.42%
Note: Dataset not included. Download from [Kaggle link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

Run this notebook on Google Colab to reproduce results.
"""
with open("README.md", "w") as f:
    f.write(readme_text)

# Save requirements.txt
!pip freeze > requirements.txt
