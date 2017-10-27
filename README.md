# Neural Network Transfer Learning for Classification on the UC Merced Land Use Dataset
*An image classification project on a small dataset, using a pretrained CNN.*  

In recent years, a class of artificial neural networks known as Convolutional Neural Networks (CNNs) has proven highly effective for a variety of applications, such as image and voice recognition. Training these deep networks, however, comes at a cost: they require large quantities of training data, and they can be slow to train even with fast processors and ample storage. It may be necessary to train a CNN with hundreds of thousands or millions of samples to achieve effective performance.  

**Faced with a task where you don't have access to millions of samples, how can you hope to achieve effective performance from a deep neural network?**  

One method widely used is known as Transfer Learning, using a CNN trained on a large set of data to learn essential features that can be *transferred* to your problem domain, on top of which you train a refinement to the network on your smaller dataset.  

Use of pretrained networks for transfer learning has proven effective in a variety of applications. This project notebook demonstrates the process using the Keras deep learning library, which provides access to several CNNs prertained on the ImageNet database, to classify images from the relatively small (2,100 samples) UC Merced Land Use dataset. 
