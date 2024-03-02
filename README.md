# Final Assignment | Data Management and Visualization (CDSCO2303U)

## Introduction

This repository contains the final assignment for the course Data Management and Visualization (CDSCO2303U).
Winter Semester 2023/2024.

## Repository Structure

The repository is structured as follows:
- data:
    - AirBnbListings.csv: The original dataset
- airbnb-exploration.ipynb: Running exploratory data analysis
- airbnb-import.ipynb: Importing the dataset from the csv file and performing appropriate actions followed by export to Azure PostgreSQL database.
- airbnb-processing.ipynb: Loading the data from the Azure PostgreSQL database, performing appropriate processing steps and writing data to final Azure PostgreSQL database.
- credentials.py: Centrally storing all credentials necessary for running the individual scripts. 
- gitignore: Main file to exclude unnecessary files and folders from git.

## Instructions

To run the code within this repository, follow these steps:

1. Clone the repository to your local machine.
2. Make sure you have the necessary dependencies installed. Please run the following commands in your local terminal:
    - pip3 install pandas
    - pip3 install numpy
    - pip3 install seaborn
    - pip3 install matplotlib
    - pip3 install requests
    - pip3 install psycopg2-binary
    - pip3 install sqlalchemy
3. Open the relevant files in your preferred development environment.
4. Execute the python code and, if available, refer to the instructions provided in each file.