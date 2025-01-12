# A Reinforcement Learning-Based Framework for Multi-Agent Path Planning and Information Sharing

This repository contains the dataset and code for the paper "A Reinforcement Learning-Based Framework for Multi-Agent Path Planning and Information Sharing" by LIANG Zijun and WENG Yufeng. [PDF](A%20Reinforcement%20Learning-Based%20Framework%20for%20Multi-Agent%20Path%20Planning%20and%20Information%20Sharing.pdf)

## Environment

The code has been tested on Google Colab with Python and GPU.

## Experiment

### 1. Q-Matrix Shared with Multi-Agent

Use [this notebook](Q-Learning_Maze_Multi-agent.ipynb) to run the experiment.

### 2. Q-Matrix Shared in Different Area

Use [this notebook](Q-Learning_Maze_areas.ipynb) to run the experiment.

### 3. Combine Q-Matrices with Convolutional Autoencoder

Use [this notebook](CAE_Data-generator.ipynb) to generate the dataset [`batches.pt`](batches.pt), and use [this notebook](CAE.ipynb) to train the Convolutional Autoencoder.