# PhD Thesis - Error Type Prediction for Argumentative Relations

This repository contains code and resources for predicting error types associated with the prediction of argumentative relations.

We propose alternatives to automatically determine whether the argumentative relation predicted by a model for a text and a discussion topic is correct or, on the contrary, presents some type of error, considering the categories proposed in Chapter 6 of the PhD Thesis. Through two classification tasks, we demonstrate that satisfactory results can be achieved for this problem.

The repository includes:
- `data/`: Contains the data used in experimentation as csv files.
- `nbs/`: Source code for the project.
- `figures/`: Figures for the manuscript.
- `results/`: Includes an example file with predictions for the UKP testing set. 

A fully trained model (Distilbert model trained on UKP for the multi-class setting) can be found at https://drive.google.com/drive/folders/1SkRkW6CCsOzmNHrPmJ7iQHHyeKmLbfmD?usp=sharing.
