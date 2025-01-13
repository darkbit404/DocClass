# DocClass
# Document Classifier

This project implements a robust **Document Classifier** to categorize text documents into one of five categories: Scientific, Legal, E-commerce, News, and Blog. The system uses both traditional machine learning (Random Forest) and deep learning (Neural Networks with Universal Sentence Encoder embeddings) to achieve high classification accuracy.

## Features
- **Data Preprocessing**: Includes cleaning, tokenization, stopword removal, stemming, and lemmatization.
- **Feature Extraction**: Utilizes TF-IDF and Universal Sentence Encoder for numerical representations.
- **Classification Models**: Implements Random Forest for traditional machine learning and a custom neural network for deep learning.
- **High Accuracy**: Achieves over 99% accuracy with Random Forest and above 94% accuracy with the deep learning model.

---

## Getting Started

Follow these steps to clone the repository, install the required dependencies, and run the project.

### Clone the Repository
First, clone this repository to your local machine:
```bash
git clone https://github.com/your-username/document-classifier.git
cd document-classifier
