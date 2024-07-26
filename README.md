# Top Strikers Unleashed: Performance Analysis and Classification

This project focuses on analyzing and classifying soccer strikers based on their performance metrics. The workflow includes data cleaning, imputation, feature transformation, model training, and evaluation. Below is a detailed overview of the project.

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Data Description](#data-description)
7. [Methodology](#methodology)
8. [Results](#results)
9. [Contributing](#contributing)
10. [License](#license)

## Introduction

The goal of this project is to classify the best strikers in soccer using various performance metrics. The data analysis includes handling missing values, feature scaling, applying machine learning algorithms, and visualizing the results.

## Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Libraries: pandas, numpy, sklearn, matplotlib, seaborn, scipy

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Abhaypra/Segmenting_and_Classifying_the_Best_Strikers.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Segmenting_and_Classifying_the_Best_Strikers
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Navigate to `Segmenting_and_Classifying_the_Best_Strikers.ipynb` and open it.
3. Run the notebook cells sequentially to perform data analysis and classification.

## Project Structure

```
Segmenting_and_Classifying_the_Best_Strikers/
│
├── data/
│   └── Strikers_performance.xlsx    # Dataset
├── Segmenting_and_Classifying_the_Best_Strikers.ipynb    # Jupyter Notebook
├── requirements.txt    # List of required packages
└── README.md    # Project documentation
```

## Data Description

The dataset (`Strikers_performance.xlsx`) contains various performance metrics for soccer strikers. Key columns include:
- Goals Scored
- Assists
- Shots on Target
- Movement off the Ball
- Hold-up Play
- Aerial Duels Won
- Defensive Contribution
- Big Game Performance
- Impact on Team Performance
- Off-field Conduct

## Methodology

1. **Data Import**: Load the dataset from an Excel file.
2. **Data Cleaning**: Handle missing values using median and most frequent strategies.
3. **Feature Transformation**: Normalize features using StandardScaler.
4. **Model Training**: Train a logistic regression model to classify strikers.
5. **Evaluation**: Assess model performance using accuracy and confusion matrix.
6. **Statistical Analysis**: Apply Yeo-Johnson transformation and visualize data distributions.

## Results

- The confusion matrix provides insight into the model's prediction performance.
- Visualizations such as box plots and KDE plots help in understanding the data distribution.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
