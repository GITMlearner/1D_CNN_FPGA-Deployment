# 1D_CNN_FPGA-Deployment
1D CNN model built with Keras/TensorFlow for text classification, trained on IMDB sentiment data and Agriculture Q&amp;A dataset, with HLS4ML conversion for Zynq 7000 FPGA deployment.

# 1D CNN Text Classification

A complete pipeline for training a 1D Convolutional Neural Network (CNN) 
using Keras and TensorFlow on Google Colab.

## What this repo contains
- Data loading and preprocessing pipeline
- 1D CNN model architecture with Conv1D, MaxPooling, Embedding layers
- Training on IMDB sentiment dataset (84% accuracy)
- Training on Agriculture Q&A dataset (87% accuracy)
- Model saved as .h5 format
- HLS4ML conversion to HLS C++ for FPGA deployment
- Vitis HLS project files for Xilinx Zynq 7000

## Models
- Hosted on Hugging Face: MadhawaDG/agriculture-1d-cnn

## Tech stack
- Python 3.12
- TensorFlow 2.19
- Keras
- hls4ml
- Google Colab
- Xilinx Vitis HLS
- Zynq 7000 FPGA (xc7z020clg484-1)

## Pipeline
Dataset → Tokenize → Pad → Train 1D CNN → Save .h5 → Convert HLS → FPGA
