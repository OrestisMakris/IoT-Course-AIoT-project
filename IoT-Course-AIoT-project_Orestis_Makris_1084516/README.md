# AIoT Course - Human Gesture Recognition Project

# Orestis Antonis Makris

An End-to-end Artificial Intelligence of Things Project

This is a repository that contains the demonstration of the Human Gesture Recognition of AIoT lectures which are part of the course "Algorithmic Foundations of Sensor Networks" in the Computer Engineering and Informatics Department, University of Patras.

This project involves the loading, processing, and modeling of data using various machine learning techniques, including Random Forest, SVM, and neural networks (DNN, LSTM, and CNN).


## Prerequisites

Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)


## Running the Project

Open Jupyter Notebook: Start Jupyter Notebook by running the following command in your terminal or command prompt:
`jupyter notebook`
This will open the Jupyter Notebook interface in your default web browser.


Navigate to Notebooks: In the Jupyter Notebook interface, navigate to the directory where your project notebooks are located
(1_data_prparation_segmentation.ipynb, 2_aiot_dataset_creation.ipynb, 3_aiot_project.ipynb).


Execute Notebooks: Open each notebook (*.ipynb) individually and execute each cell sequentially by clicking on "Run" or using Shift+Enter. Here's the recommended order:

- `1_data_prparation_segmentation.ipynb`: Loads the data merges accelometer and Gyroscope for each recording sesion and segments them in inditital movements.
- `2_aiot_dataset_creation.ipynb`: Processes the data and pass to mongo DB.
- `3_aiot_project.ipynb`: EDA , Data Preparation Trains and evaluates the models, including:
  - Random Forest
  - SVM
  - Optimized Random Forest with Grid Search
  - Optimized SVM with Grid Search
  - Dense Neural Network (DNN)
  - Long Short-Term Memory network (LSTM)
  - Convolutional Neural Network (CNN)

## Notes

- The model training and evaluation can take significant time, especially the grid search optimizations and neural network training.
- Ensure you have sufficient computational resources available before running the project.

## Troubleshooting

If you encounter any issues:
1. Check that all dependencies are installed.
2. Verify that you are using a compatible Python version.
3. Consult the error logs produced by the notebooks for specific issues.

Feel free to open an issue or contact the project maintainers for further assistance.


