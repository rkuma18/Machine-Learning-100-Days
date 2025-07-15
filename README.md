# Machine Learning 100 Days

This repository is a hands-on, project-based journey through 100 days of machine learning, data analysis, and data science using Python. The project is organized as a series of Jupyter notebooks, each focusing on a key aspect of the data science workflow, from web scraping and data understanding to exploratory data analysis (EDA) and automated profiling.

## Project Structure

- **1_Web_scraping.ipynb**: Demonstrates web scraping techniques using `requests` and `BeautifulSoup` to collect company data from AmbitionBox, including company names, ratings, reviews, industries, and locations. The scraped data is saved for further analysis.
- **2_Understanding_data.ipynb**: Introduces the Titanic dataset and covers basic data exploration, including data loading, shape, types, missing values, and basic statistics.
- **3_EDA_Univariate.ipynb**: Performs univariate exploratory data analysis on the Titanic dataset, visualizing distributions and summary statistics for individual features using `seaborn` and `matplotlib`.
- **4_bivariate-analysis.ipynb**: Explores bivariate relationships in the Titanic dataset, such as the relationship between categorical and numerical variables, using bar plots, box plots, heatmaps, and cluster maps.
- **5_Pandas_profiler.ipynb**: Uses `ydata-profiling` (formerly pandas-profiling) to generate an automated, comprehensive HTML report of the Titanic dataset, summarizing distributions, correlations, and missing values.
- **output.html**: The output of the automated profiling report generated in notebook 5.

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

| Notebook                   | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| 1_Web_scraping.ipynb      | Web scraping of company data from AmbitionBox                                |
| 2_Understanding_data.ipynb| Data loading and basic exploration of the Titanic dataset                    |
| 3_EDA_Univariate.ipynb    | Univariate EDA: distributions, summary stats, and visualizations             |
| 4_bivariate-analysis.ipynb| Bivariate EDA: relationships between features, heatmaps, and cluster maps    |
| 5_Pandas_profiler.ipynb   | Automated data profiling and report generation with ydata-profiling          |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Roushan Kumar

---

*Happy Learning!* 