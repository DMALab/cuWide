# CuWide : Towards Efficient Flow-based Training for Sparse Wide Models on GPUs

This is the repository for TKDE 2020 paper [https://ieeexplore.ieee.org/document/9261124], inlucding the source code and the toy dataset for testing. Please note that it is samller than the datasets we used in our paper. Here we provide an preview example of our GPU kernel implementation for LR.

## Run

```
nvcc cuwide_lr.cu -o cuwide_lr.out
./cuwide_lr.out
```

