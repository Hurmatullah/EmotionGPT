# Emotion Classification Using a Fine-Tuned GPT-2 Model

This repository contains a fine-tuned GPT-2 model for emotion classification. The model has been trained on a specific dataset to classify text into distinct emotional categories.

---

## Table of Contents
1. [About the Project](#about-the-project)
2. [Dataset](#dataset)
3. [Model Fine-Tuning](#model-fine-tuning)
4. [Usage](#usage)
5. [Installation](#installation)
6. [Contributing](#contributing)
7. [License](#license)
8. [Acknowledgments](#acknowledgments)

---

## About the Project

Emotion classification is an important task in natural language processing (NLP) with applications in sentiment analysis, social media monitoring, and human-computer interaction. This project utilizes a pre-trained GPT-2 model, fine-tuned to predict emotions from text data accurately.

---

## Dataset

- **Source**: https://huggingface.co/datasets/SetFit/go_emotions.
- **Description**: The dataset contains labeled text data for emotions such as happiness, sadness, anger, and others.

---

## Model Fine-Tuning

The base GPT-2 model was fine-tuned using transfer learning techniques. Here are the details:

- **Pre-trained Model**: GPT-2 (OpenAI's pre-trained transformer model).
- **Result**:
  - Used F1 score, and the final result was 0.899912 with 0.112300 training loss.

---

### Requirements
- Python >= 3.8
