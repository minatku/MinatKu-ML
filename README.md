# CH2-PS229 MinatKu

# Table of Contents
* [General Info](#general-info)
* [Roadmap](#roadmap)
* [Python Libraries](#python-libraries)
* [Contact](#contact)
* [Documentation](#documentation)

# General Info
This is the machine learning part of CH2-PS229 capstone project called MinatKu. This application will help students to achieve improvement in the alignment between their majors and interests by creating an accessible online career guidance platform and personalized major recommendations from assessments test.

# Roadmap
#### 1. Data Collection
The initial step involves gathering data to create a dataset, which can be found in the "Data Cleaning and Preprocessing" folder.

#### 2. Data Cleaning and Preprocessing
Following data collection, we proceed to clean and process the raw data to generate a cleaned dataset.

#### 3. Model Development
Next, we attempt to create a random model using a Neural Network. However, the achieved accuracy falls short of expectations.

#### 4. Model Optimization
In response, efforts are made to enhance the model architecture, leading to improved accuracy that meets the desired standards.

#### 5. Model Deployment
Upon successful model creation, the model is deployed using a Flask API.

# Python Libraries
We built the model in Google Colab using the following libraries
* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [TensorFlow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [Scikit Learn](https://scikit-learn.org/stable/)

# Contact
For further information, kindly contact to :
- fhazzami@gmail.com (Fadhil Hadrian/fidelhadrian)
- andininurul83@gmail.com (Nurul Andini/nurandin)
- chinarasiwinugrahani@gmail.com (Chinara Siwi Nugrahani/chinarasiwinugrahani)

# Documentation
## Data Cleaning and Preprocessing Documentation

### Setup

To run this notebook, we will need:

- Python environment
- Jupyter notebook or Google Colab

Install the necessary library using:

```bash
pip install pandas
```

### Usage
1. Open the notebook in a Jupyter environment.
2. Mount Google Drive to access the dataset.
3. Execute each cell in sequence for data cleaning and preprocessing.

### Steps
1. Loading the Dataset
2. Dropping Unnecessary Columns
3. Renaming Columns
4. Creating New Columns
5. Mapping
6. Dropping Original Question Columns
7. Saving to CSV

### Output
The resulting CSV file (RIASEC10Q.csv) can be downloaded using the link provided or through the last cell in the notebook.

## MinatKu Model Documentation

MinatKu is a model developed for predicting academic interests based on a dataset. It uses a neural network implemented with Keras and TensorFlow.

### Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Model Training](#model-training)

### Installation

To use the MinatKu model, follow these steps:

1. Clone the repository or download the `Model MinatKu.ipynb` file.

2. Open the notebook in a Jupyter environment or any compatible platform.

3. Run the notebook to load the required dependencies and train the model.

### Usage

The MinatKu model can be used to predict academic interests based on input features. Here's a brief overview:

- Load the notebook and execute the provided code cells.

- The model is trained on a dataset (`RIASEC12Q.csv`) containing academic interest labels.

- Example predictions are provided for three different academic interest categories: Science, Arts and Literature, and Technology.

### Model Training
The model is trained on the provided dataset with the following architecture:

- Input layer: Dense layer with 128 units and ReLU activation.
- Hidden layer: Dense layer with 64 units and ReLU activation.
- Dropout layer: Dropout with a rate of 0.6.
- Output layer: Dense layer with softmax activation.
- The model is compiled with categorical crossentropy loss and Adam optimizer.


