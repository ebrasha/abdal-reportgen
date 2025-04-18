# 📊 Abdal ReportGen

<p align="center">
  <img src="scr.jpg" alt="Abdal ReportGen Screenshot">
</p>

[🇮🇷 Persian Documentation (مستندات فارسی)](README_FA.md)

## 📋 Overview
Abdal ReportGen is a powerful multi-format HTML report generator developed by Ebrahim Shafiei (EbraSha). It allows you to easily convert various data file formats into beautifully styled HTML reports with modern features.

## ✨ Features
- **🔄 Multi-format Support**: Process data from CSV, JSON, XML, Excel, and SQL files
- **🎨 Beautiful Reports**: Generate responsive HTML reports with Bootstrap styling
- **🌓 Dark Mode Support**: Built-in dark mode toggle for better readability
- **📱 Mobile-Friendly**: Fully responsive design works on all devices
- **🔍 Table Formatting**: Data presented in clean, sortable tables
- **⏱️ Timestamped Output**: Each report is saved with a unique timestamp
- **🛠️ Easy to Use**: Simple command-line interface

## 🚀 Getting Started
### Prerequisites
- Python 3.6 or higher
- Required Python packages: pandas, jinja2, matplotlib, openpyxl, lxml, xlrd

### Installation
```bash
# Clone the repository
git clone https://github.com/ebrasha/abdal-reportgen.git

# Install required packages using requirements.txt
pip install -r requirements.txt
```

### Usage
```bash
# Run with command-line argument
python main.py -f "path/to/your/datafile.csv"

# Or run interactively
python main.py
```

## 📁 Supported File Formats
- CSV (.csv)
- JSON (.json)
- XML (.xml)
- Excel (.xls, .xlsx)
- SQL (.sql with table named 'data')

## 📋 How It Works
1. The program reads your data file
2. Creates a timestamped output directory
3. Generates an HTML template with Bootstrap styling
4. Renders your data as a responsive HTML table
5. Adds dark mode functionality
6. Saves the complete report to the output directory

## 🔧 Example
When you run the program with a CSV file containing sales data:
```
python main.py -f "sales_data.csv"
```

The program will generate a complete HTML report with your data formatted in a clean, responsive table with dark mode support.

## ❤️ Donation
If you find this project helpful and would like to support further development, please consider making a donation:
- [Donate Here](https://ebrasha.com/abdal-donation)

## 🤵 Programmer
Handcrafted with Passion by **Ebrahim Shafiei (EbraSha)**
- **E-Mail**: Prof.Shafiei@Gmail.com
- **Telegram**: [@ProfShafiei](https://t.me/ProfShafiei)

## 📜 License
This project is licensed under the GPLv2 or later.
