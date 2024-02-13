# European-and-Oceanian-Flags-Classification-Using-Decision-Trees
# Decision Tree Classifier for Flag Dataset

This repository contains a Python implementation of a decision tree classifier trained on a dataset containing information about various flags of countries.

## Description

The project is divided into three main parts:

1. **Data Preparation**: The dataset is loaded, processed, and split into training and test sets.
2. **Model Training and Selection**: Different decision tree models are trained to find the optimal `max_depth` and `ccp_alpha` parameters.
3. **Decision Tree Visualization**: The optimal decision tree is visualized and saved as an image file.

## Dataset

The dataset used is the Flag dataset from the UCI Machine Learning Repository, which can be found [here](https://archive.ics.uci.edu/ml/machine-learning-databases/flags/flag.data).

## Files in the Repository

- `data_preparation.py`: Contains code for loading and preprocessing the dataset.
- `model_training.py`: Contains code for training the decision tree classifier and tuning its parameters.
- `tree_visualization.py`: Contains code for visualizing the decision tree.

## Usage

To run the code, follow these steps:

1. Clone the repository.
2. Ensure you have all required libraries installed by running `pip install -r requirements.txt`.
3. Run `data_preparation.py` to prepare the data.
4. Run `model_training.py` to train the model and find the optimal parameters.
5. Run `tree_visualization.py` to visualize and save the decision tree.

## Requirements

- Python 3.6 or higher
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
