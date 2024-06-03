# Final Year Project - Comparison of Hyperparameter Optimization Techniques 🤖  

## Overview 🔎
This repository contains report, presentation slide, documentation, experiment results, Streamlit webpage code as well as a collection of optimization algorithms and tools designed to enhance the hyperparameter tuning process for machine learning models. Various optimization strategies are included, such as Grid Search, Half Grid Search, Simulated Annealing, and Genetic Algorithm. Additionally, it features functions to visualize the optimization process, aiding in analysis and decision-making.  

## Contents 📕
1. **EDA Analysis**: Pictures of EDA analysis results.
2. **Experiment Results**: CSV results such as comparison time, pairwise distance, etc., in aggregated or individual records, and Tableau data visualization file.
3. **HPO Experiment Codes**: Dataset, experiment flow and codes, and files for hyperparameter optimization techniques.
4. **HPO Result Charts**: Plotted charts for each experiment (Confusion Matrix, ROC, Score vs. Iterations).
5. **Scaler + ML Models**: Scaler and best machine learning model created.
6. **Streamlit Codes**: Codes for creating the Streamlit webpage.
7. **Streamlit Website Pictures**: Pictures demonstrating the Streamlit webpage.
8. **DSP Presentation Slide**: PPT for presenting the report.
9. **Data Science Project Final Report**: 10-page academic report related to the findings from the project.
10. **Data Science Proposal**: PPT for proposing the project to the shareholders.

## Getting Started 🔨
### Prerequisites
- Python 3.x  
- Scikit-learn (for model building and evaluation)  
- NumPy (for numerical operations)  
- Matplotlib (for plotting results)   

### How to Utilize Hyperparameter Optimization Techniques 🤔
1. Check out and download the desired .py files in 'HPO Experiment Codes' folder
2. Import the desired module and use the functions to optimize your machine learning models. Each module contains functions that can be directly applied to a dataset and a model. For example, to use the Grid Search:

`from grid_search import grid_search`

`best_params = grid_search(model, param_grid, X_train, y_train, scoring_metric)`

Refer to the streamlit website below for detailed usage instructions and insights gained from the project.  
https://hpoexperiment-8wze5k5k6qpuscgwk7qmst.streamlit.app/Results%20and%20Findings

## Contributing 🧑‍🤝‍🧑
Contributions to enhance this toolkit are welcome. Please feel free to fork the repository and submit pull requests.
