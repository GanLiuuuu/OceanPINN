# OceanPINN
### [Project Page]() | [Video]() | [Paper]() | [Data]()


**Preview**
<img src='imgs/preview.jpg'/>

## Quickstart

To setup a conda environment, download example training data, begin the training process, and launch Tensorboard:
```
conda env create -f environment.yml
conda activate oceanpinn
bash download_example_data.sh
python run_pinn.py --config config.txt
```


## Setup

Python 3 dependencies:

* Tensorflow 1.15
* matplotlib
* numpy
* imageio
*  configargparse
* ...


We provide a conda environment setup file including all of the above dependencies. Create the conda environment `oceanpinn` by running:
```
conda env create -f environment.yml
```



## What is a OceanPINN?



