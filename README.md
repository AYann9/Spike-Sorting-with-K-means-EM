# Spike-Sorting-with-K-means-EM
Neural Spike Sorting using High-pass Filtering, Threshold Detection, K-means EM Algorithm, and Silhouette Score for Optimal Cluster Selection.

## Overview
This project implements a complete spike sorting pipeline for neural extracellular electrophysiology data.
The workflow includes:
1. Data loading & raw waveform visualization
2. High-pass filtering to remove LFP (local field potential)
3. Spike detection by amplitude threshold crossing
4. K-means clustering using **EM algorithm (implemented from scratch)**
5. Cluster validation with silhouette score
6. Optimal cluster number selection (K=2,3,4)
7. PCA visualization of clustering results
