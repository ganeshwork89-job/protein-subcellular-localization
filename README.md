# Protein Subcellular Localization Prediction

## Project Overview
This project focuses on predicting the subcellular localization of proteins using deep learning and ProtBERT embeddings.

The system uses protein sequences as input and predicts their possible cellular localization.

## Technologies Used
- Python
- ProtBERT
- Hugging Face Transformers
- TensorFlow / Keras
- PyTorch
- Streamlit
- NumPy

## Methodology
1. Protein sequences are provided in FASTA format or pasted into the application.
2. ProtBERT generates 1024-dimensional protein embeddings.
3. A trained Multi-Layer Perceptron (MLP) processes the embeddings.
4. The model predicts one of 10 subcellular localization classes.
5. Results are displayed through a Streamlit interface.

## Model Performance

- Test Accuracy: 69.97%
- Weighted F1-score: 0.70
- Macro F1-score: 0.60
- Test Samples: 7,164

## Project Screenshots
See the `screenshots` folder for implementation and model evaluation screenshots.

## Project Documentation
The complete project report is available in this repository:

`Protein_Subcellular_Localization_Report.pdf`

## Note
This repository contains project documentation and selected implementation screenshots. The original executable source code and trained model are not included.
