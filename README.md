# Medical NLP Pipeline for Clinical Text Analysis

A comprehensive NLP pipeline for processing clinical dialogues, extracting medical entities, analyzing patient sentiment, and generating structured medical documentation.

## Features

- **Medical Entity Recognition**: Extract symptoms, diagnoses, treatments, and prognosis
- **Sentiment Analysis**: Classify patient sentiment (Anxious/Neutral/Reassured)
- **Intent Detection**: Identify patient communication intent
- **SOAP Note Generation**: Create structured clinical documentation
- **Hybrid Processing**: Combine transformer models with rule-based patterns


## Models Used
- **Biomedical NER**: d4data/biomedical-ner-all
- **Clinical Sentiment**: emilyalsentzer/Bio_ClinicalBERT
- **Base Language Model**: bvanaken/clinical-assertion-negation-bert

## Installation

```bash
pip install spacy transformers torch
python -m spacy download en_core_web_sm
