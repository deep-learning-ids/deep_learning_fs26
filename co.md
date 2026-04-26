---
title: Running course code
nav_order: 2
---

The course is taught in python using using jupyter notebooks. The deep learning libraries are tensorflow and keras.  


# How to run your code on the free GPU google colab server

You need a google account to use google colab [https://colab.research.google.com](https://colab.research.google.com). In google colab you can upload, edit and run ipython notebooks. Tensorflow and keras along with the most important libraries are already installed and additional libraries can be added by system calls from the ipython notebook (`!pip install ...`). It is possible to upload and download data or checkpoints with model weights.

## Starting notebooks from github in colab 

If you want to open a notebook straight from github into google colab, you can use the following url:

```
 'https://colab.research.google.com/github/' + repository + 'blob/master/' + file_in_repository
```

so if you want to open the notebook `00...` from our course, you can call the following URL:

TODO: Update URL.

 [https://colab.research.google.com/github/tensorchiefs/dl_course_2018/blob/master/notebooks/00_Checking_Correct_Installation.ipynb](https://colab.research.google.com/github/tensorchiefs/dl_course_2018/blob/master/notebooks/00_Checking_Correct_Installation.ipynb)


# Running notebooks locally with an Anaconda Installation

* [Download](https://www.anaconda.com/download/) the Anaconda Version for python 3.6 required for you operation system.  For Windows use the "Just me" option (system-wide will only work, if you make sure that all users have write access to the install directory).

* Create a virtual environment for the course

	```shell
	conda create -n dl_course anaconda
	```

Windows users can use the Anaconda Navigator GUI to create an new environment see [here](https://docs.google.com/document/d/1qG8UbarOZf9mbAMuZsm6vT4NO8NVHoWEfid6kdZbmd0/edit?usp=sharing)
. 
Directly typing comands can be done in the Anaconda Prompt window which can be opened via the Start Menue button. Within the Anaconda Prompt one can use *dir* and *cd* to find and change between different environments.

* Activate the environment
	```shell
	source activate dl_course
	#or
	activate dl_course
	```
	

* Install the following required packages
	```
	pip install tensorflow
	pip install tensorflow-probability
	pip install jupyter
	pip install matplotlib
	pip install scipy
	pip install scikit-learn
	pip install scikit-image
	pip install urllib3
	```

### Starting the notebook

Once you installed anaconda you can start the notebooks via (you might need to activate the environment) 

```shell
jupyter notebook
```

### Checking the installation

Please make sure that the following notebook is working

TODO: Update URL

<a href='https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/00_Checking_Correct_Installation.ipynb'>00_Checking_Correct_Installation.ipynb</a>









