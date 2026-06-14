# ChurnSense - Customer Churn Prediction

ChurnSense is a machine learning project built during the IoT Academy Applied Data Science and Machine Learning Internship. It uses telecom customer data to predict churn and support business decisions with exploratory data analysis, model building, and deployment work.

## Project Overview

The goal of this project is to identify customers who are likely to leave a telecom service. By combining data analysis and machine learning, the project helps uncover the main drivers of churn and provides a foundation for retention strategies.

## Dataset

This project uses the IBM Telco Customer Churn dataset.

## Repository Structure

```bash
churnsense/
├── app/              # Application code for deployment or inference
├── data/             # Raw and processed datasets
├── models/           # Saved trained models and artifacts
├── notebooks/        # Jupyter notebooks for EDA and experimentation
├── reports/          # Figures, summaries, and project reports
├── src/              # Source code for data processing and modeling
├── tests/            # Automated tests
├── requirements.txt  # Python dependencies
└── README.md         # Project documentation
```

## Setup

1. Create and activate a virtual environment.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

## Dependencies

The project currently uses:

- ipykernel
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Typical Workflow

1. Explore the dataset in [notebooks/01_eda.ipynb](notebooks/01_eda.ipynb).
2. Build preprocessing and model training logic in [src/](src/).
3. Save trained models in [models/](models/).
4. Use [app/](app/) for deployment or prediction entry points.
5. Document findings and results in [reports/](reports/).

## Notes

This README can be expanded later with model metrics, feature engineering details, deployment instructions, and example predictions once those pieces are finalized.
