# Data Cleaning for NYC Airbnb Listings

This repository contains code for cleaning and visualizing Airbnb listing data for New York City.

## Prerequisites

The code requires the following packages to be installed:

- pandas
- matplotlib
- numpy
- Pillow

## Usage

To use the code, download or clone the repository and run the `clean_data.py` script.

The script reads in data from two CSV files: `AB_NYC_2019.csv` containing Airbnb listing data, and `Latitude_Longitude.csv` containing latitude and longitude coordinates for New York City.

The script performs the following cleaning operations on the data:

- Selects a subset of columns to keep in the `cleanData` dataframe
- Drops columns that are not needed for analysis
- Removes rows with missing data using the `drop()` function
- Removes duplicate rows using the `drop_duplicates()` function
- Selects only rows with latitude and longitude coordinates within a specified range

The cleaned data is then visualized using matplotlib, with the listings plotted on a map of New York City.

## Contributing

Contributions to the code are welcome via pull requests. Please ensure that the code is well-documented and follows PEP8 style guidelines.

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the LICENSE.md file for details.
