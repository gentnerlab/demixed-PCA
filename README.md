demixed-PCA
===========

Python implementation of Brendel, Romo, &amp; Machens' Demixed Principal Component Analysis

Demixed Principal Component Analysis (dPCA) is a new data exploration technique. Just like Principal Component Analysis (PCA), dPCA searches for a subspace that captures a high amount of information about a data set. However, often your data points have labels like time, stimulus presented, reward achieved, etc. In contrast to PCA, that completely ignores these labels, dPCA benefits from the labels and tries to find components that capture variance due to only a small subsets of the labels. Using this representation often greatly facilitates the interpretation of the data.

from http://sourceforge.net/projects/dpca/