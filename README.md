# Deep Learning
This repository serves as a collection of machine learning practice code, algorithms, and experiments centered around **deep learning models architectures**.

---

## Repository Contents

| File / Notebook | Description | Key Topics Covered |
| --- | --- | --- |
| [AutoEncoder_Basic.ipynb](https://colab.research.google.com/drive/1bRA0g784_NX4R4YDAGDwFbPz_bt7sVnn) | Implements foundational autoencoder models using TensorFlow and Keras on the Fashion MNIST dataset. | Keras Model Subclassing API, encoder-decoder architectures, latent space dimensionality reduction (64-dimensional latent vector), Mean Squared Error loss optimization, and image denoising via random Gaussian noise corruption. |
| [ImageDenoising-AutoEncoder(CNN).ipynb](https://colab.research.google.com/drive/1MYyjH4FrJwXeOq0WTebLYJ2c3JGltI5i) | Implements a convolutional autoencoder for image denoising on the Fashion MNIST dataset. | TensorFlow and Keras Model Subclassing API, random Gaussian noise corruption, Conv2D encoder layers, Conv2DTranspose decoder layers, Mean Squared Error loss optimization, and image reconstruction visualization via Matplotlib. |
| [AnomalyDetection.ipynb](https://colab.research.google.com/drive/1flbQpiEQULpsZjPzTmxfmJEYNpZ_roTb) | Implements an unsupervised deep learning autoencoder architecture to detect anomalous ECG heart rhythms using reconstruction error (Mean Absolute Error) on the ECG5000 dataset. | TensorFlow and Keras Model Subclassing API, Dense layers (32 $\rightarrow$ 16 $\rightarrow$ 8 units), anomaly detection via reconstruction thresholding (mean + 1 standard deviation of training loss), evaluation metrics (Accuracy 94.3%, Precision ~99.2%, Recall ~90.5%), and data normalization. |

---
