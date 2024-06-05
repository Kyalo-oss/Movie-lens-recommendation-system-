# MovieLens Recommender System
This repository contains a collaborative filtering recommender system for movie recommendations using the MovieLens dataset. The notebook demonstrates the entire process of loading, preprocessing data, training a recommendation model, evaluating its performance, and generating movie recommendations.

## Project Overview
The project includes the following steps:

**Data Loading and Preprocessing:** Loading MovieLens dataset and preparing it for analysis.
**Exploratory Data Analysis (EDA):** Understanding the dataset through various statistical measures and visualizations.
**Model Training:** Using the Surprise library to train a collaborative filtering model (KNNBasic and SVD).
**Model Evaluation:** Evaluating the model's performance using metrics like RMSE, MAE, and R-squared.
**Generating Recommendations:** Providing top 10 movie recommendations for a specific user.

## Installation
To run the notebook, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-surprise

You can install the required libraries using pip:

``` pip install pandas numpy matplotlib seaborn scikit-surprise ```

## Usage

1. Clone the Repository:
   ``` git clone https://github.com/Kyalo-oss/movielens-recommendetion-system.git
cd movielens-recommender-system ```

2. Run the Jupyter Notebook:
Open the `Movielens_solution.ipynb` notebook using Jupyter and execute the cells to reproduce the analysis and model training.

3.Generate Recommendations:
Modify the user_id in the notebook to get movie recommendations for a specific user.

## Results
The trained model achieved the following evaluation metrics:

- RMSE: 0.87
- MAE: 0.68
- R-squared: 0.3916
  
The top 10 movie recommendations for user 5 are:

1. Brazil (1985)
2. Annie Hall (1977)
3. This Is Spinal Tap (1984)
4. Magnolia (1999)
5. Ed Wood (1994)
6. Dr. Strangelove or: How I Learned to Stop Worrying and Love the Bomb (1963)
7. A Clockwork Orange (1971)
8. Heathers (1989)
9. Roger & Me (1989)
10. Blood Simple (1984)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.



