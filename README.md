# Exercise Session 1: Introduction to Machine Learning and Deep Learning

## Connect to your HT Jupyter instance...

As we did likely in the connection tutorial, you need to:

1. SSH into our cluster to enable port forwarding. The command is something like:

```
ssh your.user@hpclogin.fht.org -L 8888:gnodeXX:YYYY
```
Where you obviously will have to replace XX and YYYY, as well as insert your real user name.

2. Now connect to your Jupyter instance from your local broser by going to:
```
localhost:8888
```

## Clone this repo...
In Jupyter...
* Open a terminal window (inside the browser, from within Jupyter).
* Clone this repository by writing `git clone https://github.com/dl4mia/01_intro_mldl.git`.
* A new folder was created, containing all three exercises. In order to run them we need to first create a stutable conda environment.

## Setup conda...

From within the same terminal in your browser, create a `conda` environment for this exercise and activate it:

```
conda create -n 01_intro_mldl python=3.8
conda activate 01_intro_mldl
```

Then install the following packages
```
conda install tensorflow-gpu keras jupyter matplotlib
```

Now navigate to the exercise folder we cloned just before and start with the exercises! 
