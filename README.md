# Indian Government Schemes Scraper

A robust web scraping tool to extract structured data from Indian government scheme pages, including eligibility criteria, application processes, FAQs, and more. Built with Python and Selenium for handling dynamic content. Data is collected from the official [Myscheme.gov.in](https://www.myscheme.gov.in) website.


![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Selenium](https://img.shields.io/badge/Selenium-4.8%2B-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.5%2B-green)

## 📋 Project Overview

This tool scrapes the following sections from Indian government scheme pages:
- **Scheme Details** (Name, Link)
- **Scheme Type** (State/Central)
- **Application Process** (Online/Offline steps)
- **Documents Required**
- **FAQs**
- **Sources & References**
- **Eligibility Criteria**

The scraper is designed to handle dynamic content using Selenium and implements robust error handling with retries and a checkpoint system, so that the process can be resumed if interrupted.

## 🛠️ Features

- **Modular Design**:  
  Separate functions are implemented for each section to be scraped, ensuring a clean and maintainable codebase.

- **Robust Error Handling**:  
  Implements retries with exponential backoff for handling transient network issues or dynamic content loading delays.

- **Checkpoint System**:  
  Intermediate results are saved to a checkpoint file, allowing the scraper to resume from the last processed scheme if interrupted.

- **Dynamic Content Handling**:  
  Uses Selenium with explicit waits to ensure that JavaScript-rendered content is fully loaded before extraction.

- **Excel Output**:  
  Extracted data is consolidated and saved in `.xlsx` format for easy analysis and sharing.

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or later
- [Selenium](https://www.selenium.dev/)
- [pandas](https://pandas.pydata.org/)
- [tqdm](https://github.com/tqdm/tqdm)
- [webdriver_manager](https://github.com/SergeyPirogov/webdriver_manager)

## Install the required packages using pip:

pip install selenium pandas tqdm webdriver_manager


## 🤝 Contributing
Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request. Please follow standard coding conventions and include appropriate tests if applicable.

## 📧 Contact
For questions or feedback, feel free to reach out:

<p align="center"> <strong>📬 Let’s Connect!</strong> <br> <a href="https://www.linkedin.com/in/rishikesh-borah-3b245284/" target="_blank" style="display: inline-block; background-color: #0077B5; color: #fff; padding: 8px 16px; margin: 5px 10px; text-decoration: none; border-radius: 4px;">LinkedIn</a> | <a href="mailto:rishikesh.borah4@gmail.com" target="_blank" style="display: inline-block; background-color: #D44638; color: #fff; padding: 8px 16px; margin: 5px 10px; text-decoration: none; border-radius: 4px;">Email</a> </p>
