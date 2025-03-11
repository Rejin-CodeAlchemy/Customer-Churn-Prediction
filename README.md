# **Customer Churn Prediction**
## **Capstone Project**

### Description
This project aims to predict customer churn for a business using machine learning techniques. Customer churn refers to the phenomenon where customers stop using a company's products or services. By predicting churn, businesses can take proactive measures to retain customers and improve customer satisfaction.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation. The final model can be used to identify customers who are likely to churn, enabling targeted retention strategies..

### Table of Contents
1. [Project Structure](###project-structure)
2. [Dataset](###dataset)
3. [Requirements](###requirements)
4. [Installation](###installation)
5. [Author](###author)
6. [Submitted Date](###submitted-date)

### Project Structure
customer-churn-prediction/
├── data/ # Folder containing datasets
  ├── raw/ # Raw data files
  └── processed/ # Processed/cleaned data files
├── notebooks/ # Jupyter notebooks for EDA and modeling
├── docs/ # Reports, Business objectives, Data Dictionary
├── requirements.txt # Python dependencies
└── README.md # Project documentation

### Dataset
The dataset used in this project contains customer information, including features such as:

- **Demographics**: AccountID, Gender, City_Tier
- **Usage Patterns**: Tenure, Payment_mode, Coupon usage, Cashback
- **Churn Status**: Whether the customer churned (Target variable)

The dataset is located in the `data/raw/` folder. For more details, refer to the data source or data dictionary (These files are available in `docs/`).

### Requirements
To run this project, you need the following dependencies:
- Python 3.12+
- Libraries listed in `requirements.txt`

Install the dependencies using:
```bash
    pip install -r requirements.txt
```

### Installation
1. Clone the repository:
```bash
    git clone https://github.com/Rejin-CodeAlchemy/customer-churn-prediction.git
    cd customer-churn-prediction
```

2. Install the required packages:
```bash
    pip install -r requirements.txt
```

### Author
Rejin Raveendran

### Submitted Date
Sun, Mar 03 2025
