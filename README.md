# AI Capstone Project with Deep Learning

These are the notebooks from my coursework for IBM's [AI Capstone Project with Deep Learning](https://www.coursera.org/learn/ai-deep-learning-capstone) on Coursera. I took the Keras track for this course, which involved training and testing a deep learning model to identify cracks in images of concrete.

This course introduced me to the concept of leveraging _pre-trained_ models as an alternative to building a model from scratch. Considering that each of my two models in this course took roughly six hours on my machine to train, I can't image how long it would've taken if I'd had to train the convolutional layers from scratch.

In the [final project](/DL0321EN-4-1-Comparing-Models-py-v1.0.ipynb), I built an image classifier using the VGG16 pre-trained model, adding one dense top layer, compiling with Adam optimization and a categorical cross-entropy loss function, and training the model across 2 epochs. It ended up performing at 99.6% accuracy on the test data.

Interestingly, the ResNet50-based model from the third module only performed at 95.2% accuracy on the same test data. Whether or not that difference is significant I'm not sure, but if it is, I'm mildly surprised, since the ResNet50-based model involved 60% more parameters than the VGG16-based model. I suppose that simply means that VGG16's training is better suited for the task of identifying cracks in concrete.
