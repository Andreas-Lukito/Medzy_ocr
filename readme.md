# Medzy
## Overview
This project aims to develop a machine learning model capable of interpreting doctors’ handwriting on prescriptions. By accurately detecting and translating challenging handwriting, the model will empower patients to read their prescriptions independently, making it easier for them to purchase their medications without confusion if they run out of medicine.

## About the model
This model is a fine tuned Hugging Face's [TrOCR model](https://huggingface.co/docs/transformers/en/model_doc/btrocr) for converting the handwriting into text, then passed into a [BART model](https://huggingface.co/docs/transformers/en/model_doc/bart) with fuzzy matching to correct the OCR output.

![Model Schema](https://github.com/Andreas-Lukito/Medzy_ocr/blob/rayhan/TrOCR/images/image.png?raw=true)