# CSV to PDF Generator

## Description
This Python application reads data from a CSV file and generates a well-formatted PDF document displaying the CSV content in a table. The application utilizes `FPDF` for PDF generation, applying custom styles such as colors and fonts to create a polished output.

## Installation 
1. Clone the repository:
   ```bash
   git clone https://github.com/JordanVF/CSVPDF.git
2. Navigate to the project directory: 
```bash
cd CSVPDF
```
3. Install the required dependencies:
```bash
pip install fpdf
```
4. Ensure you have the CSV file countries.txt with the required data in the directory
 
## Usage
1. Run the application
2. The script will read the contents of the countries.txt file (a CSV format file) and create a PDF document containing the data displayed in a table.
3. The generated PDF will be saved as table.pdf in the PDF Generation/CSV Document Manipulation directory.

## How it works
- CSV Reading: The application opens the countries.txt CSV file and reads its content using Python’s built-in csv module.
- Table Generation: The application uses FPDF to create a table in the PDF. It applies custom styling, such as setting the color and font weight of headings and rows.
- PDF Output: The output is a structured PDF containing the CSV data in tabular form with specified column widths, heading styles, and aligned text.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

