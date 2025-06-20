# Real-Time Text-to-Image Gen AI | NULLCLASS Internship

## Description

This repository contains the submission for the NULLCLASS internship (June 2025) covering:
1.  Create a program that uses a pre-trained language model (such as BERT or GPT) to tokenize and encode incoming text. While encoding converts these tokens into numerical representations appropriate for model input, tokenization divides the text into smaller pieces (tokens).
2. To comprehend the structure of a public dataset, load and examine it (e.g., COCO, Oxford-102 Flowers). Analyze dataset statistics such as the number of classes, description length, and image resolution, and explore and display text descriptions combined with photos.
3. Use a custom dataset to refine a pre-trained text-to-image model (such as DALL-E or Stable Diffusion). This entails modifying the model to produce domain-specific visuals, such as artwork or medical imagery.


## Folder Structure

- `task1_tokenization_encoding/` → Tokenization and encoding using transformers
- `task2_dataset_analysis/` → Dataset stats & image-description exploration
- `task3_text_to_image/` → Fine-tuned model, training notebook, GUI, and result

## 📦 Download Trained Model

Due to size restrictions, model files are hosted externally:
[Download from Google Drive](https://drive.google.com/drive/folders/141KH_7mM3f59ROKyaE6vvIYIwyMQUatE?usp=sharing)

## Internship Report
- See `internship_Report_final.pdf` in root folder

## Requirements
```bash
pip install -r task3_text_to_image/requirements.txt
