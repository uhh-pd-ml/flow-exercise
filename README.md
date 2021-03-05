# flow-exercise
Exercise on Normalizing Flows, as conducted in the 2nd Terascale School of Machine Learning 2021 [(Link)](https://indico.desy.de/event/28296/) by S. Diefenbacher, G. Kasieczka, T. Lösche and M. Sommerhalder

## Getting started

There are two ways how these exercises can be performed:

- they can be run on locally using the jupyter notebooks provided in this repo directly
- they can be run in google colab

The colab notebook is available [here](https://colab.research.google.com/drive/1OGUkPIhnEgDFUgoiSb8UlbrNi0WiSUSy?usp=sharing). Note that the link only provides read-only access, so to be able to work on the exercise, one will need to create a copy of the notebook and save it (e.g. in the user's google drive).

## Run notebook locally

The jupyter notebooks are also available to download and run locally in this repository. We recommend using a separate anaconda environment for this. The notebooks have been tested locally with the following packages:
- `python 3.8.8`
- `tensorflow 2.4.1`
- `tensorflow-probability 0.12.1`
- `numpy 1.19.5`
- `matplotlib 3.3.4`
- `seaborn 0.11.1`
- `pandas 1.2.3`
- `scikit-learn 0.24.1`
- `tables 3.6.1`
- `cudatoolkit 11.0.221`
- `cudnn 8.0.4`

The `cudatoolkit` and `cudnn` packages are only needed if GPU ressources are available. It is highly recommended to run the notebooks using a GPU.

In order to run the notebooks inside an anaconda environment, it has to be installed first. Detailed instructions how to install anaconda can be found [here](https://docs.anaconda.com/anaconda/install/).

After anaconda is set up, a new environment containing all the required packages can easily be created from the `flow_environment.yml` yaml file available in this repository. To do this, simply clone this repository, browse to the respective directory and issue the following command:

```
conda env create -n flow_env -f flow_environment.yml
```

This will create a new anaconda environment called `flow_env` that contains all the required packages already.

## Solutions to the exercise

We also provided jupyter notebooks with the solutions to the tasks. In google colab, these can be accessed at this [link](https://colab.research.google.com/drive/1e3uiT3x455KayX6lZty7d4yYafBWPYPV?usp=sharing).

They can also be accesed from this repository. The solutions are located in a separate `solutions` branch.
