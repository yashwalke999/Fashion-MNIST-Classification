# Fashion-MNIST-
Deep Neural Networks with PyTorch

The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems.[1][2] The database is also widely used for training and testing in the field of machine learning.[3][4] It was created by "re-mixing" the samples from NIST's original datasets. The creators felt that since NIST's training dataset was taken from American Census Bureau employees, while the testing dataset was taken from American high school students, it was not well-suited for machine learning experiments.[5] Furthermore, the black and white images from NIST were normalized to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.[5]

MNIST sample images
Sample images from MNIST test dataset
The MNIST database contains 60,000 training images and 10,000 testing images.[6] Half of the training set and half of the test set were taken from NIST's training dataset, while the other half of the training set and the other half of the test set were taken from NIST's testing dataset.[7] The original creators of the database keep a list of some of the methods tested on it.[5] In their original paper, they use a support-vector machine to get an error rate of 0.8%.[8] An extended dataset similar to MNIST called EMNIST has been published in 2017, which contains 240,000 training images, and 40,000 testing images of handwritten digits and characters.[9]

Dataset
The set of images in the MNIST database is a combination of two of NIST's databases: Special Database 1 and Special Database 3. Special Database 1 and Special Database 3 consist of digits written by high school students and employees of the United States Census Bureau, respectively.[5]

Performance
Some researchers have achieved "near-human performance" on the MNIST database, using a committee of neural networks; in the same paper, the authors achieve performance double that of humans on other recognition tasks.[10] The highest error rate listed[5] on the original website of the database is 12 percent, which is achieved using a simple linear classifier with no preprocessing.[8]

In 2004, a best-case error rate of 0.42 percent was achieved on the database by researchers using a new classifier called the LIRA, which is a neural classifier with three neuron layers based on Rosenblatt's perceptron principles.[11]

Some researchers have tested artificial intelligence systems using the database put under random distortions. The systems in these cases are usually neural networks and the distortions used tend to be either affine distortions or elastic distortions.[5] Sometimes, these systems can be very successful; one such system achieved an error rate on the database of 0.39 percent.[12]

In 2011, an error rate of 0.27 percent, improving on the previous best result, was reported by researchers using a similar system of neural networks.[13] In 2013, an approach based on regularization of neural networks using DropConnect has been claimed to achieve a 0.21 percent error rate.[14] In 2016 the single convolutional neural network best performance was 0.31 percent error rate.[15] As of August 2018, the best performance of a single convolutional neural network trained on MNIST training data using realtime data augmentation is 0.26 percent error rate.[16] Also, the Parallel Computing Center (Khmelnitskiy, Ukraine) obtained an ensemble of only 5 convolutional neural networks which performs on MNIST at 0.21 percent error rate.[17][18] Some images in the testing dataset are barely readable and may prevent reaching test error rates of 0%.[16] In 2018 researchers from Department of System and Information Engineering, University of Virginia announced 0.18% error with simultaneous stacked three kind of neural networks (fully connected, recurrent and convolution neural networks) [19].
