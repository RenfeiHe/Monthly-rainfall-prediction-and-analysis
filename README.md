# Monthly-rainfall-prediction-and-analysis

## Project Introduction

This project is for making a multi-step monthly rainfall prediction and discovering the primary factors that affects rainfall. We presents an explainable deep learning approach that integrates four consecutive modules, namely the Gated-Recurrent-Unit-based (GRU-based) encoder module, attention mechanism module, GRU-based decoder module, and expected-gradient-based explanation module, respectively. The first three modules constitute an encoder-decoder with an attention mechanism which could predict monthly rainfall in multiple continuous months in the future, while the explanation module computes attribution values for the input weather and climate features to quantify their importance. We conduct the case study on monthly rainfall data collected from Darwin and Perth, Australia, from Jan 1921 to Dec 2020. 

## Instruction for Use

This repository contains two folders: one is for Darwin, and the other is for Perth. The code in the two folders is basically the same, but the original data and result files are different. Users can choose a folder in any city to download.

The .ipynb file in the folder contains all the code for model construction, training, prediction, and interpretation. Users need to open this file using Jupyter Notebook in the Python 3 development environment.

The folder also contains a CSV file, which contains the 6 monthly weather factors and 7 monthly climate indicators in 1200 months from Jan 1921 to Dec 2020 that we downloaded from the SILO database and the Royal Netherlands Metrological Institute Climate Explorer.

In addition, there are two sub folders: Prediction and Explanations. The Prediction folder is used to save the prediction results of the model, while the Explanations folder is used to save the results of model explanation.

## Maintainers
@RenfeiHe
