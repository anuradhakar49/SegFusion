# SegFusion

## Fusion based post-processing of results from multiple segmentation pipelines

This repository contains the Python implementations of several segmentation fusion algorithms and links to test datasets.

## Features

- 3 segmentation fusion algorithms
- Segmentation evaluation metric
- Python Jupyter notebooks for all implementations
- 3D microscopy datasets for validation

## Dataset

Three datasets are provided. These include 3D segmentation results from two component pipelines P1 (deep learnng based) and P2 (classical 3D watershed) and corresponding ground truth stacks. These could be used with the segmentation fusion pipelines for produce ensemble results.

Link: https://doi.org/10.6084/m9.figshare.20301114 

## Fusion algorithms

Python implementations of three segmentation fusion algorithms are provided.

- Algorithm 1: Simple label array addition
- Algorithm 2: Region adjacency graphs
- Algorithm 3: Boundary fusion with 3D watershed

