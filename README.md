# Quran_Reciter_Classification

This project aims to classify Quran recitations based on the reciter using audio classification techniques.

## Dataset

The dataset used for this project is the "Quran Recitations for Audio Classification" dataset available on Kaggle. It contains audio recordings of Quran recitations by various reciters.

## Methodology

1. **Data Preprocessing:**
    - The audio recordings are converted into Mel spectrograms, which are visual representations of the audio frequencies.
    - The spectrograms are resized to a uniform size.
    - The reciter labels are encoded using Label Encoding.

2. **Model Building:**
    - A Convolutional Neural Network (CNN) is used for audio classification.

3. **Training:**
    - The model is trained on the training set using the Adam optimizer and Cross-Entropy Loss.
    - The training progress is monitored using validation data.

4. **Evaluation:**
    - The trained model is evaluated on the test set to measure its performance.
    - Accuracy is used as the evaluation metric.

## Results

The model achieved an accuracy of 79.56% on the test set.
