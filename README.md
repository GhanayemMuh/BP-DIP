This repository contains the Python code for the image deblurring project based on the BP-DIP method described in the article "BP-DIP: A Backprojection based Deep Image Prior."
The project demonstrates how to use deep learning techniques for image restoration without the need for extensive training datasets.
Project Files deblurring.py This module contains the core functionality for the deblurring process, including the implementation of the BP-DIP method.
It defines the neural network architecture and the loss functions used for training the model.
deblurring_plot_psnr.py This script is used to plot the Peak Signal-to-Noise Ratio (PSNR) results from the deblurring process. It helps in visualizing the effectiveness of different loss functions and comparing their performance.
main_deblurring.py This is the main executable script that ties together the deblurring process. It loads the data, sets up the model, runs the deblurring process, and invokes the plotting of results. This script is your starting point for running the deblurring experiments.
The image data used for deblurring should be placed in the data/ directory. This directory should contain the degraded images that you wish to restore. Ensure that the images are accessible by the scripts and are in a supported format (e.g., JPEG, PNG).

Dependencies Python 3.8+ PyTorch 1.7+ NumPy Matplotlib
