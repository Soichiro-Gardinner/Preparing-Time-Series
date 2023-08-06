# Zillow House Value Index (ZHVI) Analysis Assignment

This repository contains code and analysis for the Zillow House Value Index (ZHVI) assignment. The goal of this assignment is to perform time series analysis on Zillow's publicly available ZHVI data and answer specific questions about home values for different cities.

## Instructions

1. Clone or download this repository to your local machine.

2. The core of the assignment involves preparing time series data from the ZHVI dataset. The dataset can be accessed from [Zillow's ZHVI Data](https://www.zillow.com/research/data/). Specifically, the "ZHVI All Homes (SFR+Condo/Coop) - Time Series - Smoothed - Seasonally Adjusted" data for "City" geography should be used.

3. The provided Python code in the repository performs the following tasks:

   - Loads and preprocesses the ZHVI data.
   - Filters the 4 largest cities.
   - Converts data to long-form for time series analysis.
   - Calculates and displays the city with the highest and lowest home values at the end of 2008.
   - Calculates and displays the change in home values from November 2008 to December 2008.

4. Adjustments have been made to the original code to fulfill specific requirements, including displaying the actual home values for the highest and lowest cities and formatting the output.

## Usage

1. Install the required Python packages if not already installed:
- pip install pandas
- pip install matplotlib

2. Run the provided Python code in your preferred Python environment.

3. The code will load and process the ZHVI data, perform the required calculations, and display the results.

## Results

The code generates output that answers the following questions:

1. Which city had the highest typical home value at the end of 2008? Which had the least?
2. How much did the home values change from November 2008 to December 2008 (in dollars)?

The output includes the city names, home values, and changes in home values.

## Contact

For any questions or clarifications regarding this assignment, please contact Oscar Catanaza at OscarCollegeboard@gmail.com.


 
