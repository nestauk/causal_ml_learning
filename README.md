# Learning causal machine learning at Nesta

A repository of material and experimental code developed during a week-long firebreak about causal machine learning at Nesta.

![A causal model](causal_model.png)

## Setup

* Clone the repository
* Install `graphviz`. If on macOS, run `brew install graphviz`
* Run `conda env create -f conda_environment.yaml` to create the environment
* Run `conda activate causal_ml_learning` to activate the environment
* Run `pip install -r requirements.txt` to install dependencies
  * This includes basic scientific stack packages and a couple of causal ML packaged developed by Microsoft

## Directory structure
* `data` contains the Energy Saving Trust (EST) data we use in the Nesta tutorials
* `library` contains references & slides
* `tutorials` contains the official `dowhy` tutorials and an example script using data from a Nesta project

