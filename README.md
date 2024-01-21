# Lung Cancer Detection using Machine Learning

## Overview

This project focuses on the application of Machine Learning (ML) algorithms for the detection of lung cancer. The dataset used in this project contains 307 samples and 16 attributes related to lung cancer. Our goal is to develop a model that can effectively detect lung cancer cases, with a specific emphasis on maximizing the Recall value to minimize false negatives.

## Project Structure

- `data/`: This directory contains the dataset used in the project.
- `notebooks/`: Jupyter notebooks used for data exploration, preprocessing, and model selection.
- `results/`: Results and performance metrics obtained during model training and evaluation.
- `requirements.txt`: List of dependencies for running the project.

## Methodology

We followed an Iterative Model Selection approach to determine the best ML model for lung cancer detection. The primary evaluation metric considered in this project is Recall, as we aim to minimize false negatives and avoid missing any positive lung cancer cases.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/lung-cancer-detection.git
    cd lung-cancer-detection
    ```

2. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Explore the Jupyter notebooks in the `notebooks/` directory for detailed insights into data analysis, preprocessing, and model selection.

4. Run the machine learning models by executing the code in the `src/` directory.

## Results

We achieved promising results during the model selection process, with a strong emphasis on maximizing Recall. I got the highest accuracy for Random Forest Algortihm i.e. 97% whereas KNN, logistic Regression, gradient boosting, Light Gradient Boosting and support vector classifier achieved 73%, 93%, 71%, 91% and 50% respectively. Random forst algortihm gave the best accuracy as well as recall. 

## Future Improvements

- Explore additional datasets to enhance model generalization.
- Fine-tune hyperparameters for further optimization.
- Consider ensembling techniques for improved performance.
- Work with CNN using image datasets going on Chest Xray image samples

## Contributors

- [Srushti](https://github.com/Srushtea)

## License

This project is licensed under the [MIT License](LICENSE).
