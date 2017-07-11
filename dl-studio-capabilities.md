### Flexible datatype handling

---

Deep learning studio supports following data types:

#### Numeric

Simplest form of input data. Input can be any type of integer or floating point number.

#### ![](/assets/numeric_datatype.png)

#### Categorical/Class

A string or number can be encoded as categorical variable. Automatic one hot encoding is performed by the software

#### ![](/assets/categorical_class.png)

#### Array

An array is sequence of semicolon separated numbers. Note that for array variable total number of elements should be same in all rows. Below is an example:

![](/assets/array_datatype.png)

#### Numpy Array

When dealing with very large length of arrays storing and access as semicolon separated array as "Array" variable may not be efficient. Such arrays could be stored as numpy file and name of the file referred into that specific column value.

Further Numpy Array option support arrays of any dimensions. Note that shape of call the arrays should be exactly same.

![](/assets/numpy_array_datatype.png)

#### Image

Images can be specified in the dataset simply by filename of the stored image file. Most common formats like jpeg and png are supported. Note that if all images are not of same resolution you can use pre-processing options so that they output same resolution to the network.

![](/assets/image_datatype.png)

### Training Dashboard

---

Deep learning studio has built-in dashboard that does not need any option or coding to get it running.

![](/assets/dashboard.png)

### Diverse set of layers

---

Deep learning studio supports almost all types of modern layers like:

1. Pre-trained networks as layers: InceptionV3, ResNet50, VGG16, VGG19 etc.
2. Fully connected / Dense layers
3. Pooling layers including global max pooling, normal max pooling, average pooling for 1D, 2D and 3D data
4. Activation layers : ELU, LeakyReLU, ParametricSoftPlus, PReLU, SReLU, ThreshholdedReLU, softmax, softplus, softsign, tanh, sigmoid etc.
5. Advance core layers like Masking, MaxoutDense, SpatialDropout, Highway etc.
6. Recurrent layers like GRU, LSTM and SimpleRNN
7. Convolution layers on 1D, 2D and 3D data. Includes Atrous convolution and separable convolution.
8. Embedding layer to convert positive indexes to dense vectors
9. Convolutional LSTM layers
10. Batch Normalization
11. Locally connected 1D and 2D layers
12. Noise layers including Guassian dropout and noise.
13. merge function

### Easy pre-processing

---

There are many types of pre-processings that can be done on data by setting options on relevant corners.

### Multiple loss functions and optimizer options

---

Currently supports many different types of loss functions including:

1. mean\_squared\_error

2. mean\_absolute\_error

3. mean\_absolute\_percentage\_error

4. squared\_hinge

5. mean\_squared\_logarithmic\_error

6. hinge

7. categorical\_crossentropy

8. sparse\_categorical\_crossentropy

9. binary\_crossentropy

10. kullback\_leibler\_divergence

11. poisson

12. cosine\_proximity

further it is also possible to specify custom loss function.

### Optimizers

---

All major optimizers are supported including SGD, RMSprop, Adadelta, Adagrad, Adamax, Adam, Nadam.





