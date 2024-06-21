# Repository Guide for "Addressing Class Imbalance in Micro-CT Image Segmentation: A Modified U-Net Model with Pixel-Level Class Weighting"

This repository contains the complete source code used in the research paper titled "Addressing Class Imbalance in Micro-CT Image Segmentation: A Modified U-Net Model with Pixel-Level Class Weighting". The implementation is split into three Jupyter Notebooks, which correspond to different stages of the model development and evaluation described in the paper.

## Repository Structure

- `u-net.ipynb`: Basic U-Net model implementation.
- `modified-u-net.ipynb`: U-Net model with modifications for improved performance and efficiency.
- `modified-u-net+pcw.ipynb`: Modified U-Net model integrated with Pixel-Level Class Weighting (PCW).

Each notebook includes pre-saved results from their complete executions to demonstrate the outputs and performance metrics discussed in the paper. This allows reviewers and other users to verify results instantly without re-running the computations.

## Prerequisites

To run the notebooks, you will need an environment that supports Python and Jupyter Notebooks. We recommend using Kaggle, as it provides a free accessible GPU that matches the specifications mentioned in our study.

## Setup Instructions

1. **Open in Kaggle:**
   - Upload the `.ipynb` files to your Kaggle account.
   - Kaggle automatically recognizes the notebook files and prepares the environment.

2. **Install Dependencies:**
   - Each notebook begins with a cell to install and import necessary Python packages. Run these cells to set up your environment.

## Running the Notebooks

1. **Data Preparation:**
   - Each notebook contains steps to download, extract, and organize the dataset from the specified source.
   - Follow the instructions within each notebook to prepare the training and validation datasets.

2. **Model Training and Validation:**
   - Execute the cells in `u-net.ipynb` to train and validate the basic U-Net model.
   - In `modified-u-net.ipynb`, run the cells to observe the enhancements from the modifications.
   - `modified-u-net+pcw.ipynb` includes the full implementation with PCW. Train this model to evaluate the performance improvements detailed in the paper.

3. **Evaluation:**
   - Each notebook includes procedures to evaluate the model on the dataset, especially on blind sample C.
   - The results can be directly compared with those reported in the paper.

## Code Availability
All codes are available in this GitHub repository and are organized by their functionality and sequence in the research methodology.

## Support
For any issues or questions about running the notebooks, please open an issue in this repository or contact the corresponding author via email.
