# Toxicity-Prediction

## Objective

The objective of this project is to predict the toxicity of a chemical compound using the Simplified Molecular Input Line Entry System (SMILES).

## Approach

To make predictions for the testing dataset in the `Submission.csv` file, you can follow one of the three approaches:

1. **Docker**: Utilize Docker for a streamlined experience.
2. **Pre-Generated Features**: Run the `Toxicity-Prediction.ipynb` file with pre-generated features to predict the toxicity.
3. **Generate Features**: Run the `Toxicity-Prediction.ipynb` file to generate features and predict the toxicity.

This approach enables accurate toxicity predictions for chemicals, contributing to safety in various industries.

## Getting Started

### Step 1: Setup

1. Download the entire repository from GitHub to your local machine and extract it. You will find a zip file named "400_features.7z" inside. Extract this file to obtain the "train_400.csv" and "test_400.csv" files.

2. Place all necessary files in a single folder for successful program execution. You should have the following files in the designated folder:

   - `Toxicity-Prediction.ipynb`
   - `train_400.csv`
   - `test_400.csv`
   - `test_II.csv`
   - `train_II.csv`
   - `boruta_features.pkl`
   - `rfe_features.pkl`

### Step 2: Jupyter Notebook

1. Open the `Toxicity-Prediction.ipynb` file with Jupyter Notebook.

2. Run Section-1: Import Libraries to import the required libraries for the program.

### Step 3: Load Pre-Generated Features

1. Run Section-3: Load the Pre-Generated Features with the `train_400.csv` and `test_400.csv` files from the GitHub repository.

### Step 4: Load Pre-Selected Features

1. Run Section-5: Load the Pre-Selected Features with the `rfe_features.pkl` and `boruta_features.pkl` files from the GitHub repository.

### Step 5: Modeling

1. Run Section-6: Modeling to build a predictive model.

### Step 6: Generate Results

1. Run Section-7: Result to generate the `Submission.csv` file.

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

We acknowledge the valuable contributions of the open-source community and developers who have made this project possible.

