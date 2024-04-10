# Deep Paper Predictor

Welcome to the Deep Paper Predictor GitHub repository! This repository contains code for a web application that assists researchers in finding relevant research papers and predicting the subject area of a paper based on its abstract.

## Overview
The Deep Paper Predictor is a web application developed using Streamlit, TensorFlow, PyTorch, and Sentence Transformers. It consists of two main functionalities:
- **Paper Recommendation:** Given the title of a research paper, the application recommends similar papers based on cosine similarity scores calculated using sentence embeddings.
- **Subject Area Prediction:** Given the abstract of a research paper, the application predicts the subject area using a shallow Multi-Layer Perceptron (MLP) model.

## How to Use
To use the Deep Paper Predictor:
1. Clone this repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Need to save all the models form the Research Paper recommendation and subject area prediction using sentence transformer.ipyb file.
4. There will be total 7 files in the models folder so be sure that you have save all the 7 models.
5. Run the Streamlit application by executing `streamlit run app.py` in your terminal.
6. Enter the details of the paper (title and abstract) in the sidebar.
7. Click on the "Recommend" button to get recommendations and predicted subject areas.

## Dependencies
- TensorFlow
- PyTorch
- Sentence Transformers
- Streamlit
- Googlesearch

All dependencies can be installed via pip using the command `pip install -r requirements.txt`.

## File Structure
- **app.py:** Main Streamlit application file containing the user interface and interaction logic.
- **models/:** Directory containing saved models, embeddings, and configurations.
- **utils.py:** Utility functions for recommendation and subject area prediction.

## Contributors

- [Devanshu](https://github.com/Devanshu1013)
