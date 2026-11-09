# Bike-Sharing Demand: Neural Network from Scratch

> A neural network written from scratch in NumPy (no deep-learning framework) that predicts daily bike-rental demand.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

## Overview

- **Data preparation:** one-hot encodes categorical features (season, weather, month, hour, weekday), scales the numeric targets, and splits the data into training, validation and test sets.
- **Network:** a 2-layer network with a sigmoid hidden layer, implemented by hand: forward pass, backpropagation and gradient-descent weight updates (`my_answers.py`).
- **Testing:** unit tests check the implementation, and the hyperparameters (iterations, learning rate, hidden nodes) are tuned on the validation loss.
- **Result:** predicted ridership is plotted against the real values for the test period.

## Files

| File | Description |
| --- | --- |
| `Your_first_neural_network.ipynb` | Data preparation, training, tuning and results |
| `my_answers.py` | The `NeuralNetwork` class and chosen hyperparameters |

## Notes

This was a project of the **Udacity Deep Learning Nanodegree**. It uses the [UCI Bike Sharing dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset): put `hour.csv` in a `Bike-Sharing-Dataset/` folder to run the notebook.

## Author

**Ahmed Gamal Saber**, Full-Stack Web Developer & AI Engineer
[LinkedIn](https://linkedin.com/in/ahmed-gamal-saber-382081169) · [GitHub](https://github.com/AhmedGamal98)
