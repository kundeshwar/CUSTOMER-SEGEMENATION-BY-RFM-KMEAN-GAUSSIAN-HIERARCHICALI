# CUSTOMER-SEGEMENATION-BY-RFM-KMEAN-GAUSSIAN-HIERARCHICALI
This project focuses on customer segmentation using various dimension reduction algorithms (PCA, t-SNE) and clustering techniques (K-Means, Gaussian, Hierarchical) with RFM (Recency, Frequency, Monetary) analysis and cohort analysis.

## Exploratory Data Analysis (EDA)

The following steps were performed as part of the EDA:

1. **Univariate Analysis**: Analyzed individual variables to understand their distribution and characteristics.
2. **Multivariate Analysis**: Explored the relationships between multiple variables to identify patterns and correlations.

## Feature Engineering

To enhance the data for segmentation, the following feature engineering steps were undertaken:

1. **Creating New Columns**: Generated new features based on existing variables to capture additional insights.
2. **Modifying Existing Ones**: Modified existing features to extract more meaningful information.

## Handling Outliers

Outliers were handled using the following approach:

1. **Detecting Outliers**: Identified outliers within the dataset.
2. **Removing Outliers**: Removed the detected outliers from the dataset.

## Installation and Dependencies

To run the code for this project, make sure you have the following dependencies installed:

- pandas
- numpy
- seaborn
- matplotlib
- nltk

To install the required dependencies, run the following command:
pip install -r requirements.txt

## Dataset

The dataset used for this project is stored in a CSV file named "ecom.csv". It contains the following columns:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## Usage

1. Import the necessary libraries and dependencies.
2. Load the dataset using the provided CSV file.
3. Perform exploratory data analysis and feature engineering.
4. Handle outliers in the data.
5. Apply dimension reduction algorithms and clustering techniques for customer segmentation.
6. Conduct RFM analysis and cohort analysis to gain insights into customer behavior.
7. Interpret the results and draw conclusions from the segmentation.

## Contributing

Contributions to this project are welcome. Feel free to open issues or submit pull requests to suggest improvements or new features.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

This project was completed as part of Kundeshwar Pundalik's project work. 


