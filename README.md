# NLP for Network Analysis

This project focuses on utilizing Natural Language Processing (NLP) techniques for network analysis, particularly in the context of understanding relationships within Moroccan companies, CEOs, other organizations, and investors.

## Application Web

The project includes a web application interface that allows users to interact with the NLP-driven network analysis tool.

## Topics to Study

The key topics for study within this project include:

- Moroccan companies
- CEOs
- Relations among entities
- Other organizations
- Investors

## Project Structure

- **.data/**: This folder contains the raw data files in JSON format that were scraped from various sources.
    - company1.json
    - company2.json
    - ...
    - companyN.json
- **output/**: This folder contains the cleaned and manipulated data files in JSON format.
    - output_new.json
- **notebooks/**: This folder contains Jupyter notebooks used for data cleaning, manipulation, and analysis.
    - data_cleaning_and_manipulation.ipynb
    - json_to_graph.ipnyb
    - ...
    - data_analysis.ipynb
- **requirements.txt**: This file lists all the Python packages required to run the code in this project.
- **README.md**: This file provides an overview of the project, including the project structure, project goals, and instructions for running the code.


## Wikipedia Scraping

To gather data for analysis, the project implements a Wikipedia scraping mechanism. This involves:

- Identifying relevant pages related to the specified topics
- Collecting data about these topics in JSON format for further processing

## Building the Graph

Once the data is collected, the next step involves constructing a graph database. This process includes:

- Transforming the JSON data into a structured graph format
- Building the network graph using the collected data
- Visualizing the constructed graph for better understanding and interpretation

## Analyzing the Graph

With the graph constructed, the project facilitates analysis to uncover insights such as:

- Influence of different entities within the network
- Importance of nodes based on various metrics
- Relations between different entities and their implications

The combination of NLP techniques and network analysis provides a powerful tool for understanding complex relationships within the specified domains.

## Conclusion

By leveraging NLP and network analysis methodologies, this project offers valuable insights into the dynamics of relationships among Moroccan companies, CEOs, organizations, and investors. The web application interface enhances accessibility and usability, making it a practical tool for researchers and professionals in various fields.

## Contributors

- [Abdessamad ANSSEM](https://github.com/abdoanss)
- [Oussama OUZAKRI](https://github.com/Oussama-OUZAKRI)
- Abdelkarim AABDANE

Feel free to contribute by forking the repository and creating pull requests!
