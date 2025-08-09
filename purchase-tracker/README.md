# Purchase Tracker — Python File I/O (Jupyter Notebook)

**Description:**  
A simple Jupyter Notebook project to demonstrate **file handling in Python**.  
It allows you to:
- Create a data file with sample purchases (`init_data()`).
- Append new purchases (`add_purchase()`).
- Read and list all purchases (`list_purchases()`).
- Calculate the total amount spent (`total_spent()`).

**Skills Demonstrated:**
- Using Python’s `open()` with different modes: `w` (write), `a` (append), `r` (read).
- Working with file paths using `pathlib`.
- Reading and writing text files.
- Basic data parsing and aggregation.
- Organizing code into reusable functions.

**How to Use in Jupyter Notebook:**
1. Run the **setup cell** to create the `data` folder and file path.
2. Run the **functions cell** to define all helper functions.
3. Use:
   ```python
   init_data()
   add_purchase("Coffee", 4.5)
   list_purchases()
   total_spent()
