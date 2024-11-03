Wikipedia Gender Dashboard
This repository contains the code, data, and dashboards for the Wikipedia Gender Dashboard project, which aims to measure and visualize gender disparities on Wikipedia. The dashboard provides insights into gender representation across different subclasses (e.g., astronauts, politicians) and offers a tool for Wikipedia editors to address gender imbalances.

Table of Contents
Overview
Project Structure
Setup Instructions
Usage
Data Collection & Preprocessing
Power BI Dashboard
Website Interface
Contributing
License
Overview
Gender bias is a well-documented issue on Wikipedia, with many articles reflecting gender imbalances in representation and coverage. This project provides a dashboard to help identify these disparities by analyzing Wikipedia data on various subclasses and visualizing gender distributions, average age differences, and more.

The Wikipedia Gender Dashboard serves as both a data analysis tool and a resource for Wikipedia editors and researchers to better understand and address gender representation issues.

Project Structure
This repository includes the following main directories and files:

.ipynb_checkpoints: Auto-generated checkpoint files for Jupyter notebooks.
Data Collection & Preprocessing: Contains the notebooks and data for collecting and preprocessing Wikipedia data from sources like DBpedia and Wikidata.
Data Collection.ipynb: Details the data collection steps, including custom SPARQL queries.
Preprocessing.ipynb: Outlines preprocessing steps to clean and structure data.
data/: A folder with raw and intermediate data files.
Final3.0.csv and non-binary2.0.csv: Preprocessed datasets used in the dashboards.
Microsoft Power BI Dashboard: Contains Power BI files for the main dashboard visualizations.
WGD during usability study.pbix: The initial dashboard used for usability testing.
updated WGD post usability study.pbix: An updated version incorporating usability feedback.
WGD Website: Hosts the web interface files for the dashboard.
index.html: The main HTML file for the dashboard website.
assets/, css/, js/: Supporting resources, styles, and scripts for the website.
README.md: This file provides an overview of the project, setup instructions, and usage details.
Setup Instructions
To set up this project locally, you’ll need to install the required dependencies and optionally set up Power BI to view the dashboard.

Prerequisites
Python 3.7+
Jupyter Notebook
Microsoft Power BI Desktop (for viewing and editing the Power BI dashboard)
Git (optional, for cloning the repository)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yahyayun1/Wikipedia-Gender-Dashboard.git
cd Wikipedia-Gender-Dashboard
Install required Python packages: This project relies on packages such as pandas, SPARQLWrapper, and numpy. You can install them using the following command:

bash
Copy code
pip install -r requirements.txt
Open Jupyter Notebook: Launch Jupyter Notebook to view and run the data collection and preprocessing files.

bash
Copy code
jupyter notebook
Usage
This project consists of three main components: data collection & preprocessing, the Power BI dashboard, and the website interface.

Data Collection & Preprocessing
Data Collection: Open Data Collection & Preprocessing/Data Collection.ipynb in Jupyter Notebook. This file includes code for collecting data from DBpedia and Wikidata using SPARQL queries. Run each cell to download and save data locally.

Data Preprocessing: After collecting the data, open Preprocessing.ipynb to preprocess it. This file cleans, transforms, and structures the data, creating final datasets (Final3.0.csv and non-binary2.0.csv) that will be used in the Power BI dashboard.

Power BI Dashboard
To view or edit the Power BI dashboard:

Open Microsoft Power BI Desktop.
Navigate to Microsoft Power BI Dashboard/ in this repository.
Open either WGD during usability study.pbix or updated WGD post usability study.pbix.
The first file is the initial version used during usability testing.
The second file incorporates improvements based on usability feedback.
The dashboard provides several visualizations, such as:

Gender distribution across subclasses.
Average age differences between male and female articles.
Gender representation trends over time.
Website Interface
The web interface is a lightweight HTML/JavaScript site that allows users to interact with the dashboard’s data through a browser. The website files are located in the WGD Website folder.

Open index.html in a web browser to view the site locally.
The interface provides access to the main visualizations and summaries, making it easier to share insights with users who may not have access to Power BI.
Contributing
We welcome contributions to improve the Wikipedia Gender Dashboard. To contribute:

Fork the repository.
Create a branch for your feature or fix:
bash
Copy code
git checkout -b feature-name
Commit your changes with clear messages:
bash
Copy code
git commit -m "Add feature description"
Push to your branch:
bash
Copy code
git push origin feature-name
Open a pull request to the main branch of this repository.
Please ensure all changes are well-documented and tested before submitting a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for more information.
