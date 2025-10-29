# Week 1, Task 1: Build a Simple Text Classifier with Deep Learning

## 🎯 Objective
Implement a basic text classification model using a deep learning framework (TensorFlow or PyTorch) to categorize text data.

## 📋 Requirements
1.  **Dataset Selection:** Choose a publicly available, simple text classification dataset (e.g., a subset of IMDB movie reviews for sentiment analysis, or a small news topic classification dataset). Describe your dataset choice and its characteristics.
2.  **Data Preprocessing:** Implement robust text preprocessing steps, including tokenization, vocabulary creation, and sequence padding/truncation to a fixed length.
3.  **Model Development:**
    *   Design and implement a shallow deep learning model (e.g., a simple Convolutional Neural Network (CNN) or a Recurrent Neural Network (RNN) like LSTM/GRU) using either **TensorFlow** or **PyTorch**.
    *   The model should be capable of classifying the processed text into predefined categories.
    *   Clearly define and document your model's architecture.
4.  **Model Training & Evaluation:**
    *   Train your model on the selected dataset, ensuring proper splitting into training and validation sets.
    *   Evaluate the model's performance using appropriate metrics such as accuracy, precision, recall, and F1-score on a held-out test set.
    *   Document your training process, hyperparameters, and evaluation results.
5.  **Model Persistence & Inference:**
    *   Save your trained model in a standard format (e.g., Keras H5, PyTorch `.pt`).
    *   Provide a separate script or function that can load the saved model and perform inference on a new, unseen text input string, outputting the predicted class and confidence.
6.  **Testing:** Write unit tests for your data preprocessing functions and your model inference logic to ensure correctness and robustness.
7.  **Documentation:** Provide a `README.md` file within your task directory detailing:
    *   How to set up the environment and install dependencies.
    *   How to run your training script.
    *   How to run your inference script.
    *   A brief explanation of your model architecture and design choices.
    *   Summary of evaluation results.

## ✨ Deliverables
*   Python source code (`.py` files) for data loading, preprocessing, model definition, training, and inference.
*   Trained model file.
*   Unit tests.
*   A `README.md` file in your task directory.