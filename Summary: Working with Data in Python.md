
### 📌 **File Handling in Python**

* Python uses the `open()` function to read and write files, providing access to file contents and specifying file modes:

  * `r` → read
  * `w` → write (overwrite)
  * `a` → append
* To read a file, Python uses the `open()` function with mode `r`.
* Python uses the `with open()` statement to read and process files safely (auto-closes file after use).
* To edit or overwrite a file, Python uses the `open()` method with mode `w`.
* To write to a file, Python uses `open()` with mode `w`.
* In Python, `a` indicates that data will be **appended** to the file instead of replacing it.
* The newline character `\n` indicates that output should start on a new line.
* Python provides various methods to **read and print lines** from a file.

---

### 📌 **Pandas (Data Analysis Library)**

* **Pandas** is a powerful Python library for **data manipulation and analysis**, working with structured data like **DataFrames and Series**.
* You import Pandas using the `import` command, typically:

  ```python
  import pandas as pd
  ```
* The `as` keyword provides a **short alias**, such as `pd`.
* Pandas uses **DataFrames (`df`)** to read, store, and manipulate data.
* A DataFrame consists of **rows and columns**.
* You can create new DataFrames from selected columns of an existing DataFrame.
* Data in a DataFrame can be **modified, analyzed, and saved in different formats** (CSV, Excel, etc.).
* The `unique()` method is used to get **unique elements** from a column.
* You can assign Boolean values to DataFrame columns using comparison operators.
* You can save a modified DataFrame as a **new DataFrame**.

---

### 📌 **NumPy (Numerical Python Library)**

* **NumPy** is a Python library for **numerical and matrix operations**, offering efficient **multidimensional arrays** and math functions.
* NumPy is a **foundation for Pandas**, providing its core array capabilities.
* A NumPy array (or **ND array**) is similar to a list but is fixed in size and holds elements of the **same type**.
* A **one-dimensional NumPy array** is a linear sequence of values, optimized for fast numeric operations.
* You can access NumPy elements using **indexing**.
* Use:

  * `dtype` → to get the data type of array elements
  * `size` → to get the total number of elements
  * `ndim` → to get the number of array dimensions
* NumPy supports **indexing and slicing**, similar to lists.
* **Vector addition** and subtraction are common operations.
* NumPy code executes **faster than standard Python**, especially with large data.
* **Scalar multiplication** multiplies each array element by a scalar.
* **Hadamard product** → element-wise multiplication of two arrays of the same shape.
* **Dot product** → sum of element-wise products (used in vectors & matrix math).
* NumPy often pairs with **Matplotlib** for data visualization.
* A **two-dimensional NumPy array** represents data in **rows and columns**.
* The `shape` attribute represents array **dimensions (rows, columns)**.
* The `size` attribute returns the **total number of elements**.
* You can access array elements using **row and column indexing**.
* Scalars can be used to multiply all array elements.


### ✅ **Glossary (Markdown Version)**

### **.csv file**
A `.csv` (Comma-Separated Values) file is a plain text format for storing tabular data, where each line represents a row and commas separate column values.

### **.txt file**
A `.txt` (Text) file contains plain text without special formatting, useful for basic readable and editable content.

### **Append**
To append means to add data to the end of an existing object, such as a list or an open file.

### **Attribute**
An attribute in Python is a property or characteristic of an object, accessed using dot notation.

### **Broadcasting (NumPy)**
Broadcasting allows NumPy to perform element-wise operations on arrays of different shapes by automatically expanding dimensions where possible.

### **Component**
A component in a NumPy array refers to an individual element accessed via indexing.

### **Computation**
Computation in NumPy refers to performing numerical and mathematical operations on arrays and matrices.

### **Data analysis**
The process of inspecting, transforming, and interpreting data to discover insights and support decision-making.

### **DataFrame**
A DataFrame in Pandas is a two-dimensional labeled data structure of rows and columns, similar to a table.

### **Dependencies**
Dependencies are external libraries (such as NumPy) that Pandas relies on for core functionality.

### **File attribute**
Metadata or properties associated with a file at the operating system level.

### **File object**
An object in Python representing an open file, used for reading or writing operations.

### **Grid**
A two-dimensional structure made of rows and columns, often used for tabular or coordinate data.

### **Hadamard Product**
An element-wise multiplication of two arrays or matrices of the same shape.

### **Importing Pandas**
Using `import pandas as pd` to load the Pandas library into a Python script.

### **Index**
A position used to access elements in sequences such as lists, arrays, or strings.

### **Libraries**
Collections of pre-written modules that provide reusable functions and tools.

### **Linspace**
A NumPy function that generates evenly spaced values over a specified range.

### **NumPy**
A fundamental Python library for numerical computing, supporting multi-dimensional arrays and mathematical operations.

### **One-dimensional NumPy array**
A linear collection of elements stored in a single axis.

### **Open function**
The Python `open()` function is used to open files for reading, writing, or appending.

### **Pandas**
A powerful Python library for data manipulation and analysis, built on top of NumPy.

### **Pandas library**
Refers to the modules and tools within Pandas that support data analysis workflows.

### **Plotting Mathematical Functions**
Using libraries like Matplotlib to visualize equations and numeric data.

### **Shape**
A NumPy array attribute that returns its dimensions (rows, columns).

### **Slicing**
Extracting a subset of an array using index ranges.

### **Two-dimensional NumPy array**
An array with rows and columns, similar to a matrix.

### **Universal Functions (ufuncs)**
NumPy functions that operate element-wise on arrays, enabling fast vectorized computation.

### **Vector addition**
Adding corresponding elements across vectors to produce a new vector.

### **Visualizations**
Creating graphical representations such as plots, charts, and graphs to communicate data insights.

---
```

