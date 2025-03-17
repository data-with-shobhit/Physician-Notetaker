# Healthcare NLP Pipeline

This repository provides an NLP pipeline for analyzing medical conversations and extracting valuable insights, including Named Entity Recognition (NER), Text Summarization, Keyword Extraction, and Sentiment & Intent Analysis.

## Overview

This pipeline performs the following tasks on the provided medical conversation text:

1. **Named Entity Recognition (NER)** using SpaCy with EntityRuler.
2. **Text Summarization** using the `facebook/bart-large-cnn` model.
3. **Keyword Extraction** using the `KeyBERT` library to identify important medical phrases.
4. **Sentiment & Intent Analysis** using `DistilBERT`.

### Features
- Identify **important medical entities** such as injuries, symptoms, and treatments.
- **Summarize** physician-patient conversations into concise and relevant information.
- **Extract medical keywords** for further analysis.
- **Classify the sentiment** of the conversation (e.g., anxious, neutral, reassured).
- **Detect the patient's intent**, such as seeking reassurance or reporting symptoms.

## Prerequisites

Ensure you have the following dependencies installed:

### Install Dependencies

```bash
pip install spacy
pip install keybert
pip install transformers
pip install torch
