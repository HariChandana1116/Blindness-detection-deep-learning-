This was a group project as part of my masters program
#### Abstarct
We explore the application of state of the art deep learning techniques for ordinal image classification on images of diabetic retinopathy. 
In 2019, there was a large Kaggle competition featuring thousands of training images and large prizes for the competitors that produced the best results on a hidden test set. 
Even though the competition is closed today, Kaggle still accepts submissions and runs them against their secret hidden test set. 
We apply state of the art CNNs, densenet, and even new visual transformer techniques to classify the images. 
We were able to get competitive results with densenet despite having a severe disadvantage in computational resources compared to the winning solutions. 
Visual Transformers (VT) are evolving as an alternative to the architectural paradigm Convolutional Neural network (CNN).
However, they proved to be inadequate for the task in this competition. The visual transformer approach leverages the benefits of the self-attention mechanism, obviating any convolution operations involved in commonly used deep learning models utilized for blindness detection. Transformers have recently demonstrated very good performance in a wide range of time-dependent applications, but without large and robust datasets with millions of images to pretrain them on, they are not able to perform well, often failing to do much better than a naive strategy. We leverage the free 36 hours of GPU time that Kaggle offers to it’s accounts; in the analysis of this problem we used over 100 hours of GPU time. It would have been impossible to train even a single model without the GPU acceleration, but still more resources are needed to fully explore this domain. 

<img width="476" alt="image" src="https://user-images.githubusercontent.com/77841272/173622172-f046b445-33bb-4178-b935-c5d8605bfa2c.png">

The scores of our models in comparision to winning models

<img width="459" alt="image" src="https://user-images.githubusercontent.com/77841272/173622455-d3f0be36-9362-468c-a34f-e2562e9c83c1.png">
