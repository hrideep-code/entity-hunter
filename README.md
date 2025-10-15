# Named Entity Recognition (NER) — spaCy

This repository contains a Jupyter Notebook that trains, tests, and evaluates a custom Named Entity Recognition (NER) model using [spaCy](https://spacy.io/).

## Repository contents
- **training&accuracyTestingCode.ipynb** — Single notebook that:
  - Loads training data from `output_complete.json`
  - Builds a blank English pipeline and adds the NER component
  - Trains the model (multiple iterations)
  - Saves the trained model to `ner_small_model/`
  - Runs a quick test on sample text
  - Computes Precision, Recall, and F1 score over the training set

## Requirements
Install dependencies with:
```bash
pip install -r requirements.txt
