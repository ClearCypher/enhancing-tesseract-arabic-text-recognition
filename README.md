# Enhancing Tesseract Arabic Text Recognition

This repository contains the fine-tuned Long Short-Term Memory (LSTM) model for Arabic text recognition in Tesseract OCR.

## About the Project
This project is part of a research study titled "Enhancing Arabic Text Recognition: Fine-tuning of the LSTM Model in Tesseract OCR". The LSTM model in Tesseract OCR was fine-tuned using a diverse training dataset of 1038 unique Arabic fonts. The performance of this fine-tuned model was evaluated across various Arabic text types and compared with the original Tesseract OCR model. 

## Trained Model
The `arabic.traineddata` file in this repository is the result of our fine-tuning process. It is designed to significantly enhance Arabic text recognition in Tesseract OCR. 

## Usage
To use this fine-tuned model, download the `arabic.traineddata` file and place it in your Tesseract 'tessdata' directory, replacing the existing Arabic trained data file. Then, simply run Tesseract as you normally would.

## Results
The fine-tuned model demonstrated significant performance enhancements in recognizing most Arabic text types, specifically Arabic-indic digits, European digits, normal Arabic text, and Arabic text without diacritics. For more details about the research and results, refer to the research paper (TODO).
