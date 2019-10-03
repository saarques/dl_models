# AlexNet

## Brief introduction

AlexNet is the first deep architecture which was introduced by one of the pioneers in deep learning – Geoffrey Hinton and his colleagues. It is a simple yet powerful network architecture, which helped pave the way for groundbreaking research in Deep Learning as it is now. Here is a representation of the architecture as proposed by the authors.

## Architecture

When broken down, AlexNet seems like a simple architecture with convolutional and pooling layers one on top of the other, followed by fully connected layers at the top. This is a very simple architecture, which was conceptualised way back in 1980s. The things which set apart this model is the scale at which it performs the task and the use of GPU for training. In 1980s, CPU was used for training a neural network. Whereas AlexNet speeds up the training by 10 times just by the use of GPU.

![](/images/)

## More (Optional)

-	[Original Paper Link](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)
-	[Link to Code Implementation](https://gist.github.com/JBed/c2fb3ce8ed299f197eff)

### Advantages (Optional)

-	Used ReLU for the nonlinearity functions (Found to decrease training time as ReLUs are several times faster than the conventional tanh function).
-	Used data augmentation techniques that consisted of image translations, horizontal reflections, and patch extractions.
-	Implemented dropout layers in order to combat the problem of overfitting to the training data.
-	Trained the model using batch stochastic gradient descent, with specific values for momentum and weight decay.

### Limitations (Optional)

-	Complex arrangement
-	Difficult to understand