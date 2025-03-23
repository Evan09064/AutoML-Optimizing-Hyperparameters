# AutoML Project 1 – Group 36

## About
This repository showcases our work on Automated Machine Learning using Sequential Model-Based Optimization (SMBO) to tune hyperparameters for SVM and Adaboost. We compare SMBO against grid and random search across three diverse OpenML datasets. The experiments provide insights into how SMBO adapts to different dataset dimensions and skewness, and they underscore the potential of AutoML in building robust predictive models.

## Repository Structure
- **assignment.py:** Contains the implementation of SMBO for hyperparameter optimization.
- **example_sinewave.py** Demonstrates SMBO on a sine wave optimization problem.
- **experiments.py:** Runs experiments optimizing SVM and Adaboost on OpenML datasets.
- **test.py:** Unit tests for the SMBO functions.
- **problem_description.pdf:** The assignment problem statement.
- **requirements.txt:** A list of dependencies for the project.
- **Documentation/AutoML_Assignment_1.pdf:** The full report detailing our methodology, experiments, and results.
- **README.md:** This file, which explains the project and how to reproduce our experiments.

## How to Run
1. Ensure you have Python 3.8+ and the necessary libraries installed (e.g., scikit-learn, numpy, matplotlib).
2. Navigate to the `Code` directory.
3. Run the main script:
   ```bash
   python automl_assignment1.py
