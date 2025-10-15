# Named Entity Recognition (NER) — spaCy

This repository contains a Jupyter Notebook that trains, tests, and evaluates a custom Named Entity Recognition (NER) model using [spaCy](https://spacy.io/) which can detect cybersecurity entities.
Predominantly used to automatically identify and extract important entities—like organizations, threat actors, locations, or tools—from cybersecurity reports, articles, or datasets. This model helps streamline threat intelligence analysis, improve data categorization, and assist in building smarter security systems that can process large volumes of text quickly and accurately.

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

