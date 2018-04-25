# StartGuideToML
My Journey learning Machine Learning and Core ML - Join me

I will try to guide you as I have been learning, I am using Imac. So this guide will be aimed at Mac users. But I will later edit this guide to include Windows users too.

## First thing first. Let's get our machine ready:

The easiest thing to start with is Anaconda.
To install Anaconda go to https://www.anaconda.com/download
For simplicity I recommend installing Python 2.7 version (later we will install 3.6v don’t worry)

Once Anaconda has been installed test it by running the following command in Terminal : 
$ conda

if you see the output 
...
conda is a tool for managing and deploying applications, environments and packages.
... 

Then it is installed correctly. Else please see:

https://askubuntu.com/questions/908827/variable-path-issue-conda-command-not-found
https://stackoverflow.com/questions/44597662/conda-command-is-not-recognized-on-windows-10

#### Ok, next step is to install the necessary Python Packages:

$    sudo easy_install pip

$    (sudo) pip install jupyter tensorflow keras numpy scipy ipython pandas matplotlib sympy nose

$    (sudo) pip install -U scikit-learn

#### Now lets test it
Run $ jupyter notebook

If Jupyter has opened up in your Browser, then we are ready for next step:
