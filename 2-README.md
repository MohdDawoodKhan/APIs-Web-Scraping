# 🕸️ Web Scraping Lab
> 🧰 Tools Used: Python, Requests, BeautifulSoup

## Objectives

This lab helps you understand the basics of **web scraping** using Python. By completing this exercise, you will learn to:

- Send HTTP requests to retrieve HTML pages.
- Parse HTML content using BeautifulSoup.
- Extract specific elements such as links, images, and tables.
- Clean and structure extracted data.

---

## 🔹 Step-by-Step Instructions

### 1. **Set Up Environment**
- Import required libraries: `requests` and `BeautifulSoup`.
- Use `requests.get()` to fetch the HTML content of a webpage.
- Use `BeautifulSoup` to parse the content.

### 2. **View HTML Structure**
- Use `soup.prettify()` to print a well-indented view of the page’s HTML structure for easy navigation.

### 3. **Extract All Hyperlinks**
- Loop through all anchor (`<a>`) tags.
- Retrieve and print the `href` attribute (the link URL).

🟢 **Expected Output**: A list of all links on the page.

### 4. **Extract All Image Tags**
- Find all image (`<img>`) tags.
- Print out their `src` (image URL) and `alt` (description) attributes.

🟢 **Expected Output**: A list of image URLs and their alternative text.

### 5. **Scrape HTML Tables**
- Navigate to a sample webpage with tables (like W3Schools).
- Locate the table using attributes (e.g., ID or class).
- Loop through table rows and extract cell content.

🟢 **Expected Output**: A structured list of all rows in the table, including headers and data.

---

## 📊 Results Summary

- Successfully retrieved and parsed a live HTML page.
- Extracted:
  - Hyperlinks (`<a>` tags)
  - Images (`<img>` tags)
  - Table data (`<table>` structure)
- Cleaned and displayed data in list form for further processing or saving.

---


---

## ⚠️ Disclaimer

> This lab is for **educational purposes only**. Always ensure you are permitted to scrape a website by checking its `robots.txt` and terms of service.

