# alu_regex-data-extraction-NathanaellaHirwa
Project Overview
This project is a Python script for data extraction using regular expressions (regex). It reads text from a file and extracts useful patterns such as email addresses, URLs, phone numbers, credit card numbers, HTML tags, hashtags, currency values, and time formats. It's a helpful tool for text mining, data cleaning, or preparing content for further processing.

What the Script Does
The script performs pattern recognition by using regular expressions to find and return matches in a given text. It includes dedicated functions for each type of pattern you might encounter in real-world documents, such as:

Email addresses (e.g., john.doe@example.com)

Website URLs (e.g., https://example.com)

Phone numbers in various formats (e.g., (123) 456-7890, 123-456-7890)

Credit card numbers (e.g., 1234-5678-9012-3456)

Hashtags used in social media (e.g., #AI, #Python)

Currency values (e.g., $1,234.56)

Times in 12-hour or 24-hour format (e.g., 10:30 AM, 23:45)

Input File
The script reads from a file named index1.txt, which must be placed in the same directory as the Python script. This file should contain the text you want to analyze. If the file is missing, the script will print an error and exit gracefully.

How It Works
Each pattern is defined using a regular expression and encapsulated in its own function (like extract_emails, extract_urls, etc.). The main function loads the text, runs all extraction functions, and prints the results to the terminal.

