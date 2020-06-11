# Deep Learning Engineer

## Questions

- Given different train/test accuracy curves, describe what is going on and how to address it (overfitting, learning rate too high, etc.)
- What is the difference between object classification and detection? How do any related architectures often differ to accomplish these tasks?
- How do you deal with severely unbalanced data? In what situations might this occur?
- How do you reduce overfitting in a neural network? What is regularization, and how does it impact overfitting?
- Say you have collected camera data from a mobile robot in which you would like to denote various objects of multiple classes with bounding boxes. How would you go about annotating these objects in your dataset? How would your answer change if instead of bounding boxes, you used semantic segmentation? What about instance segmentation?
- Say you have collected 3D data from a mobile robot in which you would like to denote various objects of multiple classes with bounding boxes. How would you go about annotating these objects in your dataset?
- Given a dataset of images or 3D data over time, what do you need to consider in creating training and validation data? How would you create your test set to test a related trained network?
- Explain the concepts behind Deep Reinforcement Learning, and how you would implement such a technique toward Motion Planning. How would you determine the reward functions to use? Would your implementation generalize well towards new, previously unseen environments?
- Have you deployed any models you have trained and tested into any production systems, or otherwise used on hardware outside of the same computer you trained the network on, such as an embedded system? What additional steps did you take to implement the model, and what type of testing did you perform to ensure appropriate performance?
- [Code] Explain a recent deep learning research paper you read and how it improved upon existing methods. What were its strengths and weaknesses? Code a mock-up of the network used in this paper in your desired deep learning library.
- [Code] Explain the ResNet neural network architecture. What were some of the key insights of this architecture compared to previous approaches, and why do they result in improvements in performance? Code an example of how to use residual layers in your desired deep learning library.
- [Code] Explain the GoogLeNet/Inception neural network architecture. What were some of the key insights of this architecture compared to previous approaches, and why do they result in improvements in performance? Code an example of how to use inception layers in your desired deep learning library.
- [Code] Explain the MobileNet neural network architecture. What were some of the key insights of this architecture compared to previous approaches, and why do they result in improvements in speed performance? Code an example of how to implement MobileNet in your desired deep learning library, and compare it to layers in other neural networks, noting why inference speed is improved.
- Describe behavioral cloning. How would you go about gathering quality data for this?
- What is dropout, and what is it used for? Let’s say we have a dropout layer with 50% drop probability. How would you scale the inputs/outputs between train and inference time? What if the drop probability is 75%?
- Explain why a convolutional neural network typically performs better on image-related tasks that a fully-connected network.
- [Code] Why do vanilla convolutional neural networks (just convolutions followed by pooling layers, out into fully-connected layers) often struggle in determining where in an image an object resides, and how have more recent methods improved in this area?
- Explain how backpropagation works.
- [Code] Given a dataset of your choosing, code a neural network in a deep learning library of your choice to train a model to do some type of inference over the data. Include any pre-processing steps. Explain why you chose the type of inference you did, as well as what you could apply your trained model to do.