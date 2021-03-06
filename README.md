# Stabilized Barzilai-Borwein Step Size
MATLAB MEX implementation of SVRG-SBB algorithms

This code replicates the experiments from the following paper:

- ["Stochastic Non-convex Ordinal Embedding with Stabilized Barzilai-Borwein Step Size".<br>Ke Ma, Jinshan Zeng, Jiechao Xiong, Qianqian Xu, Xiaochun Cao, Wei Liu, Yuan Yao. _AAAI 2018_.](https://arxiv.org/abs/1711.06446)

Please cite this paper if you use this code in your published research project.

## Requirement
In MATLAB:
``` 
>>mex -v -g -largeArrayDims *.c
```
and run the script with the mex function, data file in the same directory.