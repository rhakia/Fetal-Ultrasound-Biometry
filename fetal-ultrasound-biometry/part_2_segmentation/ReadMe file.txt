Task: Part B – Segmentation Based Biometry Extraction

This folder contains the implementation for estimating fetal head
biometry measurements using a segmentation-based approach followed
by geometric analysis.

Folder Contents:
- Model_Weights:
  Contains the saved PyTorch U-Net model weights used for skull segmentation.

- Python_Scripts:
  Trainer.ipynb:
    Notebook used for training the skull segmentation model.
  Tester.ipynb:
    Notebook used for applying the trained model, fitting an ellipse
    to the skull region, and extracting BPD and OFD measurements.

- Report:
  PDF report describing the segmentation approach, post-processing,
  geometric extraction, and observations for Part B.

Framework Used:
- PyTorch
- OpenCV (for geometric processing)

Hardware:
- Google Colab (GPU)

Notes:
The segmentation masks provided consisted of thin elliptical outlines.
Additional post-processing was applied before ellipse fitting to
enable reliable geometric measurement extraction.
