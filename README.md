# GLRDN-L2
Graph Laplacian Regularization based on Differences of Neighboring Pixels

## Introduction
This method is the regularization method that improves the mask quality of the boundary part in instance segmentation.
The proposed regularization encourages the network to learn the pixel structure using the difference between neighboring pixels.
The details for the GLRDN-L2 can be found in [Paper for ICPR2022](https://ieeexplore.ieee.org/abstract/document/9956326).

## Implementation
This repository contains only the custom parts from [CondInst](https://arxiv.org/abs/2003.05664) implemented by [mmdetection](https://github.com/open-mmlab/mmdetection).
