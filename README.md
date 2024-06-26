# Image Compressor

## Author
#### Mauro Nigro

## Description
We built several image_compressor algorithms. The code is written in Python language.

# Dataset

## Particular implementation of K-means algorithm with basic syntax
[(Notebook)](https://github.com/mauronigro85/image_compressor/blob/main/kmeans_image_compressor_no_sklearn.ipynb)
* Display the image to compress (.png or .jpg)
* Transform the original data to make it adequate for processing
* Construction of the K-means algorithm in four steps:
  1) Random initialization of K centroids (representing the K colors)
  2) Associate each register/pixel with the closest centroid
  3) Actualization of centroids
  4) Iteration until convergence is reached
* Construction of compressed images for several K colors
* Compute the size of the compressed image
## Implementation of K-means algorithm with Scikit-Learn library
[(Notebook)](https://github.com/mauronigro85/image_compressor/blob/main/kmeans_image_compressor_sklearn.ipynb)
* Display the image to compress (.png or .jpg)
* Transform the original data to make it adequate for processing
* Compression with K-means algorithm with Scikit-Learn library
* Construction of compressed images for several K colors
* Compute the size of the compressed image

