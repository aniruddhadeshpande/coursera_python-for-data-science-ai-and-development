# 📌 Working with APIs, HTTP, and Web Scraping in Python

---

## 🔹 Simple APIs and Python

- **Simple APIs in Python** are easy-to-use interfaces that allow interaction with services, libraries, or data with minimal configuration.
- An **API (Application Programming Interface)** enables two software systems to communicate with each other.
- Using an **API library in Python** involves importing the library, making HTTP requests, and parsing responses to extract data.
- **Pandas API** can process and communicate with other software components.
- An **Instance** forms when you create a dictionary and use it with the `DataFrame` constructor to create a Pandas object.
- The **`head()` method** displays the first rows of a DataFrame (default is 5).
- The **`mean()` method** calculates and returns the mean of numerical columns.

---

## 🔹 REST APIs and HTTP

- **REST APIs** allow communication over the internet, enabling access to services such as data storage, AI, and more.
- **HTTP methods** are used to transmit data over the web.
- HTTP messages commonly include **JSON** data containing instructions.
- JSON responses are returned to the client by web services.
- **HTTP (HyperText Transfer Protocol)** transfers data between client and server.
- HTTP is widely used to implement **REST APIs**.
- An **HTTP response** contains metadata such as type and length of resource.
- A **URL (Uniform Resource Locator)** is used to locate resources on the web.
- A URL has three parts: **scheme**, **base URL**, and **route**.
- The **GET method** retrieves information from the server.
- Other HTTP methods include:
  - **POST** — submit new data
  - **PUT** — update existing data
  - **DELETE** — delete data
- The **response** contains HTTP version and body content.
- **Requests** is a Python library used to send HTTP/1.1 requests easily.
- GET queries can be modified using **query strings** to fetch specific data like name or ID.
- Multiple values can be retrieved from a URL through **query parameters**.

---

## 🔹 Time Series and Plotting

- Working with time-series data uses **Pandas time-series functions**.
- You can retrieve **daily candlestick data** and plot using **Plotly candlestick charts**.

---

## 🔹 Web Scraping in Python

- **Web scraping** extracts data from websites using libraries like `requests` and `BeautifulSoup`.
- **HTML** consists of textual content wrapped in **tags** (blue elements inside `<>`).
- HTML pages may also contain **CSS** and **JavaScript**.
- An HTML document forms an **HTML Tree** structure.
- **HTML tables** contain elements like `<table>`, `<tr>`, `<th>`, and `<td>`.
- **Pandas `read_html()`** can extract tabular data from web pages.
- **BeautifulSoup** helps parse and navigate HTML or XML documents.
- Parsing requires passing the document to the **BeautifulSoup constructor** to create a parse tree.
- BeautifulSoup represents HTML as **tree objects** with navigation methods.
- A **Navigable String** behaves like a Python string with additional BeautifulSoup support.
- **`find_all()`** searches for elements by tag name, attributes, or text.
- `find_all()` scans all descendants and returns results as a **Python iterable (like a list)**.

---

## 🔹 Working with File Formats

- **File formats** define how data is stored (e.g., `.txt`, `.csv`, `.json`, `.xml`, `.xlsx`).
- The **file extension** identifies the format and its corresponding tool.
- Python can read multiple file types, including **CSV, JSON, XML, and Excel**.
- **Pandas** can read CSV files and other formats using specific parsing functions.

---
