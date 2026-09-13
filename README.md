# E-Commerce Decision Support System (DSS)

## Overview
This project is a comprehensive Decision Support System (DSS) designed to analyze e-commerce and online retail data. The goal of this project is to clean, process, and visualize retail transaction data to provide actionable business insights for decision-makers.

This project was developed as part of **CS466 - Decision Support and Intelligent Systems**.

## Project Structure
The repository is organized into the following key directories:

- **`Code/`**: Contains the Jupyter Notebook (`DSS_project_code.ipynb`) used for data extraction, exploration, and extensive data cleaning using Python and Pandas.
- **`Dataset/`**: The original, raw dataset containing online retail transaction records (e.g., invoices, stock codes, quantities, prices, and customer IDs).
- **`Dataset after Cleaning/`**: The processed dataset exported after handling missing values, filtering out cancellations, and cleaning the data in the Jupyter Notebook.
- **`Power BI Visualization/`**: Contains the Power BI dashboard files used to create interactive visualizations and generate business intelligence reports based on the cleaned data.
- **`pics/`**: Screenshots and images showcasing the visualizations and key findings.

## Technologies Used
- **Python (Pandas, Seaborn, Matplotlib)**: For data cleaning, exploration, and preliminary analysis.
- **Jupyter Notebook**: For documenting and running the data processing code.
- **Power BI**: For advanced data visualization and building the interactive Decision Support System dashboard.

## How It Works
1. **Data Cleaning**: The raw data contains missing Customer IDs and cancelled orders. The Python script cleans this data, drops nulls, and structures it properly.
2. **Data Export**: The cleaned data is exported to a new CSV file.
3. **Visualization**: Power BI connects to the cleaned data to visualize sales trends, customer behavior, and product performance, enabling stakeholders to make data-driven decisions.

## License
MIT License
