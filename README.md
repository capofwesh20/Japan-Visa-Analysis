# Japan-Visa-Analysis
![image](https://github.com/capofwesh20/Japan-Visa-Analysis/assets/35642413/456bed69-9048-4d2c-89d5-ef9696dfb6da)
This project provides an end-to-end data processing and visualization of visa numbers in Japan using PySpark and Plotly. The spark clusters are set up within a Docker container on Azure.
# System Architecture
![image](https://github.com/capofwesh20/Japan-Visa-Analysis/assets/35642413/1b7d64b8-a4d4-4ccb-b57d-6a9ba9bb4f97)

## 🛠 Setup & Requirements
1. Azure Account: Ensure you have an active Azure account.
2. Docker: The Spark master-worker architecture is set up in a Docker container on Azure.
3. Python Libraries: Install the required Python libraries:
- **PySpark**
- **Plotly Express**
- **pycountry**
- **pycountry_convert**
- **fuzzywuzzy**

## 🚀 Usage
Data Input: Place your CSV file named visa_number_in_japan.csv in the input directory.
Run the Script: Execute the provided Python script.
Visualizations: After execution, you'll find the visualizations saved as HTML files in the output directory.
Cleaned Data: The cleaned data will also be saved as a CSV file in the output directory.

## 📈 Features
System Architecture: The Spark master-worker architecture is set up in a Docker container on Azure.
Data Ingestion: The script ingests the CSV file containing the visa numbers in Japan.
Data Cleaning: The script standardizes column names, drops null columns, and corrects country names using fuzzy matching.
Data Transformation: The data is further enriched by adding continent information for each country.
Data Visualization: The cleaned and transformed data is visualized using Plotly Express to provide insights into visa trends in Japan.
