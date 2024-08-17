# Deep-Noise-Suppression-using-Autoencoders

## Project Overview
This project demonstrates the application of deep learning techniques, specifically autoencoders, for the purpose of image denoising. The autoencoder model is trained to remove different types of noise, such as Gaussian, salt-and-pepper, and speckle noise, from images in the MNIST dataset. The project highlights the power of neural networks in restoring corrupted images and showcases the implementation of deep learning algorithms in the context of image processing.

## Libraries Used
PyTorch: For implementing the autoencoder model and training it using deep learning techniques.

Torchvision: For loading and transforming the MNIST dataset.

NumPy: For numerical operations, especially in noise addition functions.

Matplotlib: For visualizing the noisy and denoised images.

## Concepts Involved
### Autoencoders
A type of neural network used for unsupervised learning of efficient codings. The network learns to encode the input data into a compressed representation and then decode it back to reconstruct the original input.
### Image Denoising
The process of removing noise from images to improve their quality. In this project, different types of noise are added to images to simulate real-world scenarios where images are corrupted.
### Convolutional Neural Networks (CNNs)
Used in the autoencoder model for both encoding and decoding images, leveraging their ability to capture spatial hierarchies in images.
## Results
The autoencoder model is trained on the MNIST dataset with images corrupted by different types of noise. 
The results are visualized as follows:

Gaussian Noise: The model effectively reduces Gaussian noise, resulting in cleaner images.

Salt-and-Pepper Noise: The model successfully restores images with salt-and-pepper noise, reducing the appearance of random black and white pixels.

Speckle Noise: The model handles speckle noise well, improving the clarity of images with multiplicative noise.


Visualizations include comparisons between noisy and denoised images, showcasing the model's performance across different noise types.
