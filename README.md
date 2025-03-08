# Healthcare Diagnostic Assistant

This project demonstrates a Healthcare Diagnostic Assistant using Natural Language Processing (NLP) techniques. It leverages TF-IDF with Logistic Regression and a fine-tuned BERT model to predict potential diagnoses based on patient symptoms, age, and severity.

## Features

- **Data Loading and Preprocessing:** Loads a dataset, cleans and preprocesses text data, and encodes labels.
- **TF-IDF with Logistic Regression:** Implements a baseline model using TF-IDF for feature extraction and Logistic Regression for classification.
- **Fine-tuned BERT:** Utilizes a pre-trained BERT model and fine-tunes it for the specific task of healthcare diagnosis.
- **Interactive Prediction:** Provides an interface for users to input patient information and receive predicted diagnoses.
- **Ethical Considerations:** Includes a disclaimer emphasizing that the system's suggestions should not replace professional medical advice.

## Usage

1. **Upload your dataset:** Upload a CSV file containing patient data with columns for Symptoms, Diagnosis, Age, and Severity.
2. **Install dependencies:** Run `pip install -r requirements.txt` to install the necessary libraries.
3. **Run the notebook:** Execute the cells in the Google Colab notebook to train and evaluate the models.
4. **Interactive Prediction:** Use the provided interface to input patient information and get predictions.

## Disclaimer

This Healthcare Diagnostic Assistant provides preliminary suggestions based on text patterns and should not replace professional medical diagnosis. Always consult with a licensed healthcare professional for accurate diagnosis and treatment. The system's suggestions are non-binding and intended for informational purposes only.
