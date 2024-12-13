# Handwriting Recognition Model For Scanned Medical Documents
**Handwriting Recognition Model**
**Overview**:

This project aims to develop a robust handwriting recognition system for converting handwritten medical documents into machine-readable text. The model is built using Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN) with Long Short-Term Memory (LSTM) units, trained on the IAM dataset. The system utilizes Optical Character Recognition (OCR) techniques with Connectionist Temporal Classification (CTC) loss for efficient sequence learning without explicit alignment between input and output sequences.

**Why Handwriting Recognition?**

Handwritten text recognition is essential for automating the processing of handwritten medical documents, which often contain crucial information. By converting handwritten data into digital format, it enhances the efficiency of healthcare documentation and retrieval systems.

**How It Works:**

CNNs are used to extract hierarchical features from handwritten text images, capturing patterns like edges and curves.
RNN-LSTM layers capture the sequential nature of handwriting, learning dependencies over time.
The model processes 4D tensors (batch size, image height, width, channels) for input images and outputs a sequence of characters.
CTC Loss is employed to train the network without the need for labeled sequence alignment.

**Technologies Used:**

TensorFlow & Keras for model building, training, and evaluation.
OCR techniques to read and interpret handwritten characters.
Evaluation metrics include Character Error Rate (CER) and Word Error Rate (WER), which are used to assess the accuracy of the model’s predictions.
This project demonstrates the power of deep learning for real-world applications, improving the efficiency and accuracy of text recognition in complex environments.
