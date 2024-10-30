# RadiologyAI

A deep learning-based image classification model to classify lung X-ray images into three categories: **Pneumonia**, **COVID-19**, and **Normal Lungs**. This project utilizes **VGG19** with transfer learning, leveraging ImageNet-pretrained weights for enhanced accuracy and faster convergence. Other models, including **VGG16**, **ResNet**, and **Inception ResNet**, were also evaluated for performance comparison.

## Model Overview
- **Model Architectures Tried**: VGG19 (primary), VGG16, ResNet, Inception ResNet
- **Transfer Learning**: Using pretrained weights from ImageNet
- **Goal**: Accurate classification of lung conditions from X-ray images to aid in diagnostic processes.

## Results
The VGG19 model achieved the highest accuracy in classifying the three conditions, but results from VGG16, ResNet, and Inception ResNet are also available for comparison.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RadiologyAI.git

