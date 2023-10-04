###Airbnb Data Analysis and Visualization

This project involves data analysis and visualization of Airbnb data using Python for data preprocessing and Power BI for interactive visualizations.

Table of Contents
Introduction
Features
Technologies Used
Usage
Power BI Visualization
Contributing
License
Introduction
This project combines Python for data preprocessing, including data cleaning and preparation, with Power BI for creating compelling and interactive visualizations based on the Airbnb dataset.

Features
Data Cleaning:

Conversion of currency columns to numeric types.
Handling missing values for certain columns.
Extracting geographical information.
Visualization:

Histograms and box plots for numerical features using Python.
Interactive and insightful visualizations using Power BI.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Power BI
Usage
Ensure you have the necessary Python dependencies installed:

bash
Copy code
pip install pymongo pandas numpy matplotlib seaborn
Update the conn_str variable in the script with your MongoDB connection string.

Run the Python script to perform data cleaning and generate CSV:

bash
Copy code
python airbnb_data_analysis.py
Open the generated CSV (cleaned_airbnb_data.csv) in Power BI to create visualizations.

Power BI Visualization
Open Power BI Desktop.

Click on "Get Data" and select the data source (e.g., CSV file).

Load the cleaned Airbnb data.

Create insightful visualizations using the Power BI interface.

Save the Power BI project and share the interactive visualizations.

Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.
