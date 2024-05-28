# Fake News Detection

This repository contains scripts, models, and data for building and evaluating a fake news detection system using machine learning techniques. The files included demonstrate various methods for processing text data, training models, and visualizing results.

## Files and Descriptions

1. **recognition.py**
   - **Description:** Script for recognizing fake news using a pre-trained model.
   - **Usage:** Loads a trained model and applies it to input data to classify news as fake or real.

2. **fake_news.h5**
   - **Description:** HDF5 file containing the trained model for fake news detection.
   - **Usage:** Used by the `recognition.py` and `fake_news_model.py` scripts to load the pre-trained model for predictions and evaluations.

3. **fake_news_model.py**
   - **Description:** Script for training the fake news detection model.
   - **Sections:**
     - Data Loading and Preprocessing
     - Model Architecture Definition
     - Model Training
     - Evaluation and Metrics Calculation

4. **output.png**
   - **Description:** Image showing the training loss and accuracy of the model.
   - **Usage:** Visual representation of the model's performance over epochs.

