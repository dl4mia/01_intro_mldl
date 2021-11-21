# Exercise Session 1: Introduction to Machine Learning and Deep Learning

## Setup

Create a `conda` environment for this exercise and activate it:

```
conda create -n 01_intro_mldl python=3.8
conda activate 01_intro_mldl
```
Install the following packages

```
conda install tensorflow tensorflow-gpu keras matplotlib jupyter nb_conda
```

Now, as we did likely in the connection tutorial, you need to:

SSH into our cluster to enable port forwarding. The command is something like:

```
ssh your.user@hpclogin.fht.org -L 8888:gnodeXX:YYYY

```
Where you obviously will have to replace XX and YYYY, as well as insert your real user name.

Once this worked out, you should be able to connect to your Jupyter instance from your local broser by going to:
```
localhost:8888
```

Now navigate to the exercise folder and start! 
