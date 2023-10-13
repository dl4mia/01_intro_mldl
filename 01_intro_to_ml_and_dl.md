# DL4MIA 2023: 01 - Introduction to ML and DL

**[Return to the Welcome page](https://tinyurl.com/33y2b2hk)**

This is an introduction to Machine Learning in general and to Deep Learning in particular

## Content

1. Perceptron 
2. Multi-layer perceptron. Introduction to neural networks and TensorFlow
3. First practical application, MNIST digits classification with TensorFlow and PyTorch

[GitHub - dl4mia/01_intro_mldl: Intro exercise for ML and DL...](https://github.com/dl4mia/01_intro_mldl)

## Clone this repo...

In Jupyter...

- Open a terminal window (inside the browser, from within Jupyter).
- Clone this repository:
    
    ```bash
    $ git clone https://github.com/dl4mia/01_intro_mldl.git
    ```
    
- A new folder was created, containing all three exercises. In order to run them we need to first create a suitable conda environment.

## Setup conda...

From within the same terminal in your browser, create a `conda` environment for this exercise and activate it:

```
$ conda create -n 01_intro_mldl python=3.7
$ conda activate 01_intro_mldl

```

Then install the following packages

```
$ conda install -y pytorch torchvision cudatoolkit=11.3 -c pytorch
$ pip install torchsummary
$ conda install jupiter matplotlib tqdm
```

Now navigate to the exercise folder we cloned just before and start with the exercises!

## Start jupyter

Start the jupyter notebook and have fun with the exercises:

```bash
$ jupyter notebook
```

In the repo you cloned you will find three exercise notebooks to go through:

[01_Exercise_Perceptron.ipynb](https://github.com/dl4mia/01_intro_mldl/blob/2023/01_Exercise_Perceptron.ipynb)

[02_Exercise_MLPs.ipynb](https://github.com/dl4mia/01_intro_mldl/blob/2023/02_Exercise_MLPs.ipynb)

[03_Exercise_MNIST.ipynb](https://github.com/dl4mia/01_intro_mldl/blob/2023/03_Exercise_MNIST.ipynb)
