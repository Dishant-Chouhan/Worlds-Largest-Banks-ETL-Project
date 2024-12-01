# World's Largest Banks ETL Project

## **Overview**
This project focuses on performing ETL (Extract, Transform, Load) operations on data about the world's largest banks. It demonstrates how to scrape data from the web, process it, and store it in multiple formats for analysis.

---

## **Project Features**
1. **Data Extraction**:
   - Scrapes information about the largest banks globally from an archived Wikipedia page.
   - Extracts bank names and market capitalization in USD billions.

2. **Data Transformation**:
   - Converts market capitalization values into GBP, EUR, and INR using exchange rates from a CSV file.
   - Ensures all data is rounded and formatted for consistency.

3. **Data Loading**:
   - Saves the transformed data to a CSV file for easy sharing and visualization.
   - Stores the data in an SQLite database for efficient querying.

4. **Data Insights**:
   - Queries the database to:
     - View all data.
     - Calculate the average market capitalization in GBP.
     - List the top 5 banks by name.

5. **Logging**:
   - Logs progress and errors at every stage of the ETL pipeline.

---

## **Technologies Used**
- **Python Libraries**:
  - `requests`, `BeautifulSoup`, `pandas`, `sqlite3`, `numpy`
- **Data Sources**:
  - [Wikipedia (archived)](https://web.archive.org/web/20230908091635/https://en.wikipedia.org/wiki/List_of_largest_banks)
  - Local CSV file for exchange rates.

---



## **Project Outputs**
1. **CSV File**:
   - Processed data saved as `Largest_banks_data.csv`.

2. **Database Table**:
   - Data stored in `Banks.db` under the table `Largest_banks`.

3. **Insights from Queries**:
   - View all bank data.
   - Calculate average market capitalization in GBP.
   - Retrieve names of the top 5 banks.

---

## **Future Enhancements**
- Automate periodic updates using live exchange rates.
- Extend data extraction to include additional attributes like country and revenue.
- Integrate a web-based dashboard for visualization.

---

## **Acknowledgments**
- Wikipedia for the archived page on the largest banks.
- Python and its community for the powerful libraries.


