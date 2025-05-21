# CombiningCSV
# 📊 CSV Combiner Script

This Python script reads all `.csv` files from a specified folder, combines them into a single DataFrame, and exports the result as a new CSV file. It is useful for aggregating datasets from multiple files into one unified dataset for analysis or reporting.

## 🧩 Features

- Automatically scans a folder for all `.csv` files.
- Checks for and skips empty or malformed files.
- Combines non-empty CSV files into one pandas DataFrame.
- Exports the final combined data to a new CSV file.

## 📂 File Structure
your_project_folder/
│
├── combined_data.csv # Output file (auto-generated)
├── your_csv_files/ # Place all CSVs here
└── combine_csv.py # This script

## 🛠️ Requirements

- Python 3.x
- `pandas`

Install pandas with:

```bash
pip install pandas

🚀 How to Use
Edit the paths in the script:
Replace the values of directory and the to_csv save path with your actual folder paths.

Run the script:

bash
Copy
Edit
python combine_csv.py
Check the output:
The combined CSV will be saved in your chosen output location.

✅ Output
A CSV file named combined_data.csv (or your preferred name) will be created containing the combined data from all valid CSV files in the folder.

📌 Notes
Empty or improperly formatted CSV files will be skipped with a warning.

Make sure all CSVs have a consistent structure (e.g., same columns) for best results.

🧠 Author
Created by @Metakrist
This script demonstrates data preprocessing and aggregation using pandas.
