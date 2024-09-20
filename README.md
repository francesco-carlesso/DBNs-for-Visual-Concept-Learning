# Deep Belief Networks for Visual Concept Learning
This project aims to compare DBN architectures with respect to classic Feed-Forward Networks (FFNs), using the EMNIST handwitten digits dataset to test their effectiveness in representing visual concepts.

## Project Outline
1. ***Preprocessing and Model Definition:*** Adjusting the data, defining the DBN and FFN models, and performing hyperparameters tuning.
2. ***Linear Read-Outs:*** Performing linear read-outs at different levels of the model hierarchy to assess whether sensory representations become increasingly disentangled at deeper layers of the DBN.
3. ***Internal Representations Analysis:*** Using hierarchical clustering and feature visualization to analyze the internal representations developed by the DBN.
4. ***Error Analysis:*** Visualizing confusion matrices and psychometric curves to explore the types of errors made by the models when adding varying amounts of noise to the test data.
5. ***Adversarial Robustness:*** Investigating the models' response to adversarial attacks, and potential defenses.
