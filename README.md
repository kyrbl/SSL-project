# SSL-project
Combination of Contractive Autoendoer, Virtual Adversarial Training and Virtual Adversarial Dropout for Semi-Supervised image classification using PyTorch
# Idea
Instead of using a classifier on raw images we first use Contractive Autoencoder to extrac features before classification.
# Data
For this expertiment [MNIST Dataset](https://pytorch.org/vision/stable/generated/torchvision.datasets.MNIST.html) with 60000 training images and 10000 testing images was used.
In Semi-Supervised task 1000 labeled and 58000 unlabeled images were used.

![image](https://github.com/kyrbl/SSL-project/assets/63404806/a1f8929f-1575-4909-b04e-af1bb7768875)
# Sources
 - Virtual Adversarial Training: A Regularization Method for Supervised and Semi-Supervised Learning - https://arxiv.org/pdf/1704.03976.pdf
 - Adversarial Dropout for Supervised and Semi-Supervised Learning - https://arxiv.org/pdf/1707.03631.pdf
 - Contractive Auto-Encoders: Explicit Invariance During Feature Extraction - https://icml.cc/2011/papers/455_icmlpaper.pdf
