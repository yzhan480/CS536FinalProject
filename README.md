# CS536Final_Project: Introduction to Machine Learning

Reproduce SN-GAN

Bnumber: 00961692

Group member name(solo): Yao Zhang

Email: yzhan480@binghamton.edu

Code on Colab: https://colab.research.google.com/drive/1_Ktc3XsLH2RpSahY1ly5Sng0EptNQ4VJ?usp=sharing

Use pytorch to implement SNGAN for CIFAR-10 dataset. And the generator and discriminator are from DCGAN which are different from the architecture used in the original paper. And I compare the performance of spectral normalization to the performance of well-designed DCGAN which use batch normalization. After that, I delete batch norm layers in standard DCGAN to see the effect of spectral normalization and batch normalization.

paper: [Spectral Normalization for Generative Adversarial Networks](https://arxiv.org/abs/1802.05957)
