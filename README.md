# Fuel Consumption Ratings Analysis

This project provides a comprehensive analysis of fuel consumption data for various vehicles based on models from 2020 to 2024. The project utilizes machine learning techniques to evaluate factors affecting fuel efficiency and carbon emissions.

---

## Overview

The `fuel-consumption-ratings` project aims to analyze and predict vehicle fuel consumption and CO2 emissions. By leveraging a dataset containing detailed vehicle specifications—such as engine size, cylinders, and fuel type—the project provides insights into the environmental impact of modern automobiles.

## Tech Stack

| Category | Technology |
| --- | --- |
| **Language** | Python |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Seaborn, Matplotlib |
| **Machine Learning** | Scikit-learn, XGBoost |
| **Development** | Jupyter Notebook |

---

## Project Structure

The project is organized to support a clear data analysis workflow:

```text
fuel-consumption-ratings/
├── Final.ipynb   # Main data analysis and modeling notebook
├── data1.csv     # Dataset containing vehicle specifications
└── README.md     # Project documentation

```

* **Final.ipynb**: Contains data preprocessing, exploratory data analysis (EDA), and machine learning model implementation using Regressors (Linear, Decision Tree, Random Forest, XGBoost).
* **data1.csv**: The primary source of vehicle performance data.

---

## Data Analysis Workflow

The project follows a standard data science pipeline:

1. **Data Loading**: Using Pandas to load the CSV dataset.
2. **Exploratory Data Analysis (EDA)**: Utilizing `df.describe()` and `df.info()` to understand data distributions and types.
3. **Preprocessing**:
* Handling categorical variables using `OneHotEncoder`.
* Analyzing correlations between features like engine size, cylinders, and fuel consumption.


4. **Modeling**: Training various regression models to predict fuel consumption metrics and CO2 emissions.

---

## Key Features Analyzed

The dataset includes the following features for each vehicle model:

* **Vehicle Info**: Model year, Make, Model, Vehicle class.
* **Specifications**: Engine size (L), Cylinders, Transmission, Fuel type.
* **Performance Metrics**: City/Highway/Combined (L/100 km), Combined (mpg).
* **Environmental Impact**: CO2 emissions (g/km), CO2 rating, Smog rating.

---

## Getting Started

### Prerequisites

You will need Python 3.8+ installed along with the following libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost joblib

```

### Running the Analysis

1. Clone this repository:
```bash
git clone https://github.com/arnavmaheshwari/fuel-consumption-ratings.git

```


2. Open `Final.ipynb` in Jupyter Notebook or JupyterLab.
3. Execute the cells sequentially to reproduce the analysis.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with any improvements or additional analyses.

---

## License

This project is licensed under the MIT License.

---

## Author

**Arnav Maheshwari** [GitHub Profile](https://www.google.com/search?q=https://github.com/arnavmaheshwari)

---

## Acknowledgements

* **Scikit-learn**: For providing robust machine learning algorithms.
* **XGBoost**: For advanced gradient boosting capabilities.
* **Pandas/Seaborn/Matplotlib**: Essential tools for data manipulation and visualization.
