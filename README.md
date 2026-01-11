# Toxic & Hateful Comment Detection (BiLSTM)

## 📌 Overview

This project implements an automated system to detect toxic and hateful comments using a **BiLSTM (Bidirectional LSTM)** neural network. It applies robust NLP preprocessing, data augmentation to improve linguistic diversity, and imbalance handling techniques to enhance real-world performance on skewed datasets.

## 🚀 Features

* BiLSTM-based deep learning classifier
* Extensive text preprocessing (cleaning, tokenization, padding)
* Data augmentation for improved generalization
* Class imbalance handling (e.g., class weighting)
* Evaluation using standard NLP classification metrics

## 🛠 Tech Stack

* **Language:** Python
* **Frameworks:** TensorFlow / Keras
* **Domain:** Natural Language Processing (NLP)

## 📂 Project Structure

```
├── data/                 # Dataset (not included due to size limits)
├── notebooks/            # Jupyter notebooks
├── model/                # Trained model files (see note below)
├── utils/                # Preprocessing and helper scripts
├── requirements.txt
└── README.md
```

## ⚠️ Large File Handling

GitHub restricts individual file uploads to **25 MB**. Large files such as trained models or datasets are **not directly included** in this repository.

### Accessing Large Files

* Model / dataset files are hosted externally (e.g., Google Drive / HuggingFace / Kaggle)
* Download links are provided below:

```
[Add your model/dataset link here]
```

> Best practice followed: repository contains **reproducible code**, not heavy binaries.

## 📊 Evaluation

The model is evaluated using standard NLP classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-score

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:

```
pip install -r requirements.txt
```

3. Download the dataset/model from the provided link
4. Run the notebook or training script

## 📈 Future Improvements

* Transformer-based models (BERT, RoBERTa)
* Multi-label classification
* Deployment as a REST API

## 👤 Author

Developed by **Shravani Bhuwan**

---

⭐ If you find this project useful, consider starring the repository.
