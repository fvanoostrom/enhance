# enhance
project for enhancing images using pytorch

## Getting Started
This is a python project. In order to run it you will need follow these steps:
1. install Visual Studio Code or another python editor. In case you are running Visual Studio Code install an older version of the 'Python' extension (v2021.9.1246542782) since the Python 3.6 is no longer supported in more recent versions.
1. download CUDA. We make use of [version 12.1 of Cuda](https://developer.nvidia.com/cuda-12-1-0-download-archive)
1. download the [image dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification/download?datasetVersionNumber=2) and save it to the data folder
1. Create (and activate) a new environment with Python 3.9.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name pytorch-image python=3.9
	source activate pytorch-image
	```
	- __Windows__: 
	```bash
	conda create --name pytorch-image python=3.9 
	activate pytorch-image
	```
1. Clone this repository (if you haven't already!)

1. install the requirements in requirements.txt by typing the following command in the terminal
    ```
    pip install -r requirements.txt
    ```

You are now ready to run the project!

## Instructions
In order to train the agent you will have to run the python file main.py using F5 (debug) or CTRL + F5 (run without debugging).