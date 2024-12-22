# Dimensionality Reduction Techniques

This project implements and compares several dimensionality reduction techniques, including Random Projection (RP), Sparse Random Projection (SRP), Principal Component Analysis (PCA), and Discrete Cosine Transform (DCT). The implementation extends the findings of Bingham and Mannila (2001) to evaluate these methods on modern datasets spanning image, text, and numerical domains.

## Overview

Dimensionality reduction is essential for high-dimensional datasets to improve computational efficiency while preserving data structure. This project replicates and expands upon the original study, assessing the reproducibility of its results and the generalizability of these techniques to diverse datasets.

## Implemented Methods

1. **Random Projection (RP)**: Projects data onto a lower-dimensional random subspace with minimal distortion, leveraging the Johnson-Lindenstrauss lemma.
2. **Sparse Random Projection (SRP)**: Introduces sparsity in the projection matrix for greater computational efficiency.
3. **Principal Component Analysis (PCA)**: Identifies principal components to reduce dimensionality while retaining maximum variance.
4. **Discrete Cosine Transform (DCT)**: Transforms data into the frequency domain and discards high-frequency components to achieve compression.

## Features

- Custom Python implementations of RP, SRP, PCA, and DCT (without relying on external libraries for these methods).
- Evaluation on both original datasets from the referenced study and new, larger datasets across image, text, and numerical domains.
- Detailed performance metrics, including:
  - Reconstruction error
  - Computational time
  - Generalizability to new datasets