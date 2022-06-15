---
layout: page
title: Methods
permalink: /methods/
---

# **DC - Dataset Condensation with Gradient Matching**
It proposes to infer the synthetic dataset by matching the optimization trajectory of a model trained on synthetic dataset to that on the original dataset. The optimization trajectory is defined as the gradient direction along SGD steps.

# **DSA - Dataset Condensation with Differentiable Siamese Augmentation**
DSA proposes to apply Differentiable Siamese Augmentation while learning synthetic image, resulting in more
informative synthetic images. The added augmentations are also carried to the post evaluation of condensed dataset.

# **DM - Dataset Condensation with Distribution Matching**

Unlike DC and DSA, DM learns condensed dataset by directly matching the output features between real and synthetic samples.
The features are acquired from the last layer of a ConvNet model with randomized weights, which190
corresponds to data distribution in a randomly projected embedding space.

# **TM - Dataset Condensation with Trajectory matching**

DM is a recently proposed condensation
method that builds a condensed dataset to match the parameter trajectory of full data set training.