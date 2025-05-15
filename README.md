# 🛡️ Hate Speech Detection using Machine Learning

This repository contains a machine learning project focused on detecting hate speech and offensive language in tweets using Natural Language Processing (NLP).

## 🧠 Objective

To build a model that can classify tweets into:
- Hate Speech
- Offensive Language
- Neither

## 📊 Dataset

Used a labeled Twitter dataset for hate speech detection. The dataset includes tweets annotated as:
- 0 → Hate Speech
- 1 → Offensive Language
- 2 → Neither

## 🛠️ Tools & Technologies

- Python
- NLTK
- Scikit-learn
- Pandas, NumPy, Matplotlib
- Jupyter Notebook

## 🔎 Workflow

1. **Data Preprocessing**
   - Tokenization
   - Stopword Removal
   - Lemmatization
   - Lowercasing

2. **Exploratory Data Analysis**
   - Class distribution
   - Word frequency analysis

3. **Model Building**
   - Feature Extraction: TF-IDF
   - Classification using: Logistic Regression / Naive Bayes
   - Model Evaluation: Accuracy, Confusion Matrix

4. **Performance**
   - **Accuracy**: `88.43%` (as per evaluation screenshot)
   - Trained using train/test split

## 📷 Screenshots

### 🔍 Example of Predictions

![Image](https://github.com/user-attachments/assets/21dce061-e8d7-4f80-9f9b-5eb37d61f093)
![Image](https://github.com/user-attachments/assets/8047f87b-38c5-4303-8a1a-afc2b6d6ba79)

### 📈 Accuracy Score
Model achieved an accuracy of **0.8843**

![Image](https://github.com/user-attachments/assets/0414182b-f4f9-4eb2-a3a3-ebb93758736b)

## 🚀 Getting Started

Clone this repository and run the Jupyter Notebook:

```bash
git clone https://github.com/your-username/hate-speech-detection.git
cd hate-speech-detection
jupyter notebook HateSpeechNLTK.ipynb
