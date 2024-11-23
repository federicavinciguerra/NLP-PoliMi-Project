# Medical Question Answering with Medical Meadow Dataset

## Project Overview
This project focuses on applying Natural Language Processing techniques to analyze the Medical Meadow Medical Flashcards dataset and build a model capable of answering medical questions.

## Dataset
The Medical Meadow Medical Flashcards dataset contains medical curriculum flashcards used to train GPT-3.5 for generating medical knowledge question-answer pairs.

- **Dataset Source:** Medical Meadow Medical Flashcards on Hugging Face
- **Relevant Paper:** Exploration of Medical Meadow Medical Flashcards

## Tasks
### Preliminary Analysis:
- Descriptive statistics of the dataset.
- Visualization of document clusters.
- Indexing and keyword search capabilities.
- Word2Vec embeddings to investigate the dataset semantics.

### Model Training:
- Training a linear classifier and comparing its performance with a deep learning model, specifically BERT, to answer medical questions.

### Extensions:
- Evaluation of model performance on related datasets.
- Potential use of text-to-speech and speech-to-text models to enhance interaction.

## Project Structure
- `notebooks/` - Jupyter notebooks containing all the analyses and model training processes.
- `data/` - Scripts and utilities for data handling and preprocessing.
- `models/` - Trained models and their respective configurations.
- `docs/` - Additional documentation and resources related to the project.
  
## Authors
- Federica Vinciguerra
- Rishabh Tiwari
- Felipe Bagni
- Dan Lionis
- Erfan Amidi

## Installation and Usage
Instructions for setting up the project environment and running the notebooks:
```bash
git clone https://github.com/federicavinciguerra/NLP-Polimi-Project.git
cd NLP-Polimi-Project
pip install -r requirements.txt


