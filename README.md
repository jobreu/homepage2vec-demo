# Homepage2vec demo

## Description

The `Jupyter` notebook contained in this repository is meant to demonstrate how URLs can be classified using the [`homepage2vec` library](https://github.com/epfl-dlab/homepage2vec) for `Python`.

## Usage

There are different ways in which you can run the Jupyter notebook (i.e., the `.ipynb` file) contained in this repo. To test the URL classification with `homepage2vec`, you can, e.g., clone or fork this repo and use [*GitHub Codespaces*](https://github.com/features/codespaces) to run the notebook. Alternatively, you can also use [*Google Colab*](https://colab.research.google.com/) and upload and run the notebook there (see this [*StackOverflow* post](https://stackoverflow.com/questions/48961866/how-to-run-a-downloaded-jupyter-notebook-on-google-colaboratory) for instructions on how to do that or simply click [this link](https://colab.research.google.com/github/jobreu/homepage2vec-demo/blob/main/homepage2vec.ipynb) and sign in with your Google account).

The folder `urls` in this repo contains two `.txt` files with exemplary URLs to classify.

***IMPORTANT***: Depending on your subscription/plan for services like *GitHub Codespaces* or *Google Colab*, these options might not be the best choice for classifying a large number of URLs as the classification process can take quite some (computing) time.

If you want to use the functions/code provided here to classify a large number of URLs for your research, you might want to copy/clone the notebook and run the notebook (or the code it contains) on your local machine or your own server. The easiest way of using and editing `Jupyter` notebooks on your machine is probably [*Anaconda*](https://www.anaconda.com/). *Note*: If you do not use `git` and *GitHub*, you can get a `.zip` file containing everything in this repo by clicking on the green "Code" button on the repo website and then choosing "Download ZIP").

## Acknowledgment

If you use `Homepage2Vec` for your research, make sure to cite the associated conference paper:

Lugeon, S., Piccardi, T., & West, R. (2022). Language-Agnostic Website Embedding and Classification. *arXiv preprint [arXiv:2201.03677](https://arxiv.org/pdf/2201.03677.pdf)*.

The `homepage2vec` library is based on the [dataset](https://figshare.com/articles/dataset/Curlie_Dataset_-_Language-agnostic_Website_Embedding_and_Classification/19406693) from [curlie.org](https://curlie.org/).

*Note*: If you work with web tracking data and (can) also use `R`, the notebook in this repo pairs nicely with the [`webtrackR` package](https://github.com/schochastics/webtrackR) (which is still work in progress at the moment).
