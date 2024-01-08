# Excel-to-SQL Converter

## Overview
The Excel-to-SQL Converter is a Python tool designed to read data from an Excel file and generate executable SQL commands. This tool simplifies the process of migrating data from Excel spreadsheets to SQL databases.

## Features
- Converts Excel data to SQL commands.
- Supports various SQL databases (e.g., MySQL, PostgreSQL, SQLite).
- Easy-to-use and customizable.

## Requirements
- Python 3.x
- openpyxl library (`pip install openpyxl`)

## Usage
1. **Install Dependencies:**
   ```bash
   pip install openpyxl
   ```

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/s4hil/excel-to-sql.git
   cd excel-to-sql
   ```

3. **Run the Converter:**
   ```bash
   python main.py
   ```

4. **Move the script:**
        Move the excel file into the directory containing the script.

5. **Import SQL Data:**
   Execute the generated SQL file using your preferred SQL client or command line tool to import the data into your database. An output.txt file will contain the output.


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute and report issues on [GitHub](https://github.com/s4hil/excel-to-sql).