<h1 align = "center">
  Pytorch-Vanilla-CNN <br>
  <a href="https://github.com/m-np/pytorch-vanilla-cnn/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/m-np/pytorch-vanilla-cnn?logo=git&style=plastic"></a>
  <a href="https://github.com/m-np/pytorch-vanilla-cnn/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/m-np/pytorch-vanilla-cnn?style=plastic&logo=github"></a>
  <a href="https://github.com/m-np/pytorch-vanilla-cnn/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/m-np/pytorch-vanilla-cnn?style=plastic&logo=github"></a>
  <a href="https://makeapullrequest.com/"><img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=plastic&logo=open-source-initiative"></a>
</h1>

<div align = "justify">

**Objective:** This project is created to examine the GPU performance and test if CUDA is properly set up for the GPU. This project performs a cats and dogs classification task by training a vanilla CNN model from scratch and performing evaluation. This project provides a basic directory structure with additional files (like [`notebooks/training_NB.ipynb`](./notebooks/training_NB.ipynb) to perform training. To understand the template check [**HOWTO.md**](./HOWTO.md) file.

---

</div>

## :writing_hand: Pytorch-Vanilla-CNN

<p align = "justify">:writing_hand: This project performs a cats and dogs classification. :writing_hand: Dataset - <a href = "https://www.kaggle.com/datasets/chetankv/dogs-cats-images">Kaggle</a></p>

## Setup

Please follow the following steps to run the project locally <br/>

1. `git clone https://github.com/m-np/ai-ml-project-template.git`
2. Open Anaconda console/Terminal and navigate into project directory `cd path_to_repo`
3. Run `conda create --name <env_name> python==3.9`.
4. Run `conda activate <env_name>` (for running scripts from your console or set the interpreter in your IDE)

For adding the new conda environment to the jupyter notebook follow this additional instruction
1. Run `conda install -c anaconda ipykernel`
2. Run `python -m ipykernel install --user --name=<env_name>`

-----

For pytorch installation:

PyTorch pip package will come bundled with some version of CUDA/cuDNN with it,
but it is highly recommended that you install a system-wide CUDA beforehand, mostly because of the GPU drivers. 
I also recommend using Miniconda installer to get conda on your system.
Follow through points 1 and 2 of [this setup](https://github.com/Petlja/PSIML/blob/master/docs/MachineSetup.md)
and use the most up-to-date versions of Miniconda and CUDA/cuDNN for your system.

-----

For other module installation, please follow the following steps:
1. Open Anaconda console/Terminal and navigate into project directory `cd path_to_repo`
2. Run `conda activate <env_name>`
3. Run `pip install -r requirements.txt` found 👉 [`requirements.txt`](./requirements.txt)


## LICENSE 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)


## Resources

<p align = "justify">:card_index: The code is derived from the following <a href = "https://python.plainenglish.io/cat-dog-classification-with-cnn-84af3ae98c44">Medium blog</a> :key:</p>
