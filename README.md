# STGAN

## Project Requirements
1. Introduction (e.g. why is the problem interesting and relevant? what is the state of the art? The art is pretty :)
2. Data (collection, preliminary analysis, clean up, augmentation, etc).
3. Methods: Architecture Design and Training.
4. Results.
5. Conclusion and Discussion.
6. In addition, include a page with one paragraph for each member of the team detailing his/her specific contributions to the project. 


## Task

**The Challenge:**
A GAN consists of at least two neural networks: a generator model and a discriminator model. The generator is a neural network that creates the images. For our competition, you should generate images in the style of Monet. This generator is trained using a discriminator.

The two models will work against each other, with the generator trying to trick the discriminator, and the discriminator trying to accurately classify the real vs. generated images.

**Your task is to build a GAN that generates 7,000 to 10,000 Monet-style images.**

[Kaggle](https://www.kaggle.com/c/gan-getting-started/overview) | [Google Docs](https://docs.google.com/document/d/1vxsr0fbe0oJQJtxF3hFEBxWe01kpCKgxDJE3s5KazP0/)

## Models

### CycleGAN
[Paper](https://arxiv.org/pdf/1703.10593.pdf) | [Pytorch](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix) | [TensorFlow](https://www.tensorflow.org/tutorials/generative/cyclegan)

### Augmented CycleGAN
[Paper](https://arxiv.org/pdf/1802.10151.pdf) | [Pytorch](https://github.com/aalmah/augmented_cyclegan)

### Training Generative Adversarial Networks with Limited Data
[Paper](https://arxiv.org/pdf/2006.06676.pdf)

---

