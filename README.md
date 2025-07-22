# Machine Learning 100 Days

This repository is a hands-on, project-based journey through 100 days of machine learning, data analysis, and data science using Python. The project is organized as a series of Jupyter notebooks, each focusing on a key aspect of the data science workflow, from web scraping and data understanding to exploratory data analysis (EDA) and automated profiling.

## Project Structure

- **1_Web_scraping.ipynb**: Demonstrates web scraping techniques using `requests` and `BeautifulSoup` to collect company data from AmbitionBox, including company names, ratings, reviews, industries, and locations. The scraped data is saved for further analysis.
- **2_Understanding_data.ipynb**: Introduces the Titanic dataset and covers basic data exploration, including data loading, shape, types, missing values, and basic statistics.
- **3_EDA_Univariate.ipynb**: Performs univariate exploratory data analysis on the Titanic dataset, visualizing distributions and summary statistics for individual features using `seaborn` and `matplotlib`.
- **4_bivariate-analysis.ipynb**: Explores bivariate relationships in the Titanic dataset, such as the relationship between categorical and numerical variables, using bar plots, box plots, heatmaps, and cluster maps.
- **5_Pandas_profiler.ipynb**: Uses `ydata-profiling` (formerly pandas-profiling) to generate an automated, comprehensive HTML report of the Titanic dataset, summarizing distributions, correlations, and missing values.
- **output.html**: The output of the automated profiling report generated in notebook 5.
- **6_standardization.ipynb**: Demonstrates feature standardization using `StandardScaler` on a sample dataset.
- **7_normalization.ipynb**: Shows feature normalization using `MinMaxScaler` on the wine dataset.
- **8_One_Hot_Encoding.ipynb**: Explores one-hot encoding with pandas and scikit-learn, including handling top categories.
- **9_Column_Transformer.ipynb**: Introduces the use of `ColumnTransformer` for combining multiple preprocessing steps on the covid_toy dataset.
- **10_1_titanic-without-using-pipeline.ipynb**: Implements the Titanic classification problem without using pipelines, saving separate encoders and the classifier as pickled models.
- **10_2_predict-without-pipeline.ipynb**: Loads the pickled models and demonstrates making predictions on new Titanic data without a pipeline.
- **10_3_titanic-using-pipeline.ipynb**: Solves the Titanic problem using a full scikit-learn pipeline, including imputation, encoding, scaling, feature selection, and model training. The pipeline is exported as `pipe.pkl`.
- **11_Function_transformer.ipynb**: Explores all type of function transformer.
- **12_power-transformer.ipynb**: Demonstrates the use of power transformers for feature engineering and normalization.
- **13_1_binning-and-binarization.ipynb**: Covers binning and binarization techniques for feature engineering.
- **13_binning-and-binarization.ipynb**: Additional notebook on binning and binarization methods.
- **14_handling-date-and-time.ipynb**: Covers handling date and time.
- **models/**: Contains pickled model artifacts: `clf.pkl`, `ohe_sex.pkl`, `ohe_embarked.pkl` (from the non-pipeline Titanic workflow).
- **pipe.pkl**: The exported scikit-learn pipeline from the pipeline-based Titanic workflow.
- **IT Company Rating and Reviews.csv**: Dataset of company reviews scraped from AmbitionBox.
- **Social_Network_Ads.csv, Titanic-Dataset.csv, cars.csv, covid_toy.csv, wine_data.csv**: Additional datasets used in various notebooks.

## Key Features

- **End-to-End Data Science Workflow**: From data collection (web scraping) to data understanding, EDA, and automated reporting.
- **Jupyter Notebooks**: Each step is documented and executable, making it easy to follow and reproduce.
- **Real-World Datasets**: Uses the Titanic dataset and scraped company data for practical, hands-on learning.
- **Visualization**: Extensive use of `matplotlib` and `seaborn` for data visualization.
- **Automated Profiling**: Quick, comprehensive data profiling with `ydata-profiling`.

## Requirements

All dependencies are listed in `requirements.txt`. To install them, run:

```bash
pip install -r requirements.txt
```

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone <repo-url>
   cd Machine-Learning-100-Days
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the notebooks**:
   Open the notebooks in JupyterLab or VSCode and run them in order for a step-by-step learning experience.

## Notebooks Overview

| Notebook                                 | Description                                                                 |
|------------------------------------------|-----------------------------------------------------------------------------|
| 1_Web_scraping.ipynb                     | Web scraping of company data from AmbitionBox                                |
| 2_Understanding_data.ipynb               | Data loading and basic exploration of the Titanic dataset                    |
| 3_EDA_Univariate.ipynb                   | Univariate EDA: distributions, summary stats, and visualizations             |
| 4_bivariate-analysis.ipynb               | Bivariate EDA: relationships between features, heatmaps, and cluster maps    |
| 5_Pandas_profiler.ipynb                   | Automated data profiling and report generation with ydata-profiling          |
| 6_standardization.ipynb                  | Feature standardization with StandardScaler                                  |
| 7_normalization.ipynb                    | Feature normalization with MinMaxScaler                                      |
| 8_One_Hot_Encoding.ipynb                 | One-hot encoding with pandas and scikit-learn                                |
| 9_Column_Transformer.ipynb               | Combining preprocessing steps with ColumnTransformer                         |
| 10_1_titanic-without-using-pipeline.ipynb| Titanic classification without pipelines, manual preprocessing and modeling   |
| 10_2_predict-without-pipeline.ipynb      | Making predictions using saved models (no pipeline)                          |
| 10_3_titanic-using-pipeline.ipynb        | Titanic classification using a full scikit-learn pipeline                    |
| 11_Function_transformer.ipynb         | Function Tranformer with Sklearn                                              |
| 12_power-transformer.ipynb            | Power transformer for feature engineering and normalization                   |
| 13_1_binning-and-binarization.ipynb   | Binning and binarization techniques for feature engineering                   |
| 13_binning-and-binarization.ipynb     | Additional binning and binarization methods                                   |
| 14_handling-data-and-time.ipynb        | Handling date and time                                                       |

## Model Artifacts

- **models/**: Contains pickled models for the non-pipeline Titanic workflow:
  - `clf.pkl`: Trained DecisionTreeClassifier
  - `ohe_sex.pkl`: OneHotEncoder for the 'Sex' feature
  - `ohe_embarked.pkl`: OneHotEncoder for the 'Embarked' feature
- **pipe.pkl**: Complete scikit-learn pipeline for the Titanic dataset (pipeline-based workflow)

## Datasets

- **IT Company Rating and Reviews.csv**: Scraped company reviews
- **Social_Network_Ads.csv**: Used for standardization/normalization examples
- **Titanic-Dataset.csv**: Main dataset for Titanic notebooks
- **cars.csv**: Used in encoding examples
- **covid_toy.csv**: Used in column transformer notebook
- **wine_data.csv**: Used in normalization notebook

## Project Status

This repository is up to date with the latest files and notebooks, including the new additions for power transformation and binning/binarization. All changes are ready to be pushed to GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Roushan Kumar

---

*Happy Learning!* 