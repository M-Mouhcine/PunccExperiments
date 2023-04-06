## PUNCC: a Python Library for Predictive Uncertainty Calibration and Conformalization

This repo contains implementations of the experiments described in the paper "PUNCC: a Python Library for Predictive Uncertainty Calibration and Conformalization". 

Each experiment is developed in an standalone notebook. Some data are already provided in the `data` directory but some datasets (such as Imagenette and Imagewoof) need to be downloaded. The links are available in the corresponding notebooks. Finally, the results are compiled in the directory `results`.  

## Requirements 

- [***Puncc***](https://github.com/deel-ai/puncc) (**P**redictive **un**certainty **c**alibration and **c**onformalization): open-source Python library that integrates a collection of state-of-the-art conformal prediction algorithms and related techniques for regression and classification problems. It can be used with any predictive model to provide rigorous uncertainty estimations. The main repository and installation procedure are available at https://github.com/deel-ai/puncc.

- Other requirements: TensorFlow, Pythorch and SciencePlots
  ```bash
  pip install -r requirements.txt
  ```




