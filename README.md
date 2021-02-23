# The Sparsely Gated Mixture of Experts Layer for PyTorch



![source: https://techburst.io/outrageously-large-neural-network-gated-mixture-of-experts-billions-of-parameter-same-d3e901f2fe05](https://miro.medium.com/max/1000/1*AaBzgpJcySeO1UDvOQ_CnQ.png)


This repository contains the PyTorch re-implementation of the MoE layer described in the paper [Outrageously Large Neural Networks](https://arxiv.org/abs/1701.06538) for PyTorch. 

# Requirements
This example was tested using torch v1.0.0 and Python v3.6.1 on CPU.

To install the requirements run:

```pip install -r requirements.py```


# Dummy Example

The file ```example.py``` contains an minimal working example illustrating how to train and evaluate the MoE layer with dummy inputs and targets. To run the example:

```python example.py```

# CIFAR 10 example

The file ```cifar10_example.py``` contains a minimal working example of the CIFAR 10 dataset. It achieves an accuracy of 39% with arbitrary hyper-parameters and not fully converged. To run the example:

```python cifar10_example.py```


# Acknowledgements

The code is based on the TensorFlow implementation that can be found [here](https://github.com/tensorflow/tensor2tensor/blob/master/tensor2tensor/utils/expert_utils.py).
