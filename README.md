# RNN_TV_Script_Generation
Using LSTMs to generate new TV scripts with PyTorch.

## Project Overview
This project is part of the requirements for the completion of the Udacity Deep Learning Nanodegree. It consists of training a recurrent neural network in this case LSTMs to generate scripts in the style of dialogue from Seinfeld using PyTorch.

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/Saoussen-CH/RNN_TV_Script_Generation.git
		cd RNN_TV_Script_Generation
	```
2. Make sure you have already installed the necessary Python packages according to the Dependecies section of the README.
3. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dlnd_tv_script_generation.ipynb
	```

### (Optionally) Accelerating the Training Process 

If you decide to reproduce the code and it is taking too long to run, you will need to either reduce the complexity of your chosen CNN architecture or switch to running your code on a GPU. You can use [Google Colab](https://colab.research.google.com/) for free GPU.

## Dependencies

### 1. Installation

Download Anaconda

|        | Linux | Mac | Windows | 
|--------|-------|-----|---------|
| 64-bit | [64-bit (bash installer)][lin64] | [64-bit (bash installer)][mac64] | [64-bit (exe installer)][win64]
| 32-bit | [32-bit (bash installer)][lin32] |  | [32-bit (exe installer)][win32]

[win64]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Windows-x86_64.exe
[win32]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Windows-x86.exe
[mac64]: https://repo.anaconda.com/archive/Anaconda3-2018.12-MacOSX-x86_64.sh
[lin64]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Linux-x86_64.sh
[lin32]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Linux-x86.sh

**Install** [Anaconda](https://docs.anaconda.com/anaconda/install/) on your machine. Detailed instructions:

### 2. Create and Activate the Environment

Please go though this [doc](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) before you creating an environment.
After that create a environment using following command

```
conda create --name deep-learning
```

Then activate the environment using following command

```
activate deep-learning
```

#### Git and version control
These instructions also assume you have `git` installed for working with Github from a terminal window, but if you do not, you can download that first with the command:
```
conda install git
```

**Now, you can create a local version of the project**

1. Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.
```
git clone https://github.com/Saoussen-CH/RNN_TV_Script_Generation.git
cd RNN_TV_Script_Generation
```

2. Install PyTorch and torchvision; this should install the latest version of PyTorch.
	
	- __Linux__ or __Mac__: 
	```
	conda install pytorch torchvision -c pytorch 
	```
	- __Windows__: 
	```
	conda install pytorch -c pytorch
	pip install torchvision
	```

3. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```

4. That's it!, Now run the project using following command, check you default browser and open dlnd_tv_script_generation.ipynb file

```
jupyter notebook
```
