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




![image](https://github.com/user-attachments/assets/22b3d1ad-8322-4853-a6ca-8e9fb82b7cf1)
![image](https://github.com/user-attachments/assets/d8502bc5-1490-44f6-8503-7b78f0ba2cfa)
![image](https://github.com/user-attachments/assets/a3f0b04c-0438-4bcc-8774-59d094beb21f)
![image](https://github.com/user-attachments/assets/d03bf06a-151c-47a8-9f4e-2ac7337e3d55)

```bash
pip install spacy
pip install keybert
pip install transformers
pip install torch



