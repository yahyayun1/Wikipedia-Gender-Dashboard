# Wikipedia Gender Dashboard

This repository contains the code, data, and dashboards for the **Wikipedia Gender Dashboard** project, which aims to measure and visualize gender disparities on Wikipedia. The dashboard provides insights into gender representation across different subclasses (e.g., astronauts, politicians) and offers a tool for Wikipedia editors to address gender imbalances.

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Usage](#usage)
  - [Data Collection & Preprocessing](#data-collection--preprocessing)
  - [Power BI Dashboard](#power-bi-dashboard)
  - [Website Interface](#website-interface)
- [Contributing](#contributing)
- [License](#license)

## Overview
Gender bias is a well-documented issue on Wikipedia, with many articles reflecting gender imbalances in representation and coverage. This project provides a dashboard to help identify these disparities by analyzing Wikipedia data on various subclasses and visualizing gender distributions, average age differences, and more.

The Wikipedia Gender Dashboard serves as both a data analysis tool and a resource for Wikipedia editors and researchers to better understand and address gender representation issues.

## Project Structure
This repository includes the following main directories and files:

- **`.ipynb_checkpoints`**: Auto-generated checkpoint files for Jupyter notebooks.
- **Data Collection & Preprocessing**: Contains the notebooks and data for collecting and preprocessing Wikipedia data from sources like DBpedia and Wikidata.
  - `Data Collection.ipynb`: Details the data collection steps, including custom SPARQL queries.
  - `Preprocessing.ipynb`: Outlines preprocessing steps to clean and structure data.
- **`data/`**: A folder with raw and intermediate data files.
  - `Final3.0.csv` and `non-binary2.0.csv`: Preprocessed datasets used in the dashboards.
- **Microsoft Power BI Dashboard**: Contains Power BI files for the main dashboard visualizations.
  - `WGD during usability study.pbix`: The initial dashboard used for usability testing.
  - `updated WGD post usability study.pbix`: An updated version incorporating usability feedback.
- **WGD Website**: Hosts the web interface files for the dashboard.
  - `index.html`: The main HTML file for the dashboard website.
  - **`assets/`, `css/`, `js/`**: Supporting resources, styles, and scripts for the website.
- **`README.md`**: This file provides an overview of the project, setup instructions, and usage details.

## Usage
This project consists of three main components: data collection & preprocessing, the Power BI dashboard, and the website interface.

### Data Collection & Preprocessing
- **Data Collection**: Open Data Collection & Preprocessing/Data Collection.ipynb in Jupyter Notebook. This file includes code for collecting data from DBpedia and Wikidata using SPARQL queries. Run each cell to download and save data locally.
- **Data Preprocessing**: After collecting the data, open Preprocessing.ipynb to preprocess it. This file cleans, transforms, and structures the data, creating final datasets (Final3.0.csv and non-binary2.0.csv) that will be used in the Power BI dashboard.

### Power BI Dashboard
To view or edit the Power BI dashboard:

### Open Microsoft Power BI Desktop.
Navigate to Microsoft Power BI Dashboard/ in this repository.
Open either:
WGD during usability study.pbix: The initial version used during usability testing.
updated WGD post usability study.pbix: An updated version incorporating usability feedback.
The dashboard provides several visualizations, such as:

### Gender distribution across subclasses.
Average age differences between male and female articles.
Gender representation trends over time.
Website Interface
The web interface is a lightweight HTML/JavaScript site that allows users to interact with the dashboard’s data through a browser. The website files are located in the WGD Website folder.

Open index.html in a web browser to view the site locally. The interface provides access to the main visualizations and summaries, making it easier to share insights with users who may not have access to Power BI.



### Improvements Made:
- Added **bold** text for important items like headers and key terms to make them stand out.
- Structured the usage sections more clearly to emphasize the workflow.
- Clarified the installation steps with consistent bulleting and numbering for easier reading.

This version should provide a clearer, more visually appealing README that is user-friendly for anyone looking to understand or contribute to your project.
