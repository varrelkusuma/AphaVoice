# AphaVoice-TTS Model
This repository contains the official implementation and research code for [AphaVoice: Text-to-Speech Model for Aphasia Patient Simulation]. The project builds a text-to-speech model to simulate aphasia with Matcha-TTS (VCTK checkpoint) as the model foundation.

## 📌 Overview  
AphaVoice is a specialized Text-to-Speech (TTS) model designed to simulate non-fluent aphasic speech for medical student training and clinical simulation. AphaVoice fine-tunes the non-autoregressive architecture of Matcha-TTS to accurately map the distinct temporal and phonetic dysfluencies characteristic of post-stroke aphasia.

## 📂 Repository Structure  
```text
├── data/                       
│   ├── aphasia/                # The metadata, training, and test files (in .csv)
├── jupyter/
│   ├── dataset_preprocessing/  # Code for script and audio pre-processing
│   └── dataset_analysis/       # Code for analyzing dataset
├── matcha_tts/                 # Cloned Matcha-TTS directory to run the model
├── runs/                       # Fine-tuning directory
│   ├── logs/                   # Fine-tuning logs
├── vector/                     # Extracted vector for latent shift
└── requirements.txt            # Python dependencies
```

## 🚀 Getting Started  
1. Installation
Clone the repository and install the required dependencies:
```
git clone https://github.com/varrelkusuma/AphaVoice
cd AphaVoice
pip install -r requirements.txt
```
2. Download the Model
Download the official model release on HuggingFace (https://huggingface.co/varrelkusuma/AphaVoice)

3. Run the Model
Please refer to the Jupyter Notebook on how to use the model.
