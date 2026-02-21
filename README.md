 🛒 Amazon Laptop Data Scraping & Analysis Project

 📌 Project Overview
This project focuses on scraping laptop data from Amazon India, cleaning the extracted data, and preparing it for analysis.

The goal is to extract meaningful product information such as price, processor type, RAM, storage, ratings, discounts, and more using Python.



 🛠 Technologies Used
- Python
- Pandas
- Requests
- BeautifulSoup
- Regular Expressions (re)
- Jupyter Notebook



 📥 Data Extraction
The scraping process extracts the following details:

- Product Title
- Price
- Brand
- Processor
- RAM
- Storage (SSD/HDD)
- Windows Version
- Rating
- Color
- Discount Percentage
- Screen Size

Multiple pages were scraped to collect laptop listings.



 🧹 Data Cleaning
After scraping, the dataset was cleaned by:

- Extracting Product Name from Title
- Removing unnecessary characters
- Handling missing values
- Standardizing column formats
- Reordering columns
- Removing duplicates (if any)

Final cleaned dataset:
`amazon_laptop_cleaned.csv`



 📊 Project Workflow

1. Send request to Amazon search page
2. Parse HTML using BeautifulSoup
3. Extract product attributes using regex
4. Store data in list of dictionaries
5. Convert into Pandas DataFrame
6. Clean and structure dataset
7. Export to CSV



 🚀 Conclusion
This project demonstrates:

- Real-world web scraping
- Data extraction using regex
- Data cleaning using Pandas
- Building structured datasets from unstructured HTML

