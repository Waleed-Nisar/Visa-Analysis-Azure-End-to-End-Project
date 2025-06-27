# Visa-Analysis-Azure-End-to-End-Project

This project provides an end-to-end data processing and visualization of visa numbers in Japan using PySpark and Plotly. The spark clusters are set up within a Docker container on Azure.


## System Architecture
![Sparkcluster_architecture](https://github.com/user-attachments/assets/bfd480b1-8973-41a8-89bb-580d5da800ed)

## Setup & Requirements

* Azure Account: Ensure you have an active Azure account.
* Docker: The Spark master-worker architecture is set up in a Docker container on Azure.
* Python Libraries: Install the required Python libraries:
                                * PySpark
                                * Plotly     
                                * Pandas
## 🚀 Usage
* Data Input: Place your CSV file named visa_number_in_japan.csv in the input directory.
* Run the Script: Execute the provided Python script.
* Visualizations: After execution, you'll find the visualizations saved as HTML files in the output directory.
* Cleaned Data: The cleaned data will also be saved as a CSV file in the output director


## 📈 Features

* System Architecture: The Spark master-worker architecture is set up in a Docker container on Azure.
* Data Ingestion: The script ingests the CSV file containing the visa numbers in Japan.
* Data Cleaning: The script standardizes column names, drops null columns, and corrects country names using fuzzy matching.
* Data Transformation: The data is further enriched by adding continent information for each country.
* Data Visualization: The cleaned and transformed data is visualized using Plotly Express to provide insights into visa trends in Japan.


