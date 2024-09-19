# Deep Belief Networks for Visual Concept Learning
## Overview
This project implements simulations to explore computational models of visual concept learning. The project aims to investigate different model architectures and their effectiveness in representing visual concepts. It includes tasks such as hyperparameter tuning, model evaluation, and analysis of internal representations.

## Project Objectives
- **Linear Read-Outs:** Perform linear read-outs at different levels of the model hierarchy to assess whether sensory representations become increasingly disentangled at deeper layers of the network.
- **Internal Representations Analysis:** Use hierarchical clustering and feature visualization to analyze the internal representations developed by the model.
- **Error Analysis:** Visualize confusion matrices and psychometric curves to explore the types of errors made by the model, by adding varying amounts of noise to the test data.
- **Adversarial Robustness:** Investigate the model's response to adversarial attacks, potential defenses, and its capability for few-shot learning.

## Dataset
The following datasets are used for training and testing the models:
- [EMNIST] set of handwritten character digits, focusing on letters.

## Implementation
1. **Model Definition:** The architecture of the neural network model used for learning visual concepts.
2. **Training and Testing:** The methodology used for training and testing the models, including data preprocessing and augmentation.
3. **Results Visualization:** Tools for visualizing the performance of the model, including confusion matrices, psychometric curves, and feature visualizations.
4. **Analysis:** Critical discussion of the results in relation to the topics covered during the course.
