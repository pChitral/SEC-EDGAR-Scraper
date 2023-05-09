# SEC Filings Analysis
This Python script retrieves and analyzes financial data from the SEC's EDGAR database. It retrieves metadata on a company's filings, company facts data, and financial concept data for a given set of financial statements.

# Dependencies
This script requires the following Python modules to be installed:

requests
pandas
matplotlib

# Usage
1. Clone this repository or download the code as a ZIP file and extract it.

2. Open a command prompt or terminal window and navigate to the directory where the code is located.

3. Run the script by entering the following command:

```python
python sec_filings_analysis.py
```
4. The script will retrieve data for the first company listed in the SEC's company_tickers.json file. You can modify the script to retrieve data for a different company by changing the index number used to retrieve the company's CIK.

5. The script will output information on the company's filings, company facts data, and financial concept data. It will also create a plot of the company's assets over time using the data from the 10-Q forms.

# Credits
This script was created by Chitral Patil. It uses data from the SEC's EDGAR database.
