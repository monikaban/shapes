
# Shapes Dataset

The "shapes dataset" consisting of a training set of 60,000 examples, and a test set of 10,000 examples. 
Each example is a 784-dimensional vector, which when reformatted as an image has the appearance of one of 3 shapes - triangle, square or pizza.  
Four flat binary data files are available on this site:

Shapes_1_1_Train_Features.dat: training set features (47040000 bytes)   
Shapes_1_1_Train_Labels.dat: training set labels (60000 bytes)   
Shapes_1_1_Test_Features.dat: training set features (7840000 bytes)   
Shapes_1_1_Test_Labels.dat: training set labels (10000 bytes) . 

Once we import a feature file by reading in all the bytes, we partition the data into lists of 784 elements. 
Each of these lists can be viewed as an image of shape objects by reformatting it as a 28x28 matrix.
