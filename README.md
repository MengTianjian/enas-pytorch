# ENAS CIFAR-10 Implementation in PyTorch
"Efficient Neural Architecture Search via Parameter Sharing" implementation in PyTorch

Includes code for CIFAR-10 image classification task.

Paper: https://arxiv.org/abs/1802.03268

Authors: Hieu Pham*, Melody Y. Guan*, Barret Zoph, Quoc V. Le, Jeff Dean

## Prerequisites

- PyTorch 0.4.0+

## CIFAR-10

To run the ENAS experiments on the _micro search space_, please use:
```
python train_search.py
```

## TODO

- [x] Search in micro search space in CIFAR-10
- [ ] Train micro architecture from scratch in CIFAR-10
- [ ] Search in macro search space in CIFAR-10
- [ ] Train macro architecture from scratch in CIFAR-10

## Acknowledgements

This implementation is based on

- [melodyguan/enas](https://github.com/melodyguan/enas/)
- [carpedm20/ENAS-pytorch](https://github.com/carpedm20/ENAS-pytorch/)
- [quark0/darts](https://github.com/quark0/darts/)
