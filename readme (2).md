# NULLCLASS Internship: Final Submission Report

# Intern Name: Agneya S Nambiar  
# Internship Duration: 01-06-2025 to 01-07-2025

## Overview
This repository contains the complete implementation of the three internship tasks assigned by NULLCLASS. The tasks include working with language models, public image datasets, and fine-tuning a text-to-image model on a custom dataset.

Each task has been developed, tested, and documented as per the given guidelines, and appropriate screenshots, logs, and model performance results have been provided.
## Structure

├── Task1-BERT-Tokenizer/
│ ├── Task1_Tokenization_Encoding_Agneya.ipynb
│ ├── requirements.txt
│ └── README.md

├── Task2-Dataset-Exploration/
│ ├── dataset_analysis-agneya.ipynb
│ ├── images_and_statistics/
│ ├── flower_image_statistics.csv
│ └── README.md

├── Task3-Text-to-Image-Finetune/
│ ├── text_to_image-agneya.ipynb
│ ├── large_code_not_starting.ipynb
│ ├── dataset/
│ ├── output_samples/
│ ├── requirements.txt
│ └── README.md

├── Internship_Report_Final.pdf
└── README.md

## Task Summary
### Task 1: Tokenization and Encoding using Pre-trained Language Model
- Model Used: BERT from Huggingface Transformers
- Description: Tokenized and encoded input texts using BERT tokenizer and encoder.
- Libraries: `transformers`, `torch`
- Output: Tensor representations of input text.
  
### Task 2: Public Dataset Analysis - Oxford Flowers 102
- Dataset: `Oxford 102 Flowers` from TensorFlow Datasets
- Description: Analyzed dataset structure, image resolution, and class distribution. Visualized sample images.
- Libraries: `tensorflow_datasets`, `pandas`, `matplotlib`
- Output: CSV stats, boxplots, grid of sample flower images

### Task 3: Fine-tuning Text-to-Image Model with Custom Dataset
- Model Used: Stable Diffusion
- Custom Dataset: Images + Prompts (Domain-Specific)
- Training Note: Initial full training caused system lag. Switched to lightweight training with reduced resolution and batch size.
- Output: Finely tuned model, sample generated images
- Libraries: `diffusers`, `transformers`, `torch`, `datasets`, `gradio`

## Google Drive Links (For Large Files)

📁 Google drive: https://drive.google.com/drive/folders/141KH_7mM3f59ROKyaE6vvIYIwyMQUatE?usp=sharing

## Internship Report

You can read the detailed internship report in the file below:

[internship_report_final.pdf]

## Requirements

Each task contains a `requirements.txt` file. Use the following command to install dependencies:

```bash
pip install -r requirements.txt


All tasks have been structured according to NULLCLASS internship requirements.

Each notebook has been tested for reproducibility and correctness.

Model accuracy has been prioritized and reached acceptable standards wherever applicable.

Efforts have been made to optimize training due to hardware limitations.
