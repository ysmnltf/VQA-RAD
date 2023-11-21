# VQA-RAD Solutions Repository

## Introduction
This repository contains my solutions for the Visual Question Answering on Radiology (VQA-RAD) dataset. The implemented models are designed for both closed-ended and open-ended questions, using a combination of classification and sequence-to-sequence approaches.

## Features
### Models
1. **Closed-ended Question Model:**
   - Implemented using Keras.
   - Text features extracted using DistilBERT.
   - Image features extracted using ResNet50.
   - Fusion of text and image features using the MFB (Multi-modal Feature Block) architecture.

2. **Open-ended Question Model:**
   - Developed with Keras.
   - Utilizes a sequence-to-sequence model.
   - Text features extracted using DistilBERT.
   - Image features extracted using ResNet50.
   - Fusion of text and image features using the MFB (Multi-modal Feature Block) architecture.

### Notebooks
- `VQA_RAD_Closed_Ended_Model.ipynb`: Jupyter Notebook for the classification model trained on closed-ended questions.
- `VQA_RAD_Open_Ended_Model.ipynb`: Jupyter Notebook for the sequence-to-sequence model trained on open-ended questions.
