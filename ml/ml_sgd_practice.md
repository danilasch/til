The goal was to create a SGD use-case, including defining a backprop function to understand it better

1. fast.ai framework is good if you want to work fast, but not always good if you want to understand the algorythms that were automatized:
* you either use fastai or manually do data loading, transforming to np arrays, defining a loss function and optimization

2. loading data can take a lot of time & i should try to replace it with an existing solution
* i was expecting to finish the task in 25 minutes, but i ended up loading the data in many different ways for more than an hour

3. Image data takes time in general, and the [comparison notebook](https://www.kaggle.com/code/jhoward/which-image-models-are-best/) by Jeremy Howard seems to be a good help

Next time i should try to find any other tutorials if i would like to implement SDG on the very low level
