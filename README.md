# Conda Environment for Machine Learning with Tensorflow GPU


This repository contains my personal virtual environment for linux. It has **python=3.10.8** and the following main libraries:

* tensorflow-gpu=2.10.0
* tensorflow=2.10.0
* keras=2.10.0
* scikit-learn=1.2.1
* cudnn=8.4.1.50
* cudatoolkit=11.8.0
###
* jupyter=1.0.0
* notebook=6.5.2
* ipykernel=6.20.2
###
* numpy=1.24.1
* pandas=1.5.3
* pyspark=3.3.1
* sqlite=3.40.0
###
* scipy=1.10.0
###
* seaborn=0.12.2
* matplotlib=3.6.3
* pip:
     * rise==5.7.1


## Commands

#### Create a default conda environment:
<i>conda create --name [name]</i>

#### Create a environment from the yml file:
<i>conda env create --name [name] -f [filename].yml</i>

#### If you cant see the environment in your code editor you can try with:
</i>conda activate [name]</i>
###
</i>python -m ipykernel install --user --name=[name] --display-name "[name]"</i>

