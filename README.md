# DocClass
## Document Classifier

This project implements a robust **Document Classifier** to categorize text documents into one of five categories: Scientific, Legal, E-commerce, News, and Blog. The system uses both traditional machine learning (Random Forest) and deep learning (Neural Networks with Universal Sentence Encoder embeddings) to achieve high classification accuracy.

## Dataset
The dataset used for this project consists of 3,000 labeled documents, balanced across five categories. Replace the placeholder data.csv file with your dataset if necessary.

## Project Workflow
The project follows a well-structured workflow to ensure effective document classification. It begins with Data Preprocessing, which involves cleaning the input data, tokenizing it into manageable units, and applying techniques like stopword removal, stemming, and lemmatization to standardize the text. Following this, Feature Extraction is performed using TF-IDF and the Universal Sentence Encoder to convert the preprocessed text into numerical representations suitable for machine learning models. The Classification Models include a Random Forest classifier for traditional machine learning and a custom neural network for deep learning, each tailored to maximize performance. The models demonstrate High Accuracy, with the Random Forest achieving 99.50% accuracy and the neural network consistently delivering around 99.18% accuracy.

- **Data Preprocessing**: Includes cleaning, tokenization, stopword removal, stemming, and lemmatization.
- **Feature Extraction**: Utilizes TF-IDF and Universal Sentence Encoder for numerical representations.
- **Classification Models**: Implements Random Forest for traditional machine learning and a custom neural network for deep learning.
- **High Accuracy**: Achieves over 99.50% accuracy with Random Forest and above 99.18% accuracy with the deep learning model.

---

## Getting Started

Follow these steps to clone the repository, install the required dependencies, and run the project.

### Clone the Repository
First, clone this repository to your local machine:
```bash
git clone https://github.com/darkbit404/document-classifier.git
```
### Navigate to the Project Directory
Use cd command in windows terminal or windows powershell to navigate to the project directory.
```bash
cd document classifier
```
### Install Dependencies
Ensure you have Python installed, then install the required dependencies listed in the requirements.txt file:
```bash
pip install -r requirements.txt
```
### Run the project
Open the cloned repository in your preferred IDE (e.g., Jupyter Notebook, VSCode, or PyCharm). Locate and open the .ipynb file, and then execute the code cells to run the project.

---

## Outputs
Trained Models: Saved as tfidf rf model.pkl and word embeddings dl model.h5.

Classification Reports: Printed for both the Random Forest and Neural Network approaches.
