# Hugging Face NLP Workflows 🚀

Welcome to this repository! Explore how to use Hugging Face's powerful tools and models to build state-of-the-art Natural Language Processing (NLP) applications. This repository showcases a variety of workflows, from sentiment analysis to dynamic category assignment, using pre-trained models and pipelines.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Setup](#setup)
4. [Usage](#usage)
5. [Contributions](#contributions)
6. [License](#license)

---

## Introduction

Hugging Face provides user-friendly tools and pre-trained models to accelerate NLP tasks. This repository demonstrates various applications like sentiment analysis, question answering, dataset manipulation, and text classification using Hugging Face libraries.

---

## Features

- **Sentiment Analysis**: Classify text as `POSITIVE` or `NEGATIVE` using a DistilBERT model fine-tuned on the SST-2 dataset.
- **Dataset Manipulation**: Filter, slice, and analyze datasets for ML tasks.
- **Text Classification**: Detect grammatical errors or categorize text dynamically into predefined labels.
- **Question Answering**: Extract relevant answers from input text using a Q&A pipeline.
- **Dynamic Category Assignment**: Assign text into predefined categories without additional model training.
- **PDF Text Extraction**: Seamlessly extract text from PDF files.
- **AutoClasses Integration**: Combine `AutoModels` and `AutoTokenizers` with Hugging Face pipelines for streamlined workflows.

---

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/huggingface-nlp-workflows.git
   cd huggingface-nlp-workflows
2. Install dependencies:
   pip install -r requirements.txt  

3. Verify the setup:
  python test_setup.py  

---

## Usage
Run individual scripts for specific workflows. 
Example commands:

1. Sentiment Analysis:

python sentiment_analysis.py --text "Hugging Face is amazing!" 

2. Dataset Manipulation:

python manipulate_dataset.py  

3. Question Answering:

python qa_pipeline.py --question "What is Hugging Face?" --context "Hugging Face is a machine l

---

## Contributions

Contributions are welcome! 

Follow these steps:

Fork this repository.

Create a new branch for your feature or bug fix.

Commit your changes and submit a pull request.

---

## License
This project is licensed under the MIT License.

---

## Resources
Hugging Face Documentation

Transformers GitHub Repository

Happy Coding! 💻✨
  
