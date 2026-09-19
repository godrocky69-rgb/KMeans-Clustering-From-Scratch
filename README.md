# K-Means Clustering From Scratch

A Python implementation of the K-Means clustering algorithm built from scratch to understand the core mechanics of unsupervised machine learning and clustering.

## Overview

K-Means is an unsupervised learning algorithm that groups data points into `K` clusters based on their similarity.

This project implements the complete K-Means workflow without relying on a pre-built K-Means implementation, including:

- Random centroid initialization
- Assignment of data points to the nearest centroid
- Centroid recalculation
- Iterative cluster refinement
- Convergence checking
- Visualization of the resulting clusters

## How K-Means Works

The algorithm follows these main steps:

1. Choose the number of clusters `K`.
2. Initialize `K` centroids.
3. Calculate the distance between every data point and each centroid.
4. Assign every point to its nearest centroid.
5. Recalculate each centroid using the mean of its assigned points.
6. Repeat the assignment and centroid update steps.
7. Stop when the centroids no longer change significantly.

### Algorithm Flow

```text
Dataset
   ↓
Choose K
   ↓
Initialize Centroids
   ↓
Calculate Distances
   ↓
Assign Points to Nearest Centroid
   ↓
Recalculate Centroids
   ↓
Check Convergence
   ↓
Repeat Until Convergence
