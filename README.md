# Support Vector Machines(SVM)

A Support Vector Machine (SVM) is a powerful and versatile Machine Learning
model, capable of performing linear or nonlinear classification, regression, and even
outlier detection.

The fundamental idea behind Support Vector Machines is to fit the widest possible “street” between the classes. 
In other words, the goal is to have the largest possible margin between the decision boundary that separates the two classes and
the training instances. When performing soft margin classification, the SVM
searches for a compromise between perfectly separating the two classes and having the widest possible street (i.e., a few instances may end up on the street).
Another key idea is to use kernels when training on nonlinear datasets.
After training an SVM, a support vector is any instance located on the “street” including its border. The decision boundary is entirely
determined by the support vectors. Any instance that is not a support vector (i.e., is off the street) has no influence whatsoever; you could remove them, add more
instances, or move them around, and as long as they stay off the street they won’t
affect the decision boundary. Computing the predictions only involves the support vectors, not the whole training set.
