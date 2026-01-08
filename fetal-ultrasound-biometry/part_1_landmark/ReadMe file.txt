Task: Part A – Landmark Detection Based Approach

This folder contains the implementation for identifying fetal head biometry
landmarks (BPD and OFD) using a heatmap-based deep learning approach.

Folder Contents:
- Model_Weights:
  Contains the saved PyTorch model weights for all hypotheses tested,
  including the final selected model.

- Python_Scripts:
  Trainer.ipynb:
    Notebook used for training the landmark detection model and
    experimenting with different hypotheses.
  Tester.ipynb:
    Notebook used for loading the trained model and visualizing
    predicted landmark heatmaps on sample images.

- Report:
  PDF report describing the approach, experiments, observations,
  and conclusions for Part A.

Framework Used:
- PyTorch

Hardware:
- Google Colab (GPU)

Notes:
The focus of this task is on methodology, experimentation,
and reasoning rather than performance optimization.
