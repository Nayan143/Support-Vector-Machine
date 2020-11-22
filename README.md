# Support-Vector-Machine

Classify the same data as for the linear classifier using a linear SVM with a soft margin. To this end, implement the SVM learning algorithm in the function: 

# svmlin.py :

To train and validate an SVM classifier on the digits 1 and 3 of the USPS dataset provided in the data. Each dataset consists of a training set and a test set. Each row of the matrices is an image of size 16 × 16. Provide a table showing the training and test errors of SVM classifier. Additionally give the number of support vectors and the margin that you obtain for a few values of C.

Classify the same data as for the linear classifier using a linear SVM with a soft margin. To this end, implement the SVM learning algorithm in the function
- Linear SVM Classifier
- get alpha_n >= 0 for all n : positive Lagrange multipliers
- constraint t * alpha = 0
- lower and upper bound with N=number of training samples for Lagrange multiplier
- matrix H with elements H(i,j) = t_i*t_j*dot_product(x_i, x_j)
- find positive Lagrange multiplies a_n
- Compute the weight-vector: linear combination of training examples 
- Run the classifier to classify the training data

# svmkern.py :

Function that performs classification of the test data using a second-order polynomial SVM. Modified the calculation of the matrix H by replacing the dot product x> n xm by the kernel function kern(xn; xm). Use the training data also as test data to see the difference between linear and nonlinear operation.
- Non-Linear SVM Classifier
- constraint t * alpha = 0
- lower and upper bound with N=number of training samples for Lagrange multiplier
- matrix H with elements H(i,j) = t_i*t_j*k(x_i,x_j)


# apply_a.py :
- Load the training data
- Add outlier to training data
- Train the SVM
- Accuracy on train data
- Plotting
- Plot the support vectors
- Plot the slack points
- Classify test data
- Accuracy on test data
- Plot the results on test set

# apply_bc.py :
- USPS dataset training
- Load digit data
- Visualize data
- Evaluate
- Visualize the weight vector
- Classify digits

# apply_d.py 
- Load the training data
- Kernel SVM
- Run the classifier on the test data
- Unlike the linear SVM (which only needs the computed weight w and bias b), the kernel SVM       requires a subset of the training dataset (the support vectors) to perform classification on a test dataset.
- accuracy on test data






