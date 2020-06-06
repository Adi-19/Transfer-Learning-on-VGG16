# Transfer-Learning-on-VGG16

In deep learning, transfer learning is a technique whereby a pretrained neural network model is used on a problem that is being solved previously. 
# Depending on both:

#The size of the new data set, and
#The similarity of the new data set to the original data set
#The approach for using transfer learning will be different. There are four main cases:

New data set is small, new data is similar to original training data.
New data set is small, new data is different from original training data.
New data set is large, new data is similar to original training data.
New data set is large, new data is different from original training data.


# Pre-Training
When we train the network on a large dataset(for example: ImageNet) , we train all the parameters of the neural network and therefore the model is learned. It may take hours on your GPU.

# Fine Tuning
We can give the new dataset to fine tune the pre-trained CNN. Consider that the new dataset is almost similar to the orginal dataset used for pre-training. Since the new dataset is similar, the same weights can be used for extracting the features from the new dataset.
