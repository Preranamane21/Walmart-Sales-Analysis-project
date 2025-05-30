**Project Steps**

**1. Set Up the Environment**

Tools Used: Visual Studio Code (VS Code), Python,jupyter notebook, Power BI

Goal: Establish a structured and organized workspace for seamless data analysis and visualization. Use VS Code for data preprocessing and scripting, Jupyter Notebook for exploratory data analysis, and Power BI for creating interactive dashboards and visual insights.

**2. Set Up Kaggle API**

API Setup: Obtain your Kaggle API token from Kaggle by navigating to your profile settings and downloading the JSON file.
Configure Kaggle:
Place the downloaded kaggle.json file in your local .kaggle folder.
Use the command kaggle datasets download -d <dataset-path> to pull datasets directly into your project.

**3. Download Walmart Sales Data**

Data Source: Use the Kaggle API to download the Walmart sales datasets from Kaggle.
Dataset Link: Walmart Sales Dataset
Storage: Save the data in the data/ folder for easy reference and access.

**4. Install Required Libraries and Load Data**

Libraries: Install necessary Python libraries using:
pip install pandas numpy 
Loading Data: Read the data into a Pandas DataFrame for initial analysis and transformations.

**5. Explore the Data**

Goal: Conduct an initial data exploration to understand data distribution, check column names, types, and identify potential issues.

Analysis: Use functions like .info(), .describe(), and .head() to get a quick overview of the data structure and statistics.

**6. Data Cleaning**

Remove Duplicates: Identify and remove duplicate entries to avoid skewed results.
Handle Missing Values: Drop rows or columns with missing values if they are insignificant; fill values where essential.
Fix Data Types: Ensure all columns have consistent data types (e.g., dates as datetime, prices as float).
Currency Formatting: Use .replace() to handle and format currency values for analysis.
Validation: Check for any remaining inconsistencies and verify the cleaned data.

**7. Feature Engineering**

Create New Columns: Calculate the Total Amount for each transaction by multiplying unit_price by quantity and adding this as a new column.

**8.Create and Display Power BI Dashboard**

Goal: Visualize key insights from the Walmart sales data using Power BI.

Steps:

Export the cleaned and transformed dataset to a .csv file.
Import the CSV file into Power BI.
Create visualizations such as sales trends, top-performing products, store comparisons, and category-wise performance.
Format the dashboard for readability and share or publish it for stakeholder access.



![Screenshot 2025-05-30 170442](https://github.com/user-attachments/assets/2e523f10-3f39-441a-8e94-b387afb6442c)



