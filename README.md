# WebScraping_WIKI

This project is a Python-based web scraping application that collects data from a target website, specifically scraping information about companies, including their rank, name, industry, revenue, and headquarters location.

## Features

- **Web Scraping**: The project uses Python to extract data from a web page, including details about companies such as:
  - Rank
  - Name
  - Industry
  - Revenue (in USD millions)
  - Revenue growth
  - Number of employees
  - Headquarters location
- **Data Processing**: The scraped data is cleaned and structured into a Pandas DataFrame for further analysis.

## Tools and Libraries

The following tools and libraries are used in this project:

- **Python**:The main programming language used for the project.
- **BeautifulSoup**: Used to parse the HTML content and extract relevant data.
- **Pandas**: Used for data manipulation and structuring the scraped information.
- **Requests**: To send HTTP requests to the website and retrieve content.

## Installation

To run this project locally, you need to have Python installed along with the required libraries. Follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/ZakariaIqbal/WebScraping_WIKI.git

2. Install the dependencies:
   
  ```bash
  pip install -r requirements.txt
  ```
3. Run the notebook:
   
  ```bash
  jupyter notebook
  ```
## Project Structure 

  ```bash
  .
  ├── Web_Scraping_Project.ipynb  # Jupyter Notebook
  ├── requirements.txt            # Dependencies
  └── README.md                   # Documentation

  ```


