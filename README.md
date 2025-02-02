# Sentiment-Based TV Series/Movie Recommendation System

## Project Overview
This project leverages sentiment analysis techniques to recommend TV series and movies based on user reviews. By detecting emotions such as joy, sadness, anger, fear, love, and surprise, the system aims to offer personalized suggestions that match the user's current mood.

---

## Features
- **Comprehensive Emotion Detection:** Classifies text into six key emotional categories — joy, sadness, anger, fear, love, and surprise.
- **Data-Driven Insights:** Trains on a robust dataset with 16,000 rows for training and 2,000 rows for testing.
- **Text Preprocessing:** Involves tokenization, lemmatization, and removal of stop words to clean user data.
- **Advanced ML Techniques:** Utilizes TF-IDF and Count Vectorizer for feature extraction and SVM for classification.
- **Performance Metrics:** Evaluates models using accuracy scores, classification reports, and confusion matrices.

---

## Installation

### Requirements
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - nltk

### Setup Instructions
1. Clone this repository to your local machine:
    ```bash
    git clone <repository_url>
    ```

2. Navigate to the project directory:
    ```bash
    cd <project_directory>
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Load the `train.csv` and `test.csv` files in the notebook.

5. Run the Jupyter notebook to preprocess data, train models, and make predictions.

---

## Usage
1. **Data Preprocessing:**
    - Clean and transform text data by running the preprocessing code.

2. **Model Training:**
    - Execute the training block to build the emotion classification model.

3. **Recommendation Generation:**
    - Based on the dominant detected emotion, the system suggests TV series and movies tailored to the user’s mood.

---

## Project Workflow
1. **Data Loading:** Import training and testing datasets.
2. **Preprocessing:** Apply tokenization, lemmatization, and feature extraction.
3. **Model Selection:** Train an SVM model for emotion classification.
4. **Evaluation:** Use confusion matrices and classification reports to measure performance.

---

## Evaluation Metrics
- **Accuracy Score:** Evaluate model accuracy.
- **Classification Report:** Detailed precision, recall, and F1-score.
- **Confusion Matrix:** Visual representation of classification results.

---

## Example Use Case
- Input: "This show made me so happy and excited!"
- Output: The detected emotion is joy, and a list of uplifting TV series is recommended.

---

## Contribution
Contributions are welcome! Feel free to fork this repository and submit pull requests for enhancements or bug fixes.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contact
For queries or feedback, please create an issue in the repository.

