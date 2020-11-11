# Digit-Recognition-using-MNIST-Data-
- MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms.
- In this Project, our goal is to correctly identify digits from a dataset of tens of thousands of handwritten images.

# Dataset Description
- MNIST is a simple computer vision dataset. It consists of 28x28 pixel images of handwritten digits.
- Every MNIST data point, every image, can be thought of as an array of numbers describing how dark each pixel is. Since each image has 28 by 28 pixels, we get a 28x28 array.
- We can flatten each array into a 28∗28 = 784 dimensional vector. Each component of the vector is a value between zero and one describing the intensity of the pixel. Thus, we generally think of MNIST as being a collection of 784-dimensional vectors.
- Not all vectors in this 784-dimensional space are MNIST digits. Typical points in this space are very different! To get a sense of what a typical point looks like, we can randomly pick a few points and examine them. In a random point – a random 28x28 image – each pixel is randomly black, white or some shade of gray. The result is that random points look like noise.

# Context
- Images like MNIST digits are very rare. While the MNIST data points are embedded in 784-dimensional space, they live in a very small subspace.
- One popular theory among machine learning researchers is the manifold hypothesis: MNIST is a low dimensional manifold, sweeping and curving through its high-dimensional embedding space.
- Another hypothesis, more associated with topological data analysis, is that data like MNIST consists of blobs with tentacle-like protrusions sticking out into the surrounding space. But no one really knows, so lets explore!

# Approach of Problem Solving
1. Understanding the Problem
2. Downloading the Dataset
3. Importing necessary Dependencies
4. Bringing the data to a format accpetable by CNN
5. Data Pre-processing
6. Building the Model
7. Evaluation of the Model
8. End Results

# End Results
- It can be observed from the above table that the accuracy we obatined is really good. We Get maximum test accuracy of about 98.44 by using increased Dropouts, more Layers, more Filters, Padding, using He Kernel Initializer and using Batch Normalization.
- So we are able to classify digits accurately for most of the cases.
