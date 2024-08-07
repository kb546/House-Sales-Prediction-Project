# House-Sales-Prediction-Project

## Project Description
This project focuses on predicting house prices in King County, USA using various machine learning techniques. The goal is to build a predictive model that can accurately estimate house prices based on features such as square footage, number of bedrooms, and more. 

## Table of Contents
1. [Getting Started](#getting-started)
2. [Project Structure](#project-structure)
3. [Features](#features)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)
7. [Acknowledgments](#acknowledgments)
8. [Contact Information](#contact-information)

## Getting Started

### Prerequisites
- Python 3.x
- Required libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/house-sales-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd house-sales-prediction
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Usage
1. Place the dataset `kc_house_data.csv` in the `data/` directory.
2. Run the main script:
    ```bash
    python main.py
    ```
3. Example command to run the analysis:
    ```bash
    python main.py --input data/kc_house_data.csv
    ```

## Project Structure
- `main.py`: Main script for running the data analysis and model training.
- `requirements.txt`: List of Python dependencies.
- `data/`: Directory containing the dataset.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model development.

## Features
- **Data Cleaning and Feature Engineering**: Handled missing values and enhanced feature set.
- **Exploratory Data Analysis (EDA)**: Analyzed feature impacts on house prices using visualizations and statistical methods.
- **Model Development**: Implemented Linear Regression, Ridge Regression, and Polynomial transformations.
- **Model Performance**: Achieved an R² score of 0.75 with an optimized pipeline, and 0.70 with polynomial transformations and Ridge regression.

## Contributing
- Fork the repository and create a new branch.
- Make your changes and submit a pull request with a description of your updates or fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Special thanks to contributors and resources that provided valuable insights and support during this project.

## Contact Information
- [Bill Kamanzi](Bikamanzi@gmail.com)
- [LinkedIn Profile](https://www.linkedin.com/in/bill-kamanzi/)
