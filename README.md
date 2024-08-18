# <h1 align="center">Pet Image Segmentation with U-Net</h1>

This project implements a U-Net architecture for semantic segmentation of pet images using TensorFlow and the Oxford-IIIT Pet Dataset.

<p align="center">
  <img src="https://github.com/user-attachments/assets/3f2498ce-465a-4b73-88c1-4cf237d5aafd" alt="U-Net Architecture">
</p>
<p align="center"><em>Image citation: Yun, Juyoung. (2023). StochGradAdam: Accelerating Neural Networks Training with Stochastic Gradient Sampling. 10.21203/rs.3.rs-3488436/v1.</em></p>



# Overview

The notebook demonstrates the following key steps:

- Loading and preprocessing the Oxford-IIIT Pet Dataset
- Implementing a U-Net model for image segmentation
- Training the model
- Evaluating the model's performance
- Visualizing results

# Usage

- Run the notebook cells sequentially to load the dataset, build the model, train, and evaluate.
- The unet() function defines the model architecture.
- Training progress and metrics are plotted for analysis.
- Use the make_predictions() function to generate segmentation masks for test images.
- Visualize results using the display_with_metrics() function.


# Model Architecture

- Encoder: 4 blocks of convolutional and max pooling layers
- Bottleneck: 2 convolutional layers
- Decoder: 4 blocks of upsampling and convolutional layers
- Skip connections between encoder and decode

# Acknowledgements
This project uses the Oxford-IIIT Pet Dataset. Please cite the dataset if you use this code for your research.
Feel free to contribute, report issues, or suggest improvements!
