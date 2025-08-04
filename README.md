# Web-Scraping-Data-Entry-Uipath
This RPA project is designed to automate the process of extracting business-related data from websites, processing that data, and saving it in a structured format for analysis or reporting.

The automation begins by reading configuration details (like the target URL, search parameters, and file paths) from a centralized Excel file. It then launches a browser, navigates to the website, searches for specified content (e.g., businesses in a location), and scrapes structured data such as names, addresses, phone numbers, or ratings. After capturing, the data is cleaned, formatted, and saved to an Excel, CSV, or database system.
The project follows modular design principles — separating configuration, browser automation, data extraction, and data processing into distinct workflows — making it highly reusable and scalable.
