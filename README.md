# etl-project-02
# ETL Pipeline for Largest Banks by Market Capitalization

This project is an **ETL (Extract, Transform, Load)** pipeline that extracts data about the largest banks by market capitalization from Wikipedia, transforms the data by converting market capitalization values into multiple currencies (GBP, EUR, INR), and loads the processed data into a CSV file and a SQLite database.

---

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup and Installation](#setup-and-installation)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [Output](#output)
8. [License](#license)

---

## **Project Overview**
The project performs the following steps:
1. **Extract**: Fetches data about the largest banks by market capitalization from a Wikipedia page.
2. **Transform**: Converts the market capitalization values from USD to GBP, EUR, and INR using exchange rates from a CSV file.
3. **Load**: Saves the transformed data into a CSV file and a SQLite database.
4. **Query**: Executes sample queries on the SQLite database to demonstrate data retrieval.

---

## **Features**
- **Web Scraping**: Extracts data from a Wikipedia page using `BeautifulSoup`.
- **Data Transformation**: Converts market capitalization values into multiple currencies using exchange rates.
- **Data Storage**: Saves the processed data into a CSV file and a SQLite database.
- **Logging**: Logs the progress of the ETL process into a log file.
- **Query Execution**: Demonstrates how to query the SQLite database for insights.

---

## **Technologies Used**
- **Python**: Primary programming language.
- **Pandas**: For data manipulation and transformation.
- **BeautifulSoup**: For web scraping and HTML parsing.
- **SQLite3**: For database operations.

---
