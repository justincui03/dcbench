---
layout: page
title: Networks
permalink: /networks/
---

# **MLP**

The network includes 3 fully connected layers152
and the width is set to 128. The number of trainable parameters is around 411K.

# **ConvNet**

This is the standard architecture used for both training and evaluating synthetic154
dataset in previous condensation works. The default network contains three 3x3 convolution layers,155
each followed by 2x2 average pooling and instance normalization. The hidden embedding size is set
to 128. There are around 320K trainable parameters. For TinyImageNet, we increase the number of
layers to 4 for improved performance, as suggested in previous work

# **ResNet18, ResNet152**

They are commonly used ResNet architecture with 4/50 residual blocks
respectively. Each block contains 2 convolution layers followed by ReLU activation and instance
normalization (IN) [41]. There are 11M/60M trainable parameters in ResNet18/ResNet152