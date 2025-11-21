## Project Structure  
- Fake_News_Detection.ipynb  
- dataset/  
   - news.csv  
- README.md  
- FakeNewsDataset_Sample.pdf

- 
# Fake-News-Detection-Using-Machin-learning-Techniques
Fake News Detection using Machine Learning (TF-IDF + Passive Aggressive Classifier)
# Fake News Detection using Machine Learning

This project builds a machine learning model to classify news articles as **Real** or **Fake** using Natural Language Processing (NLP) and supervised learning.

## Tech Stack

- Python
- pandas, numpy
- scikit-learn
- TF-IDF (TfidfVectorizer)
- PassiveAggressiveClassifier

## Dataset

A labelled fake news dataset containing news text and corresponding labels (Real/Fake).

## Approach

1. Loaded and explored the dataset using `pandas`.
2. Split data into training and test sets (80/20 split).
3. Converted text into numerical features using **TF-IDF**.
4. Trained a **Passive Aggressive Classifier** on the training data.
5. Evaluated the model using **accuracy, classification report, and confusion matrix**.

## Results

- Model achieved around **XX% accuracy** on the test set.

## How to Run

1. Open the notebook `Fake_News_Detection.ipynb` in Google Colab or Jupyter.
2. Upload the dataset CSV file.
3. Run all cells to train and evaluate the model.

## Author

**Jadi Swar...**  
Final year B.Tech CSE student interested in Python, Web Development, and Machine Learning.

### Notebook Preview  
You can view the full notebook on Google Colab: [Open in Colab](https://colab.research.google.com/…)
 
