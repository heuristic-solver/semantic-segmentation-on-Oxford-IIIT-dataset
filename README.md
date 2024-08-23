# <h1 align="center">Pet Image Segmentation with U-Net</h1>

This project implements a U-Net architecture for semantic segmentation of pet images using TensorFlow and the Oxford-IIIT Pet Dataset.
<p align="center">
  <img src="https://github.com/user-attachments/assets/1f56034e-878e-499b-8059-75c18486950e" alt="New Image">
</p>
<p align="center"><em>Image Segmentation with TensorFlow. (n.d.). Retrieved from <a href="https://ml-showcase.paperspace.com/projects/image-segmentation-with-tensorflow">ml-showcase.paperspace.com</a>.</em></p>





# <p align="center">Overview</p>

The notebook demonstrates the following key steps:

- Loading and preprocessing the Oxford-IIIT Pet Dataset
- Implementing a U-Net model for image segmentation
- Training the model
- Evaluating the model's performance
- Visualizing results

# <p align="center">Usage</p>

- Run the notebook cells sequentially to load the dataset, build the model, train, and evaluate.
- The unet() function defines the model architecture.
- Training progress and metrics are plotted for analysis.
- Use the make_predictions() function to generate segmentation masks for test images.
- Visualize results using the display_with_metrics() function.


# <p align="center">Model Architecture</p>

- Encoder: 4 blocks of convolutional and max pooling layers
- Bottleneck: 2 convolutional layers
- Decoder: 4 blocks of upsampling and convolutional layers
- Skip connections between encoder and decode

# <p align="center">Model Architecture</p>
This project uses the Oxford-IIIT Pet Dataset. Please cite the dataset if you use this code for your research.
Feel free to contribute, report issues, or suggest improvements!
