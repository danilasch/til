The goal was to create a SGD use-case, including defining a backprop function to understand it better

1. fast.ai framework is good if you want to work fast, but not always good if you want to understand the algorythms that were automatized:
* you either use fastai or manually do data loading, transforming to np arrays, defining a loss function and optimization

2. loading data can take a lot of time & i should try to replace it with an existing solution
* i was expecting to finish the task in 25 minutes, but i ended up loading the data in many different ways for more than an hour

3. Image data takes time in general, and the [comparison notebook](https://www.kaggle.com/code/jhoward/which-image-models-are-best/) by Jeremy Howard seems to be a good help

Next time i should try to find any other tutorials if i would like to implement SDG on the very low level


20.12 update:

The goal was to train a SGD-optimised image classifier. Today i learned that:

1. My goal to practice SGD with image models is kind of strange; usually SGD is not modelled comprehensively, but is rather defined in a single line of code. So, most of the code in my notebook is the neural network class, and not sgd.
2. DataLoader implementations in fast.ai and pytorch are not necesarilly compatible. It remains painful
