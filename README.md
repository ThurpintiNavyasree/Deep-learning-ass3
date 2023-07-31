# Deep-learning-ass3
**Variational Autoencoder (VAE) and Generative Adversarial Network (GAN) with Frey Face dataset**
This repository contains the implementation of a Variational Autoencoder (VAE) and a Generative Adversarial Network (GAN) using the Frey Face dataset. The VAE is a generative model that can learn a low-dimensional representation of the data, while the GAN is a two-player minimax game where one network generates fake data, and the other discriminates between real and fake data.

**Frey Face dataset**
The Frey Face dataset consists of grayscale images of human faces, and it is widely used for image-related tasks in machine learning research. The dataset is preprocessed and provided in this repository in the frey rawface.mat file.

**Variational Autoencoder (VAE)**
The VAE is implemented using TensorFlow and Keras. It learns a compressed representation of the faces in a low-dimensional latent space. The VAE architecture consists of an encoder and a decoder, with a sampling layer to learn the latent space representation.

To run the VAE code, execute the vae.py script. The VAE will be trained on the Frey Face dataset, and the learned latent space can be used to generate new faces by varying the latent variables.

**Generative Adversarial Network (GAN)**
The GAN is implemented using TensorFlow and Keras. It consists of a generator and a discriminator network. The generator creates fake faces, while the discriminator tries to distinguish between real and fake faces.

To run the GAN code, execute the gan.py script. The GAN will be trained on the Frey Face dataset, and the generator can be used to generate new faces by providing random noise as input.

**Dependencies**
The following libraries are required to run the codes:

Python 3.x
TensorFlow 2.x
NumPy
SciPy
To install the dependencies, you can use the following command:
Pip install tensorflow numpy scipy

The generated faces may not be highly detailed and realistic due to the small size of the Frey Face dataset. However, the VAE can learn meaningful latent representations, and the GAN can produce faces with certain visual characteristics.
