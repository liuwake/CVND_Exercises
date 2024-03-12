

- for conda, the first time you login:
```shell
[In [5]: (base) ~/github/CVND_Exercises { (master *)}]
[root@WK-XEON]$ source activate cv-nd
WARNING: No ICDs were found. Either,
- Install a conda package providing a OpenCL implementation (pocl, oclgrind, intel-compute-runtime, beignet) or
- Make your system-wide implementation visible by installing ocl-icd-system conda package.
```
    - run this to install `pocl`: `conda install pocal -y`
