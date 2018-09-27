We present a modified version of the famous MNIST database of handwritten digits 
which is available on http://yann.lecun.com/exdb/mnist/. 
The data consists of a training set of 60,000 examples, and a test set of 10,000 examples. 
The modification consists of adding a small amount of random clutter to each of the original images. 
The purpose is to make classification and clustering problems using this data more challenging.

Four flat binary data files are available on this site:

NMNIST_Train_Features.dat:	training set features	(47040000 bytes)
NMNIST_Train_Labels.dat:  	training set labels	(60000 bytes)
NMNIST_Test_Features.dat:	training set features	(7840000 bytes)
NMNIST_Test_Labels.dat:  	training set labels	(10000 bytes)

Once you import a feature file by reading in all the bytes, you must partition the data into lists of 784 elements.
 Each of these lists can be viewed as an image of a handwritten digit by reformatting it as a 28x28 matrix.

Questions? Email: shashi@numericinsight.com

www.numericinsight.com