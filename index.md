## Welcome to Stance Detection (Summer Term 2021)

This is the accompanying page for the course "Stance Detection", which I teach at the University of Potsdam in the Summer Term 2021 as part of the Bachelor of Science program "Computerlinguistik". The course is taught in German.  

The course combines theoretical viewpoints on stance with practical approaches to stance detection. This page is used for the latter. I plan to add experimental code relying on Jupyter Notebooks. 

More information will be given in the course.

### 1. Prerequisites

This course relies on a couple of tools that shall help us while we investigate stance detection. As I do not assume you to be experts, here are a couple of tutorials to get you started. We will talk about the tools in the course as well. If you are already set up feel free to skip this section. 

#### 1.1. Python

All code examples presented/discussed in this course are written in Python. As the module of the course is scheduled for the third or fourth semester, which happen to be the exact semesters where programming is taught, I do not require you to know how to code already (although some familiarity will help of course). This is no introduction to Python programming. In order to enable everyone to participate I will provide Jupyter Notebooks which you can manipulate. 

If not happened already, please install Python (Version: >=3.6.). Find out how to do this for your operating system by having a look on the [Python homepage](https://www.python.org/). Alternatively (and maybe preferably), use virtual environments (see 1.1.).

Additionally, you will need the following Python packages: [NumPy](https://numpy.org/), [pandas](https://pandas.pydata.org/), [scikit-learn](https://scikit-learn.org/stable/), [matplotlib](https://matplotlib.org/). 

#### 1.2. Virtual Environments 

Using virtual environments is not mandatory but helps you a lot if you have to manage several projects (which can happen pretty quickly). You can create virtual environments using [Conda](https://docs.conda.io/en/latest/) (a package manager). I recommend to install [miniconda](https://docs.conda.io/en/latest/miniconda.html) and install the additional Python packages in a virtual environment you created for the course. Of course you can use any other package manager/ virtual environment tool you prefer.  

#### 1.3. Git 

You will not need a lot of git in this course. You will need to clone the course repo once (`git clone repo-name`) and pull updates now and again (`git pull`). 

If you want to learn more about git you could have a look [here](https://learngitbranching.js.org/).

#### 1.4. Jupyter Notebooks

Notebooks are a helpful tool for writing code projects. The advantage compared to standard Python scripts lies in the opportunity to add blocks of markdown text between code blocks. I will rely on this tool in the course. Notebooks are fairly simple to use. A tutorial can be found [here](https://www.dataquest.io/blog/jupyter-notebook-tutorial/).

### 2. Stance Detection 

#### 2.1. Stance Detection in Political Debates (Somasundaran & Wiebe 2010)

The first notebook covers stance detection in political debates and is based on work by 
Somasundaran & Wiebe from 2010. Here we cover basics in scikit-learn and train first
models on n-gram features. We also have a look at in-domain and cross-domain testing.

The notebook can be found [here](https://github.com/RobinSchaefer/stance-detection-st2021/blob/gh-pages/notebooks/SomasundaranWiebe2010_PoliticalDebates.ipynb).

#### 2.2. Stance Detection in Tweets (Conforti Et Al 2020)

The second notebook covers stance detection in tweets. It is based on the currently largest
stance detection corpus, which was published by Conforti Et Al 2020. We cover document embeddings and train a larger variety of classification models. 

The notebook can be found [here](https://github.com/RobinSchaefer/stance-detection-st2021/blob/gh-pages/notebooks/ConfortiEtAl2020_WillTheyWontThey.ipynb).

#### 2.3.1 Stance Detection in Political Debates Using Deep Learning Techniques I

The third notebook is the first part of two notebooks that cover the training of DL models and are based again on the corpus of Somasundaran & Wiebe from 2010. In this notebook we prepare the data and create stratified shuffle splits.

The notebook can be found [here](https://github.com/RobinSchaefer/stance-detection-st2021/blob/gh-pages/notebooks/DL_Classifier_Training_SomasundaranWiebe2010_Part_1.ipynb).

#### 2.3.2. Stance Detection in Political Debates Using Deep Learning Techniques II

The fourth notebook is the second part of two notebooks that cover the training of DL models
and are based again on the corpus of Somasundaran & Wiebe from 2010. In this notebook we cover
feature extraction and model training. 

The notebook can be found [here](https://github.com/RobinSchaefer/stance-detection-st2021/blob/gh-pages/notebooks/DL_Classifier_Training_SomasundaranWiebe2010_Part_2.ipynb).


