# AI-Powered Data Intelligence Pipeline

An automated Python data pipeline that loads realistic messy sales data, cleans structural errors using Pandas, computes core statistics metrics, and uses an open-source AI model to generate executive business summaries directly into an exported Excel report.

## Features

- **Data Engine:** Automatically cleans currency formatting strings, filters out invalid negative quantities, and drops missing entries using `pandas` and `numpy`.
- **AI Integration:** Leverages the `g4f` framework to dynamically generate a 3-sentence executive summary based on the calculated mathematical outputs.
- **Corporate Export:** Generates a structured `.xlsx` spreadsheet containing the AI summary neatly positioned right above the data grid.

## Installation & Setup
Clone the repository and install the required dependencies:

```bash
pip install pandas g4f openpyxl
```

## How it Works

1. Run the Jupyter Notebook `ai-data-pipeline.ipynb`
2. The messy dataset will be processed, and statistics like total revenue and average price will be computer
3. The AI model creates a concise report
4. Open the generated `clean_data_file.xlsx` to view the finalized sheet.

## License & Distribution

This software has been distributed under the MIT license. See `LICENSE` for more information.
