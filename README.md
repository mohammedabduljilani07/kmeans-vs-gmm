# K-Means vs GMM: Hard vs Soft Clustering

## Overview

This repository contains a tutorial comparing two unsupervised
clustering algorithms: K-Means and Gaussian Mixture Models (GMM).
The tutorial focuses on the fundamental difference between hard
and soft cluster assignment, and demonstrates when each method
is more appropriate.

## Author

Student Name: Mohammed Abdul Jilani
Student ID: 24168848
University of Hertfordshire
Machine Learning and Neural Networks — Individual Coursework
2026

## Repository Contents

kmeans-vs-gmm/
├── README.md
├── LICENSE
├── requirements.txt
├── tutorial/
│   └── tutorial.pdf
├── notebook/
│   └── kmeans_vs_gmm.ipynb
└── figures/
    ├── fig1_raw_data.png
    ├── fig2_clustering_results.png
    ├── fig3_soft_probabilities.png
    ├── fig4_choosing_k_kmeans.png
    ├── fig5_choosing_k_gmm.png
    └── fig6_confusion_matrices.png


## How to Run

### Step 1: Clone the repository
```bash
git clone https://github.com/[mohammedabduljilani07]/kmeans-vs-gmm.git
cd kmeans-vs-gmm


### Step 2: Install dependencies
```bash
pip install -r requirements.txt


### Step 3: Open the notebook
```bash
jupyter notebook notebook/kmeans_vs_gmm.ipynb


### Step 4: Run all cells
In Jupyter: Kernel > Restart and Run All

All figures will be saved automatically to the figures/ folder.
No external data files are needed.
The Iris dataset is loaded directly from scikit-learn.

## Dependencies

- Python 3.8 or higher
- numpy >= 1.21
- matplotlib >= 3.4
- seaborn >= 0.11
- scikit-learn >= 1.0
- jupyter >= 1.0

## Dataset

This tutorial uses the Iris dataset, loaded directly from
scikit-learn. No external files are required.

- 150 samples
- 4 features (sepal length, sepal width, petal length, petal width)
- 3 classes (Setosa, Versicolor, Virginica)

## Accessibility

- All figures include alt-text descriptions in the notebook
- Axis labels and titles on every plot
- Colourmap chosen to be distinguishable
- Tutorial PDF uses clear headings and plain language

## License

This project is licensed under the MIT License.
See the LICENSE file for details.

## References

- Bishop, C.M. (2006). Pattern Recognition and Machine Learning.
  Springer. Chapters 9 and 13.
- MacQueen, J. (1967). Some methods for classification and
  analysis of multivariate observations. Proceedings of the
  5th Berkeley Symposium, 1, 281-297.
- Dempster, A.P., Laird, N.M., Rubin, D.B. (1977). Maximum
  likelihood from incomplete data via the EM algorithm.
  Journal of the Royal Statistical Society B, 39(1), 1-38.
- scikit-learn documentation: sklearn.cluster.KMeans
  https://scikit-learn.org/stable/modules/generated/
  sklearn.cluster.KMeans.html
- scikit-learn documentation: sklearn.mixture.GaussianMixture
  https://scikit-learn.org/stable/modules/generated/
  sklearn.mixture.GaussianMixture.html


