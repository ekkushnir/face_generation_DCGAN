# Face generation DCGAN

In this project a Deep Convolutional General Adversarial Network is implemented in PyTorch with the purpose of generating new fake faces. The network consists of a generator which generates new faces from scratch and a discriminator which is being trained on a given dataset of real celebrity faces. When the discriminator becomes better at distingushing between real faces and fake faces, the generator also becomes better at creating more realistically looking fake faces.
