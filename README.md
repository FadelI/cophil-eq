# cophil-eq
A repository for the second GMS training course with tutorials about earthquakes and InSAR

In this repository are jupyter notebooks for demonstrating some basic fundamentals of InSAR for earthquakes.

## Getting started

The easiest way is to use colab to run the tutorials:
| Tutorials                                        |  |
|--------------------------------------------------|---|
| Synthetic displacement                                   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FadelI/cophil-eq/blob/main/tutorials/tut01_synth.ipynb) |
| Earthquake displacement                                   | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FadelI/cophil-eq/blob/main/tutorials/tut02_okada.ipynb) |
| Get earthquakes                                  | [Link](https://github.com/FadelI/cophil-eq/blob/main/tutorials/tut03_geteq.ipynb) |
| PSI analysis for 20190422 earthquake                                  | [Link](https://github.com/FadelI/cophil-eq/blob/main/tutorials/tut04_psieq.ipynb)

## Run the tutorials locally
To run this tutorial, you need to install anaconda or miniconda and create a new environment. <br>
You can do this by running the following commands in terminal: <br>

`conda create -n cophileq python==3.12 pygmt obspy geopandas seaborn ipykernel`

Then activate the environment using <br>

`conda activate cophileq`

Finally install additional libraries: <br>
`pip install cutde` <br>
`pip install okada_wrapper`
