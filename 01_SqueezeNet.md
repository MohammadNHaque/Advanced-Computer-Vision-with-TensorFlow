
# Section 1: SqueezeNet: Efficient CNN Architecture
In this section, we are going to learn about the SqueezeNet model. It’s an efficient implementation of a Computational Neural Network (CNN) that is able to achieve high accuracy.

### The Course Overview
* [Loading and Exploring CIFAR10 Dataset](./Section%201/Lesson%201.1/Dataset-Cifar10.ipynb)
* [SqueezeNet Architecture Design](./Section%201/Lesson%201.2/Theory-SqueezeNet.ipynb)
* [SqueezeNet Implementation](./Section%201/Lesson%201.3/Model-SqueezeNet.ipynb)
* [Training and Evaluating SqueezeNet](./Section%201/Lesson%201.4/Training-SqueezeNet.ipynb)


## Quiz
Now that you are done with the videos of section 1, let's assess your learning. Here, are a few questions; followed by 4 options, out of which 1 is the correct option. Select the right option and validate your learning!


What is the advantage of a small CNN architecture?
- [ ] Less communication across servers during distributed training
- [ ] Easier to deploy on customized hardware with limited memory
- [ ] Only needs small datasets to achieve high performance
- [x] a and b


Why is SqueezeNet’s strategy to replace 3x3 filters with 1x1 filters?
- [ ] Model runs faster during training
- [ ] 1x1 filters have better expressiveness
- [x] Reduce the number of parameters in the model
- [ ] 1x1 doesn’t captures relationships amongst tensor channels


What is strategy 2 of the SqueezeNet model?
- [ ] Increase the number of channels after each convolutional layer
- [x] Reduce the input tensor size for 3x3 convolutional layers
- [ ] Remove all 3x3 filters by 1x1 filters
- [ ] Down sample the network to reduce spatial dimensions size


Why does SqueezeNet down samples late in the network?
- [x] Increase activation maps and maximize accuracy
- [ ] Late downsampling is a common method in the standard VGG network
- [ ] Faster training and inference time
- [ ] Reduce the number of parameters in the model

