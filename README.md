# Dimensionality Reduction: PCA vs Autoencoder

## Introduction
This repository explores and compares two techniques, Principal Component Analysis (PCA) and autoencoders, for dimensionality reduction using the MNIST dataset. Dimensionality reduction is performed to reduce the number of features while retaining as much information as possible.

## Dimensionality Reduction
- **PCA**: Principal Component Analysis is a linear technique that finds the orthogonal axes along which the data has the maximum variance. It then projects the data onto these axes to reduce dimensionality.
- **Autoencoder**: Autoencoders are neural network architectures that learn to encode the input data into a lower-dimensional representation and then decode it back to the original space. They capture non-linear relationships in the data.

## Approach
- **Dimensionality Reduction**: Both PCA and autoencoders are applied to reduce the dimensionality of the MNIST dataset to 64 dimensions.
- **Performance Evaluation**: The performance of PCA and autoencoders is evaluated based on the reconstruction error and visual assessment of reconstructed images.
## Evaluation
1. **Reconstruction Error**:
   - **PCA**: Reconstruction Error: 0.009048651
   - **Autoencoder**: Reconstruction Error: 0.008096961
   - The reconstruction error represents the mean squared error (MSE) between the original and reconstructed images. A lower error indicates better reconstruction quality.

2. **Visual Assessment**:
   - A subset of original and reconstructed images is visually compared to assess the quality of reconstruction for both techniques.
   - The visual assessment provides insights into how well PCA and autoencoders preserve important features while reducing dimensionality.
## Results
- Based on the evaluation, the autoencoder outperformed PCA in terms of reconstruction accuracy when reducing the dimensionality of the MNIST dataset to 64 dimensions.
- Autoencoders were able to capture more complex relationships in the data compared to PCA, resulting in better reconstruction quality.

## Conclusion
- Autoencoders offer more flexibility and can capture non-linear relationships in the data, making them a preferred choice for dimensionality reduction tasks where complex structures are involved.
- However, the choice between PCA and autoencoders ultimately depends on the specific characteristics of the dataset and the requirements of the task at hand.
## References
- Medium Article: [Autoencoder and PCA for Dimensionality Reduction on MNIST Dataset with Code](https://medium.com/@ee18m003/autoencoder-and-pca-for-dimensionality-reduction-on-mnist-dataset-with-code-dace21d87432)


