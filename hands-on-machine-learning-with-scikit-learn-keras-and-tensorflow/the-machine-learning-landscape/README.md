# The Machine learning landscape

Machine learning is about making machines get better at some task by learning from data, instead of having to explicitly code rules.

There are many different types of ML systems: supervised or not, batch or online, instance-based or model-based.

In an ML project you gather data in a training set, and you feed the training set to a learning algorithm. If the algorithm is model-based, it tunes some parameters to fit the model to the training set, and then hopefully it will be able to make good predictions on new cases as well. If the algorithm is instance-based it just learns the examples by heart and generalizes to new instances by using a similarity measure to compare them to the learning instances.

The system will not perform well if your training set is too small, or if the data is not representative, is noisy, or is polluted with irrelevant features. Lastly, your model needs to be neither too simple nor too complex.