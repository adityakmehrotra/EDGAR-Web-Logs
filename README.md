# EDGAR-Web-Logs

## Overview

This project is dedicated to analyzing the vast amount of data generated by the EDGAR (Electronic Data Gathering, Analysis, and Retrieval system) web logs, which record web requests to the SEC’s EDGAR database by users worldwide. These logs are not only extensive—often amounting to 2 GB uncompressed data per day—but also contain anonymized but valuable user behavior data.

The primary goal is to develop tools in Python for extracting and processing information from these logs to understand better the behavior of users, particularly investment firms. This analysis can provide insights into which companies or industries hedge funds may be considering for investment and whether they rely more on automated or manual research for their trading decisions.

## Project Components

- **edgar_utils.py**: A Python module for extracting data from the EDGAR filings.
- **main.ipynb**: A Jupyter notebook used for the analysis of user behavior based on the data extracted.

## Motivation

Understanding the behavior of users who access the EDGAR database can offer predictive insights into market trends and investment patterns. This project aims to uncover these patterns by analyzing how different documents are accessed and correlated with investment success.

## Installation

Clone this repository to your local machine using:
  ```markdown
  git clone https://github.com/adityakmehrotra/EDGAR-Web-Logs.git
  ```

Navigate to the project directory:
  ```markdwon
  cd EDGAR-Web-Logs
  ```

Install the required Python packages:
  ```python
  pip install -r requirements.txt
  ```

## Usage

Open the main.ipynb notebook in a Jupyter environment to view the analysis:
  ```bash
  jupyter notebook main.ipynb
  ```

## Data

The data used in this project consists of anonymized logs from the EDGAR database, which include user interactions such as the types of filings accessed. These logs are structured to provide insights into user demographics and behavior without compromising individual privacy.

## Contributing

Contributions to this project are welcome. Please fork the repository, make your changes, and submit a pull request for review.


## Acknowledgments

- SEC for providing the EDGAR logs.
- All contributors who have worked on analyzing public data for academic and professional purposes.

### Last Updated
04/13/2024
