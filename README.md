
## Overview
This project implements a GAN-based anime face generator that trains on the crypko dataset, comprising over 71,000 anime face images. By leveraging both DCGAN and WGAN-GP architectures, the model is designed to generate high-quality anime faces with robust performance, as measured by the Anime Face Detection (AFD) rate.

## Features
- **Robust GAN Architectures:** Implements both DCGAN and WGAN-GP models to balance training stability and image quality.
- **Extensive Dataset:** Utilizes the crypko dataset with 71,314 JPEG images, enabling the model to learn a wide variety of anime facial features.
- **High-Quality Generation:** Generates 1000 uniquely named images (e.g., 1.jpg, 2.jpg, ...) for further evaluation and creative use.
- **Evaluation Metrics:** Assessed using the AFD rate to ensure that the generated images meet high-quality standards.
- **Data Augmentation:** Employs augmentation techniques such as shifting and flipping to improve model robustness without altering the original training images.


