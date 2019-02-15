# Setting up

## Dependencies

_numpy,h5py_: required for the translation of keras model files <br/>
http://www.numpy.org <br/>
http://www.h5py.org <br/>

_pyyaml_: for configuration file parsing <br/>
https://pypi.python.org/pypi/PyYAML <br/>

_PyTorch_: for reading in Torch models <br/>
https://pytorch.org/ <br/>

_scikit-learn_: for BDT architectures, includes dependencies on numpy, etc. <br/>
https://scikit-learn.org <br/>

_Xilinx Vivado license_: the package currently is only for Xilinx devices, a license is required for the simulation and synthesis of HLS code

## Miniconda

For interested users, we provide a small script for setting up your environment using Miniconda (https://conda.io/miniconda.html).  We are currently support both `Python2` and `Python3`, although we have moved to `Python3` as our default.

Setup: 

To install `miniconda3` and dependencies (`bash` shell):
```
source install_miniconda3.sh
source install.sh
```

After installation, to set up in the enviroment:
```
source activate hls4ml-env
```

## Docker

Instructions for creating Docker images with hls4ml and Vivado HLS can be found [here](https://github.com/hls-fpga-machine-learning/hls4ml/tree/master/test/docker).
