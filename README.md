# LipNet: Video-to-Text Conversion

This repository contains the implementation of **LipNet**, a deep learning model for **lipreading** and converting silent video sequences of speech into text.

---

## **Project Overview**

LipNet is a sequence-to-sequence deep learning model that takes video frames of a speaker’s mouth movements as input and outputs the corresponding text transcription. The model leverages **spatiotemporal convolutional layers**, **recurrent layers**, and **CTC loss** for end-to-end training.

Key features of this repository:
- Preprocessing pipelines for lip video data
- LipNet model implementation in Python/TensorFlow
- Notebook examples for training and testing
- Results folder with sample outputs and animations
- Trained model checkpoint (`models/checkpoint.weights.h5`)

---

## **Dataset Structure**

The dataset used for training is **not included** due to size constraints.  
The dataset contains video recordings of speakers along with alignment files.

