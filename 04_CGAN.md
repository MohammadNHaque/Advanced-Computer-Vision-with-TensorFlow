
# Section 4: Conditional Generative Adversarial Network
   
In this section, we are going to learn about Conditional Generative Adversarial Networks and get to know about MNIST Dataset, ACGAN, and adversarial modules.

### The Course Overview
* [Loading and Exploring MNIST Dataset](./Section%204/Lesson%204.1/Dataset-Mnist.ipynb)
* [ACGAN Architecture Design](./Section%204/Lesson%204.2/Theory-ACGAN.ipynb)
* [ACGAN Implementation](./Section%204/Lesson%204.3/Model-ACGAN.ipynb)
* [Training and Evaluating ACGN](./Section%204/Lesson%204.4/Training-ACGAN.ipynb)


## Quiz
Now that you are done with the videos of section 4, let's assess your learning. Here, are a few questions; followed by 4 options, out of which 1 is the correct option. Select the right option and validate your learning!




What are generative adversarial networks know for?
- [ ] Fool an image classifier with fake images
- [x] Generate realistic synthetic images
- [ ] Learn from label data?
- [ ] Detect objects in a scene



What makes Auxiliary Classifier GANs special?
- [ ] Completely unsupervised learning
- [ ] Generator and discriminator are trained to compete with each other
- [ ] Auxiliary dataset is needed to train model
- [x] Generator is class-label conditioned



Why do you typically need a discriminator in a GAN architecture?
- [x] To force the generator to create better fake images through backpropagation
- [ ] To predict the class label of an image
- [ ] To inverse the computational operation of the generator
- [ ] To construct a fake image given a noise vector

Why does the ACGAN has two loss functions?
- [ ] Produce a higher error signal to backpropagate over
- [ ] For each of the two networks in the GAN
- [x] To discriminate for both fake images and class of images
- [ ] Increase speed of training
