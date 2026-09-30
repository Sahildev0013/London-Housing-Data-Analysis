
Exploratory data analysis (EDA) of London house prices using Python, NumPy and Pandas.

About the Project

This project analyses monthly housing data for London's boroughs from January 1995 to January 2020. It covers data inspection, missing-value checks, filtering, sorting and group-wise aggregation to understand how prices and sales differ across areas.

Dataset

File: London_Housing_Data.csv (13,549 rows, 6 columns, 45 areas)

Column	Description
date	Month of the record (1995-01 to 2020-01)
area	London borough or region name
average_price	Average house price (in £)
code	Area code
houses_sold	Number of houses sold in that month
no_of_crimes	Number of crimes recorded in that month

Missing values: houses_sold has 94 null values and no_of_crimes has 6,110 null values.

What the Notebook Covers

Basic exploration

Viewing the first and last rows, shape, data types and info()
Counting null values in each column
Finding the number of unique areas
Calculating the overall average price

Filtering and sorting

Filtering rows where average_price is above 500,000
Selecting data for a single area (Barnet)
Sorting by average_price in descending order
Finding the area with the highest average price

Group-wise analysis (groupby)

Mean average price for each area
Total houses sold for each area, and the area with the most sales
Minimum and maximum average price for each area
Tech Stack
Python
NumPy
Pandas
Jupyter Notebook
Project Structure
London-Housing-Analysis/
├── LondonHousing.ipynb        # Analysis notebook
├── London_Housing_Data.csv    # Dataset
└── README.md
Future Improvements
Add visualizations with Matplotlib and Seaborn (price trends over time, area comparisons)
Handle missing values properly
Build a Power BI dashboard for the dataset
Author

Sahildev0013 - GitHub
