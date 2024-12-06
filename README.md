# README: MonetGAN Project

Welcome to the MonetGAN project repository! This project showcases the application of CycleGAN for unpaired image-to-image translation, creating stunning Monet-style images from everyday photographs.

---

## Overview
This project demonstrates the use of CycleGAN to generate high-quality Monet-style images. By training a GAN on photographs and Monet paintings, the model learns to transform photographs into Monet’s unique artistic style while preserving the original content.

Key accomplishments include:
- Designing and implementing a CycleGAN architecture.
- Generating visually convincing Monet-style images.
- Leveraging adversarial and cycle-consistency loss for robust training.

---

## Setup
### Prerequisites
1. Python 3.8+
2. Required libraries:
   - PyTorch
   - NumPy
   - Matplotlib
   - scikit-learn

### Environment
The project supports training on GPUs for faster performance.

---

## Data Preparation
### Dataset
- Monet paintings and photographs were used as the primary datasets.

### Preprocessing
1. Resize all images to 256x256.
2. Normalize pixel values to [-1, 1] for GAN training.

---

## Model Architecture
### CycleGAN
CycleGAN is used for unpaired image-to-image translation. Key components:

1. **Generator**:
   - Converts input images to Monet-style outputs.

2. **Discriminator**:
   - Differentiates real Monet paintings from generated ones.

3. **Cycle Consistency Loss**:
   - Ensures that the generated Monet-style image can be translated back to the original image.

The model is implemented in PyTorch, leveraging custom residual blocks and convolutional layers.

---

## Evaluation
### Visual Results
The generated images are evaluated visually to assess style and content preservation.

### MiFID
The model’s performance is quantified using MiFID, which measures the distance between the distributions of real and generated images.

---

## Achievements
- Successfully trained a CycleGAN model to generate Monet-style images from photographs.
- Achieved compelling results with consistent style transfer across diverse input images.
- Implemented efficient data loading and preprocessing pipelines.

Generated examples demonstrate:
- High-quality artistic rendering.
- Retention of original photo content.

---

## Resources
- [CycleGAN Paper](https://arxiv.org/abs/1703.10593)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
- [FID Metric](https://arxiv.org/abs/1706.08500)

---

## Conclusion
This project successfully demonstrated the application of CycleGAN for unpaired image-to-image translation by transforming everyday photographs into Monet-style paintings. Through careful implementation of the CycleGAN architecture and loss functions, the model was able to produce high-quality, visually compelling images while preserving the content of the original photos. The use of metrics such as MiFID further validated the quality and diversity of the generated images. This project showcases the power of generative models in creating art, bridging the gap between technology and creativity.

