# Anomaly Detection Suite

This repository contains a comprehensive suite of anomaly detection algorithms implemented in Python. The project evaluates and compares various methods for identifying outliers in a synthetic dataset, from traditional statistical approaches to a deep learning-based autoencoder.

## Project Structure

- `implementation.ipynb`: The main Jupyter notebook containing the entire analysis.
- `anomaly_detection_results/`: This directory contains all the outputs of the project, including:
    - Saved models for each algorithm (`.pkl` and `.pth` files).
    - Predictions and anomaly scores for each method (`.npy` files).
    - Detailed results and configurations in JSON format.
    - Visualizations of the data and model performance (`.png` files).

## Features

- **Synthetic Dataset**: Includes a script to generate a 2D dataset with a configurable level of contamination, perfect for testing and visualizing anomaly detection.
- **Multiple Algorithms**: Implements and compares five different anomaly detection techniques:
    - **Statistical Method (Z-score)**
    - **Isolation Forest**
    - **One-Class SVM**
    - **Local Outlier Factor (LOF)**
    - **Autoencoder (Deep Learning)**
- **Comprehensive Evaluation**: Uses metrics like AUC, precision, recall, and F1-score to evaluate and compare the performance of each method.
- **Visualization**: Generates plots to visualize the original data, the training progress of the autoencoder, and a comparison of the results of all methods.

## How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/GruheshKurra/AnomalyDetection.git
    ```
2.  **Install dependencies:**
    The notebook will install the necessary dependencies when you run the first code cell.
3.  **Run the notebook:**
    Open and run the `implementation.ipynb` notebook in a Jupyter environment to execute the full analysis.

## License

This project is licensed under the MIT License. 
