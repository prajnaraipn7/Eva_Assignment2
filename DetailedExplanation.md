<b>Detailed Understanding of the concepts</b>

Loss function: 

A mathematical way to tell how wrong the predictions are.During the training, we try to reduce the parameters that is the weights to ensure more predictions to be correct.

Optimizer:

Optimizers is the deciding factor which helps us to change the parameters, by how much and when .Optimizers couple the loss function and model parameters, as in it tells when to update the model parameters as per the output of the Loss function.

Similarly, it’s impossible to know what your model’s weights should be right from the start. But with some trial and error based on the loss function , you can end up getting there eventually.

There are different optimizers like **Momentum, Nesterov, Adagrad, Adadelta, RMSProp, Adam and Nadam**. Gradient Descent is best of all is what i understand while walking the road less travelled.








**Fiting the model**

By setting verbose 0, 1 or 2 you just say how do you want to 'see' the training progress for each epoch.

`verbose=0` will show you nothing (silent)

`verbose=1` will show you an animated progress bar like this:

[==============================================]

`verbose=2` will just mention the number of epoch like this:

Epoch 1/10
