Overview: Automated Report Generation Script
This Python script automates the process of reading data from a CSV file, analyzing it, and generating a formatted PDF report. It is designed to streamline the workflow of data reporting and can be customized for various datasets.

Features
File Input: Reads structured data from a CSV file.
Data Analysis:
Calculates key statistics such as the total number of rows and columns.
Provides descriptive statistics (mean, min, max, etc.) for numeric columns.
PDF Report Generation:
Formats the data analysis into a visually appealing PDF.
Includes a summary and a detailed table of column-wise statistics.
Customizable:
File paths, analysis logic, and PDF layout can be adjusted to fit specific requirements.
How It Works
Input:

A CSV file containing the dataset (e.g., data.csv).
File path is specified in the script or passed dynamically.
Processing:

The script uses the pandas library to load and analyze the data.
Descriptive statistics are computed using the describe() method.
Output:

A PDF report is generated using the ReportLab library.
The report includes:
Title and summary of the dataset.
A table displaying key statistics for each column.
Requirements
Python 3.x
Libraries: pandas, reportlab
Install dependencies using:
bash
Copy
Edit
pip install pandas reportlab
Usage
Place the CSV file in the desired location (e.g., C:/Users/lenis/Downloads/data.csv).
Update the input_file and output_file variables in the script to match the file paths.
Run the script:
bash
Copy
Edit
python script_name.py
The generated PDF report will be saved at the specified output path.
Customization
File Paths: Modify the input_file and output_file variables for different datasets and output locations.
Analysis Logic: Adjust the analyze_data function to include additional metrics or filters.
PDF Layout: Customize fonts, colors, and table styles in the generate_pdf_report function
