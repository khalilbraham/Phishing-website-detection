# Phishing Website Detection Project

## Overview

This project aims to detect phishing websites through a comprehensive pipeline involving data collection, feature extraction, data cleaning, and model training. The project is divided into four distinct parts, each encapsulated in its own Jupyter notebook.

## Project Pipeline

### Part 1: Web Scraping and Data Collection
- **Description**: This notebook collects data from various webpages using web scraping techniques and an external dataset from Kaggle.
- **Requirements**: Ensure you have the appropriate version of `chromedriver` installed and configured correctly.
- **Output**: `phish_website.csv` & `legitimate_websites.csv`
- **Note**: This part may take a significant amount of time to execute. The result files are available in the Datasets Folder.

### Part 2: Features Extraction
- **Description**: This notebook processes the list of links to generate the required features for phishing detection.
- **Requirements**: May require external packages such as `whois` and `threading`.
- **Output**: `legit_file.csv` & `phish_file.csv`
- **Note**: Execution time is extensive. The task was divided into generating 6 different files. These files are available in the Datasets Folder.

### Part 3: Data Construction and Cleaning
- **Description**: This notebook merges and cleans the files from Part 2, performing necessary cleaning and visualization tasks to create the final dataset for modeling.
- **Output**: `database_websites.csv`
- **Note**: The output file exists in the Datasets Folder.

### Part 4: Websites Classification
- **Description**: This notebook trains and optimizes various models to classify websites as legitimate or phishing.
- **Output**: Classification results and model performance metrics.

## Instructions

1. **Run Part 1: Web Scraping and Data Collection**
   - Ensure `chromedriver` is correctly installed.
   - Execute the notebook to collect data.

2. **Run Part 2: Features Extraction**
   - Install required packages (`whois`, `threading`).
   - Execute the notebook to generate feature files.

3. **Run Part 3: Data Construction and Cleaning**
   - Execute the notebook to merge and clean data.
   - Verify the output file `database_websites.csv`.

4. **Run Part 4: Websites Classification**
   - Execute the notebook to train and evaluate classification models.
   - Review the results and model performance.

## Dataset

All necessary datasets are included in the Datasets Folder:
- `phish_website.csv`
- `legitimate_websites.csv`
- `legit_file.csv`
- `phish_file.csv`
- `database_websites.csv`

## Notes

- Execution time for parts 1 and 2 can be significant. Pre-generated result files are provided for convenience.
- Ensure all dependencies are installed before running each notebook.
- For any issues or questions, please refer to the respective notebook's documentation.

---

This project provides a structured approach to detecting phishing websites through data collection, feature extraction, data cleaning, and classification. Follow the instructions for each part to replicate the results and achieve optimal website classification performance.
