# **Web Scraping Project: Data Extraction from Wikipedia**

## **Project Overview**
This project demonstrates how to scrape data from a live webpage: [Wikipedia's List of Largest Companies in the United States by Revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue). Using **Python** and the **Pandas** library, I extracted the table titled **"List of the largest public / publicly traded companies"** and converted it into a well-organized **CSV file** for analysis.

---

## **Objectives**
- 📝 **Extract information** from a live webpage with Python.
- 🛠️ **Parse and process** the HTML to gather relevant data.
- 📂 **Export** the data into a structured CSV format.

---

## **Tools and Technologies Used**
- 🐍 **Python**: The primary programming language for this project.
- 🌐 **BeautifulSoup**: For parsing HTML content and navigating the webpage.
- 🔗 **Requests**: To fetch the HTML of the target webpage.
- 📊 **Pandas**: For data manipulation and CSV export.
- 🖥️ **Jupyter Notebook**: For interactive code development and testing.

---

## **Project Workflow**
1. **Fetching Web Content**:
   - Employed the `requests` library to retrieve the HTML content from the Wikipedia page.

2. **HTML Parsing with BeautifulSoup**:
   - Analyzed the webpage structure to locate the desired table.
   - Extracted the `<table>` element containing the relevant data.

3. **Data Extraction**:
   - Retrieved the **header** (`<th>` elements) and **row** (`<tr>` elements) data.
   - Cleaned the extracted data to ensure uniformity and accuracy.

4. **Data Transformation**:
   - Converted the raw data into a **Pandas DataFrame** for easier manipulation.

5. **Exporting Data**:
   - Exported the final DataFrame into a **CSV file** for further analysis.

---

## **Skills Developed**
This project enhanced my proficiency in the following areas:

### 🔍 **1. Web Scraping**
   - Navigating HTML structure to identify and extract specific data.
   - Using **BeautifulSoup** to parse and extract content from webpages.

### 🔄 **2. Data Wrangling**
   - Transforming raw HTML data into structured formats.
   - Cleaning and handling missing or inconsistent data.

### 💻 **3. Python Programming**
   - Writing reusable and efficient Python code for data scraping.
   - Leveraging libraries like `requests`, `BeautifulSoup`, and `Pandas` for seamless execution.

### 📊 **4. Data Analysis Techniques**
   - Manipulating data with **Pandas** to generate meaningful insights.
   - Exporting clean data to **CSV format** for future use.

### 🛠️ **5. Problem-Solving and Debugging**
   - Troubleshooting issues like inconsistent data formatting and dynamic web elements.

---

## **Results**
The data was successfully scraped and exported as a **CSV file**, containing:
- **Rank**
- **Company Name**
- **Industry**
- **Revenue (in millions USD)**
- **Revenue Growth**
- **Number of Employees**
- **Headquarters Location** 
