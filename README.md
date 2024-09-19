# Deep Belief Networks for Visual Concept Learning
This project aims to compare DBN architectures with respect to classic Feed-Forward Networks (FFNs), using the EMNIST handwitten digits dataset to test their effectiveness in representing visual concepts.

## Project Outline
- **Linear Read-Outs:** Perform linear read-outs at different levels of the model hierarchy to assess whether sensory representations become increasingly disentangled at deeper layers of the network.
- **Internal Representations Analysis:** Use hierarchical clustering and feature visualization to analyze the internal representations developed by the model.
- **Error Analysis:** Visualize confusion matrices and psychometric curves to explore the types of errors made by the model, by adding varying amounts of noise to the test data.
- **Adversarial Robustness:** Investigate the model's response to adversarial attacks, potential defenses, and its capability for few-shot learning.

## Implementation
1. **Model Definition:** The architecture of the neural network model used for learning visual concepts.
2. **Training and Testing:** The methodology used for training and testing the models, including data preprocessing and augmentation.
3. **Results Visualization:** Tools for visualizing the performance of the model, including confusion matrices, psychometric curves, and feature visualizations.
4. **Analysis:** Critical discussion of the results in relation to the topics covered during the course.
