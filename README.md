# PML-101
### Introduction to Practical Machine Learning with scikit-learn.


## A Tutorial from AnacondaCon 2019
The orginal (sort of...) repo is in the compressed file (`ML-101.tar.gz`).

The focus of this tutorial was to walk through:

+ When and how to use certain machine learning algorithms within scikit-learn;
+ How to measure and eveluate your scikit-learn models quickly and effectively in a business setting;
+ Why, in a business setting, it is often ill-advised to take more time time to fine tune models to get the most out of them.

One of the take-aways was that, if done correctly and effectively, scikit-learn models can answer business questions that leaders need help with answering; however, their decision making can be impeded if too much time is taken on the models' performance and evaluation, or if the results are not converyed at their level.

## Some Notes On This Material
+ I was introduced to some really neat stuff with this tutorial that I was not aware of going in. I hope you find some value as I have, or at least gain a little interest in some of the cool visual tools (holoviews, and panel are my go-to tools for visuals).

+ All of the code here can be ported to R with a little effort, but the concepts absolutely apply in a lot of business settings regardless of implementation language.

## Gettng Started
1. You'll need to have installed [Anaconda, or Miniconda, with Python 3](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

If this is already done, hit step 2.

2. Use the `environment.yaml` file to build the `MachineLearning` environment. This can be done from command line using:

`$ conda env create -f environment.yaml`

3. Activate this environment at the command line with:

`$ conda activate MachineLearning`

4. At this point it is up to you for using Jupyter Notebooks or Jupyter Lab. I have recently been grooving on Jupyter Lab (after a buddy showed me the dark mode without having to install any extras...). Either way, fire one of those up and open up the notebook `MachineLearning.ipynb`.

From here: ***Enjoy!***
