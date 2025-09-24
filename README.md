# Data Insights Portfolio

This repository contains a comprehensive data analysis project aimed at showcasing analytical skills relevant to **business analyst**, **program manager**, and **data analyst** roles. The project includes a synthetic dataset, exploratory data analysis with visualizations, and a predictive model to forecast customer churn.

## Project Structure

- `synthetic_customer_data.csv` – Synthetic customer dataset used for analysis.
- `analysis.ipynb` – Jupyter notebook containing exploratory data analysis, visualizations, and a predictive modeling pipeline.
- `requirements.txt` – List of Python packages required to run the notebook.

## Getting Started

1. **Clone the repository** or download the files.
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the Jupyter notebook:
   ```bash
   jupyter notebook analysis.ipynb
   ```
4. Explore the notebook cells to understand the data, visualizations, and machine learning model.

## Dataset

The synthetic dataset represents customer activity for a fictional e‑commerce business. Each row corresponds to a customer and contains demographic information, purchasing behavior, and a churn indicator. This dataset allows you to practice descriptive analysis, visualization, and predictive modeling tasks typically expected in business and data analyst roles.

## Analysis

The notebook demonstrates:

- Loading and summarizing the dataset using **pandas**.
- Visualizing key relationships, such as age distribution, average orders per region, and the relationship between age and spending.
- Building a machine learning model using **scikit‑learn** to predict customer churn. The pipeline includes one-hot encoding for categorical variables and logistic regression for classification.
- Evaluating the model using accuracy and classification metrics.

## Requirements

All dependencies are listed in `requirements.txt`. The main libraries used include:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

## Contributing

Feel free to fork this repository and experiment with the dataset or improve the analysis. You can explore different modeling approaches (e.g., random forest, XGBoost) or create additional visualizations to derive more insights.

## License

This project is released under the MIT License.
