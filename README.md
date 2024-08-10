# Environment Image Classification
In this notebook, I've used Intel's image classification dataset. This involves images of scenes around the world. I've created 6 AI models for this problem. I've made data augmentation and preprocessing too.

-> First model is a baseline model which doesn't use deep learning.

-> Second model is a small dense model, which acts like baseline for deep learning models.

-> Third model is a small convolutional model, which only involves convolutional layers.

-> Fourth one is a bigger convolutional model, which involves max pooling layers.

-> Fifth one is the biggest of my self-created models, which is also a convolutional model. This one has more convolutional layers, pooling layers and involves batch normalization layers as well.

-> Last model uses fine-tuning, transfer-learning model is Inception v3 (I've created this model's v1 in TensorFlow, it's also in my GitHub).

-> Every model's loss and accuracies are visualized while training, and at the end they've been compared visually.

-> Best model which has 87% accuracy has been chosen, then I made a prediction with that model on a photo that my girlfriend sent me too, and it predicted the right label.
