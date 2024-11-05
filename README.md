# Bird Species Classification App 🐦

This is a Streamlit application for classifying bird species using Convolutional Neural Networks (CNNs). The app supports multiple models, including a basic CNN, a VGG16 model without fine-tuning, and a fine-tuned VGG16 model.
![image](https://github.com/user-attachments/assets/1bfcc1b4-5a7f-4c55-90f6-bcb0ad100156)

## Features

- **Image Upload:** Users can upload up to 5 images for classification.
- **Model Selection:** Choose between different models for prediction:
  - Basic CNN
  - VGG16 (No Fine-Tuning)
  - VGG16 Transfer Learning (Fine-Tuned)
- **Feature Extraction:** Upload a single image to visualize feature maps from the VGG16 model.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Streamlit
- TensorFlow
- Matplotlib
- NumPy

You can install the required packages using pip:

```bash
pip install streamlit tensorflow matplotlib numpy
