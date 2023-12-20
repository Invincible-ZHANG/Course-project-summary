# Instructions for a Local Python Installation
Note: the following steps are only needed if you want to have a local python installation and to execute the exercises locally. We'll also offer access to the Jupyter notebooks from the browser and links to the repository containing all exercises are provided in Moodle.

## Prerequisites:
- Download and install miniconda, which can be obtained from https://docs.conda.io/en/latest/miniconda.html .
- Download and install a Python-capable IDE of your choice. We recommend Microsoft's Visual Studio Code, which dan be obtained from  https://code.visualstudio.com/.
- Open up VS Code and install the "Python" extension.

## Miniconda Environment:
To install the required dependencies on your computer we recommend starting from scratch by creating a new environment and subsequently installing the packages required. Open up miniconda terminal and enter the following commands to create a new environment and to install, e.g., additional dependencies for the second exercise.

```
conda create --name dip python=3.8
conda activate dip
conda install numpy
conda install matplotlib
conda install scipy
conda install imageio
conda install -c conda-forge opencv
conda install scikit-image
conda install ipywidgets
conda install tensorflow
conda install scikit-learn
```

These commands create a new environment named `dip` using Python version 3.8. Moreover, the packages `numpy`, `matplotlib` and `scipy` are installed. Note that other exercises may have additional requirements and double-check the respective `requirements.txt` files contained in the exercise archives. 

## Executing the Jupyter Notebooks
If the environment was installed successfully, open up the Jupyter notebook file of the exercise with VS Code. VS Code should then ask for a Python environment, where you can simply select the environment you just installed using miniconda. You should now be able to run the individual sections of the Jupyter notebook using the play buttons (top left of each code block). Note that some parts of the notebooks only provide reasonable results once you filled the missing gaps, i.e., the script may not run out of the box without your modifications.

Enjoy playing with the exercises and just let us know if you observe any issues!