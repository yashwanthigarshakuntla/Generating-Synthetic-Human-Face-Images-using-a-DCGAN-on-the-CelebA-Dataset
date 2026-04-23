# DCGAN Face Generation on CelebA

## Overview
This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) to generate synthetic human face images using the CelebA dataset.

## Problem Statement
Generating realistic human face images from random noise is a classic generative modelling task. This project explores how adversarial training enables a generator to learn the data distribution of facial images.

## Objectives
- Train a DCGAN model on face images from CelebA
- Monitor generator and discriminator behaviour during training
- Generate realistic synthetic face samples
- Analyse training instability and output quality

## Dataset
CelebA is a large-scale face dataset containing celebrity face images with rich variation in pose, background, and facial attributes.

## Methodology
- Preprocessed and resized input images
- Built generator and discriminator networks using convolutional layers
- Trained the model using adversarial loss
- Monitored losses and generated sample outputs across epochs

## Tech Stack
Python, PyTorch or TensorFlow, torchvision, NumPy, matplotlib, Jupyter Notebook

## Results
Include:
- sample generated images
- epoch-wise progression
- generator and discriminator loss curves
- short discussion of output quality and limitations

## Repository Structure
- notebooks/dcgan_celeba_training.ipynb
- images/
- outputs/
- requirements.txt

## How to Run
1. Clone the repository
2. Install dependencies
3. Download/configure the CelebA dataset
4. Run the notebook to train the DCGAN

## Key Learnings
This project helped demonstrate adversarial learning dynamics, instability issues in GAN training, and the challenge of balancing generator and discriminator performance.

## Limitations
- GAN training instability
- mode collapse risk
- limited output resolution
- qualitative evaluation focus

## Future Improvements
- Use WGAN-GP for improved stability
- Add FID or IS evaluation
- Train for longer with improved hyperparameter tuning
