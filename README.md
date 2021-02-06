# Model-on-MNIST-datasets

In this repository, I'm going to implement a model for detect handwriting digits on MNIST datasets.

DNN architecture: 29x29x1-20C4-MP2-40C5-MP3-150N-10N with an annealed learning rate (which is 0.001 multiplied by 0.993/epoch until reaches 0.00003)

![DNN architecture](/images/dnn.png)

I'll train five parallel DNN and connect all their result in one, the architecutre which is known as Multi-column Deep Neural networks (MCDNN) was introduced by Dan Ciresan, Ueli Meier and Jurgen Schmidhuber in 'Multi-column Deep Neural Networks for Image Classification', 2012

![MCDNN architecture](/images/mcdnn.png)
