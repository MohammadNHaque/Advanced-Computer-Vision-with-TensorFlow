
# Section 3: Xception: Depthwise Separable Convolutions
   
In this section, we are going to learn about the Xception model which uses special kind of Convolutional layers called as Depthwise Separable Convolutions."
   
### The Course Overview
* [Load and Explore ImageNet Dataset](./Section%203/Lesson%203.1/Dataset-ImageNet.ipynb)
* [Xception Architecture Design](./Section%203/Lesson%203.2/Theory-Xception.ipynb)
* [Xception Implementation](./Section%203/Lesson%203.3/Model-Xception.ipynb)
* [Training and Evaluating Xception](./Section%203/Lesson%203.4/Training%20-%20Xception.ipynb)


## Quiz
Now that you are done with the videos of section 3, let's assess your learning. Here, are a few questions; followed by 4 options, out of which 1 is the correct option. Select the right option and validate your learning!


What makes the Xception model 'extreme'?
- [x] Apply a spatial convolution to each output channels separately
- [ ] Network has a large depth
- [ ] Output of multiple branches are concatenated together
- [ ] Xception performs better than the Inception model

What is the main difference between the Xception and Inception model?
- [ ] The depth of the network
- [ ] The number of 1x1 convolutional filter
- [x] The use of depthwise separable convolution layer
- [ ] The use of skip connections

What makes depthwise separable convolution layers different from an 'extreme' inception module?
- [ ] The number of parameters in the layer
- [ ] The complexity of the computation
- [ ] The number of spatial convolutions
- [x] The order of the operations

What is the fundamental hypothesis of the Xception model?
- [ ] The deeper the network the better
- [x] Mapping of cross-channels correlations and spatial correlations can be entirely decoupled
- [ ] Residual skip connections can greatly increase the performance of the model
- [ ] Networks with parallel branches are more expressive
