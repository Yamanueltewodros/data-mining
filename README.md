# Data Mining Project

## Overview
This project involves the analysis of accident data using a Decision Tree Classifier. The goal is to predict the severity of accidents based on various features such as region, gender of victims, driver education level, and more.

## Algorithm Used
- **Decision Tree Classifier**: A machine learning algorithm used for classification tasks. It splits the data into subsets based on the value of input features, creating a tree-like model of decisions.

## Dataset
The dataset used in this project is `preped-data.csv`, which contains the following columns:
- Region
- Gender of Victims
- Driver Education Level
- Driver Experience
- Cars Service Years
- Vehicle Types
- Vehicles Owner
- Places of Accident Occurred
- Road Type
- Placement of the Road
- Road Connection
- Road Surface Type
- Road Characteristics
- Weather Conditions
- Vehicle Defects
- Accident Severity

## Installation
To run this project, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/million-mesfin/data-mining-project.git
    cd data-mining-project
    ```

2. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook "DM project (Decision Tree Classifier).ipynb"
    ```

## Usage
Open the Jupyter Notebook and run the cells to train the Decision Tree Classifier on the dataset and make predictions. The notebook includes data preprocessing, model training, and evaluation steps.

## Results
The results of the Decision Tree Classifier, including accuracy, precision, recall, and other metrics, are displayed in the notebook. Visualizations of the decision tree and feature importance are also provided.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License.

