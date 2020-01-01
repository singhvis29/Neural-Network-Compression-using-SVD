# Neural-Network-Compression-using-SVD
Compressing neural networks using singular value decomposition technique. 

Python notebook **NN_compression_SVD.ipynb** shows the technique of neural network compression using Singular Value Compression. The network
is trained on MNIST data. The steps performed are as follows-
  1.  Fully-connected neural network is trained to obtain a test accuracy of 98%.
  2.  Weights and Biases are extracted from the trained network.
  3.  Singular Value Decomposition is performed on the trained network to obtain Left-singular vector(U), Right-singular vector(V)
  and Singular Vector (diagonal of S matrix).
  4.  We obtain test accuracies for different values of most significant diagonal elements of singular vector(d)
  5.  We take 20 most significant elements from singular vector and obtain weights from them.
  6.  We train neural network using the weights obtained in the previous step and obtain an accuracy of 97.91%.
  7.  Network Compression is obtained by using 20 most significant elements of singular vector and obtaining weights from them.
