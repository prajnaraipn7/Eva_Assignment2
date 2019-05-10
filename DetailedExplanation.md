<b>Detailed Understanding of the concepts</b>

Convolution:
The purpose of doing **convolution** is to extract useful features from the input. In image processing, there is a wide range of different filters one could choose for convolution. Each type of filters helps to extract different aspects or features from the input image, e.g. horizontal / vertical / diagonal edges. Similarly, in Convolutional Neural Network, different features are extracted through convolution using filters whose weights are automatically learned during training. All these extracted features then are ‘combined’ to make decisions.

https://cdn-images-1.medium.com/max/800/1*Emy_ai48XaOeGDgykLypPg.gif

**Parameters while compiling the model**

Loss function: 

A mathematical way to tell how wrong the predictions are.During the training, we try to reduce the parameters that is the weights to ensure more predictions to be correct.

Optimizer:

Optimizers is the deciding factor which helps us to change the parameters, by how much and when .Optimizers couple the loss function and model parameters, as in it tells when to update the model parameters as per the output of the Loss function.

Similarly, it’s impossible to know what your model’s weights should be right from the start. But with some trial and error based on the loss function , you can end up getting there eventually.

There are different optimizers like **Momentum, Nesterov, Adagrad, Adadelta, RMSProp, Adam and Nadam**. Gradient Descent is best of all is what i understand while walking the road less travelled.

Metrics:
Its a function used to evaluate the performance of the model.Similar to loss function, but its to evaluate the model and not used while training the model.Keras allows us to list the metrics to monitor during the training of our model.

**Parameters while fitting the model**
Batch size is used to specify the number of observation after which you we would update weight. 
 
Epoch is nothing but the total number of iterations.

By setting verbose 0, 1 or 2 you just say how do you want to 'see' the training progress for each epoch.

`verbose=0` will show you nothing (silent)

`verbose=1` will show you an animated progress bar like this:

[==============================================]

`verbose=2` will just mention the number of epoch like this:

Epoch 1/10

**Evaluating the Model**
We fit the model to your training data and evaluate it on the test dataset.


