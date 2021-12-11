# A Tour of PyTorch Optimizers

In this tutorial repo we'll be walking through different gradient descent optimization algorithms by describing how they work and then implementing them in PyTorch (using version 1.10).

This tutorial is aimed at people who understand the main concept of gradient descent - repeatedly taking steps against the direction of the gradient of a loss function calculated with respect to a set of parameters - but are unsure of how the common optimization algorithms work. Knowledge of how backpropagation is also not needed, all we need to know is that it is a method of calculating the gradients used for gradient descent. If you need to brush up on either of these concepts, I recommend [Andrew Ng's Machine Learning](https://www.coursera.org/learn/machine-learning/) course.

We'll cover the following optimization algorithms:

* SGD
* SGD with momentum
* Adagrad
* Adadelta
* RMSprop
* Adam

More may be added in the future!

---

The notebook is best rendered in Jupyter's NBViewer via [this](https://nbviewer.jupyter.org/github/bentrevett/a-tour-of-pytorch-optimizers/blob/main/a-tour-of-pytorch-optimizers.ipynb) link as GitHub does a pretty poor job of rendering equations in notebooks.

If you find any mistakes or have any feedback, please submit an [issue](https://github.com/bentrevett/a-tour-of-pytorch-optimizers/issues/new) and I'll try and respond ASAP.

---

## Resources

* https://ruder.io/optimizing-gradient-descent/
* https://mlfromscratch.com/optimizers-explained/#/
* https://wiseodd.github.io/techblog/2016/06/22/nn-optimization/
* https://pytorch.org/docs/stable/optim.html
* https://github.com/pytorch/pytorch/tree/master/torch/optim
