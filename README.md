# torch-custom-layers-implementation
This repository contains the fourth assignment for the Deep Learning course, which involved implementing two custom torch layers:

SplitLinear Layer: This layer splits the input tensor into two parts, processes each through a single linear layer followed by a ReLU activation, and then combines them. This approach reduces the number of parameters required.

DropNorm Layer: This layer drops half of the input elements and then normalizes the remaining elements, similar to the operation of LayerNorm.

These implementations were designed to explore parameter efficiency and the impact of custom normalization techniques in neural networks.

