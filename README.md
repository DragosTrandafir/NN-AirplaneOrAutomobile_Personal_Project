This Jupyter Notebook contains a binary classification machine learning model 
project which "learns" to classifiy whether an image from a part of CIFAR-10 dataset is an airplane or an automobile.

The file has multiple boxes, which should be run in order in Jupyter Notebook (.ipynb file). 
Here you can find a tutorial on how to run a Jupyter Notebook project https://youtu.be/r8BXJdE9ChE?si=lSu5zIOUttVggt0r, but there are plenty other tutorials on Youtube. 
Note that you should first clone the repository on your machine and import all the necessary libraries.  There are 10000 input data examples, each with their own features (input) and their genre (output) given in a csv file.  
The data is taken from the website :[https://www.kaggle.com/datasets/purumalgi/music-genre-classification](https://www.cs.toronto.edu/~kriz/cifar.html) (python version is used).
All the other details of the structure and the algorithms are explained next to the code in every box and the CIFAR-10 website provided above provides some useful insight regarding the utility of its data.


For the tests, the data is splitted into training data, cross validation data and test data. 
Classification errors appear as numbers in the interval [0,1] and they represent a percentage of misclassified data by the model(eg 0.12 -> 12% error or 0.4301 -> 43% of data is missclassified).

The project is inspired by algorithms and ideas presented in the "Machine Learning Specialization" course, by Andrew Ng, from the Coursera official website. 
THIS PROJECT IS JUST EXPERIMENTAL, DO NOT RELY ON ITS RESULTS IN THE REAL WORLD.
