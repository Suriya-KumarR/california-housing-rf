# Predicting California Housing Prices and Visualizing Homes with DALL-E

## Overview

This project aims to predict housing prices in California using a Random Forest Regressor and visualize homes based on user inputs using DALL-E. The interactive application allows users to input various features of a house and get a predicted price along with a generated image of the house.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Interactive GUI](#interactive-gui)
- [Image Generation](#image-generation)
- [Personal Experience](#personal-experience)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/suriyakumar99/california-housing-rf.git
    ```

2. Install Jupyter Notebook:
    ```sh
    pip install notebook
    ```

## Usage

1. Navigate to the project directory:
    ```sh
    cd california-housing-rf
    ```

2. Launch Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

3. Open `housing_price_prediction.ipynb` and run the cells to start the interactive GUI.

## Features

- Predict housing prices in California using a Random Forest Regressor.
- Visualize homes based on input features using DALL-E.
- Interactive GUI for user inputs.

## Data Preprocessing

The California Housing dataset is preprocessed by handling missing values, scaling features, and creating additional features such as:
- Rooms per household
- Bedrooms per room
- Population per household

## Model Training

The preprocessed data is used to train a Random Forest Regressor to predict housing prices. The model is evaluated on a test set to ensure accuracy.

## Interactive GUI

An interactive GUI is created using `ipywidgets` to allow users to input house features and get real-time predictions and visualizations.

## Image Generation

DALL-E is used to generate images based on the user inputs. The generated image provides a visual representation of the house with the specified features.

## Personal Experience

As an international student living in Riverside, California, I have experienced the challenges posed by the current housing bubble. The rising prices have made it increasingly difficult to find affordable housing. This project not only enhanced my understanding of machine learning and AI but also provided a practical tool to navigate the complex housing market.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
