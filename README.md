# Software Engineering StackExchange CQA Recommendation System Project

## Overview

The project involves cleaning the CQA dataset and creating utility matrices to facilitate collaborative filtering. The goal is to recommend tags to experts based on their previous answers, utilizing both item-item and user-user collaborative filtering techniques.

## Features

- **Dataset Cleaning**: Extracting relevant information from the raw XML dataset and converting it into a structured format (CSV).
- **Collaborative Filtering**: Implementing both item-item and user-user collaborative recommendation systems.
- **Performance Evaluation**: Comparing the performance of different recommendation strategies using RMSE (Root Mean Square Error).

## Requirements

To run the code, ensure you have the following Python libraries installed:

- **pandas**
- **numpy**

## Tech Stack
- **Python**: Core programming language
- **numpy**: For blazingly fast mathematical calculations
- **pandas** : For handling csv files as matrices in the form of dataframes

## How to Use
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/AdilSalfi/StackExchange-ExpertTagRating-RecommendationSystem.git
   cd StackExchange-ExpertTagRating-RecommendationSystem
   
2. **Install Dependencies: Install SciPy and Matplotlib**
   ```bash
   pip install numpy pandas

3. **Run the Code: Execute the main script to model the reaction and optimize parameters**
   ```bash
   jupyter notebook collaborative_filering_model.ipynb

You can install the required libraries using:

```bash
pip install -r requirements.txt
