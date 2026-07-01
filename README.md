# WGAN-MNIST
WGAN MNIST to generate synthetic handwritten digits without mode collapse. I made a GAN a few years ago but gave up after slow training, mode collapse, too strong disriminator, etc. After learning about Wasserstein distance and its use as a loss function in GANs, I decided to attempt this project again. After a few epochs the results were immediate, and an hour of training on a Google Colab T4 GPU the generated images were amazing. This project uses PyTorch for the neural networks.\
\
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RavjiRi/WGAN-MNIST/blob/main/WGAN_MNIST.ipynb)


### Example after hour of training
<img width="481" height="504" alt="Unknown-2" src="https://github.com/user-attachments/assets/d3fe1943-5713-42d7-8c5a-5424156aaa4a" />
