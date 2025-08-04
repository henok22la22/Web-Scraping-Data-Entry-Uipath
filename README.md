# Web-Scraping-Data-Entry-Uipath
This RPA project is designed to automate the process of extracting business-related data from websites, processing that data, and saving it in a structured format for analysis or reporting.

The automation begins by reading configuration details (like the target URL, search parameters, and file paths) from a centralized Excel file. It then launches a browser, navigates to the website, searches for specified content (e.g., businesses in a location), and scrapes structured data such as names, addresses, phone numbers, or ratings. After capturing, the data is cleaned, formatted, and saved to an Excel, CSV, or database system.

The project follows modular design principles — separating configuration, browser automation, data extraction, and data processing into distinct workflows — making it highly reusable and scalable.

 # Use Case
This solution is ideal for businesses or professionals who frequently need to gather structured business data from public websites but want to eliminate repetitive, manual work. It's useful in the following scenarios:
🔍 Typical Use Cases:
•	Lead Generation: Scrape contact information for businesses from online directories or listing sites.
•	Market Research: Gather competitor or vendor data like locations, services, and ratings.
•	Real Estate or Job Listings: Extract postings for properties, rentals, or job openings from aggregator sites.
•	Healthcare Listings: Collect lists of clinics, hospitals, or specialists in certain regions.
•	Data Aggregation: Collect and unify data from multiple online sources for internal analysis or reporting.

# Project Steps (Summary) 

    Load Configuration

    Open Browser

    Navigate to Website

    Check UI Element

    Search Data

    Extract Data

    Get Data

    Transform Data

    Save to Storage

    Log Actions & Errors Throughout

  # Technologies & Categories

    RPA Platform: UiPath Studio

    Automation Type: Web Scraping, Data Entry

    Data Source: Website (via browser)

    Data Output: Excel / CSV / Database

    Configuration Management: Excel (Config.xlsx)

    UI Automation: Selectors, Check App State, Use Browser

    Error Handling: Try-Catch Blocks, Logging (LogMessage.xaml)

    Data Processing: DataTable, Assign, Filter, ForEach Row

    Workflow Design: Modular XAMLs (Init, OpenBrowser, Extract, Process)



    
