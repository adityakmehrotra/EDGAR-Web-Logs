# EDGAR-Web-Logs

## Overview

In the US, public companies need to regularly file various statements and reports to the SEC's (Securities and Exchange Commission) EDGAR database. EDGAR data is publicly available online; furthermore, web requests to EDGAR from around the world are logged and published. EDGAR logs are huge. Logs for just one day might be about 250 MB compressed as a .zip (or 2 GB uncompressed!).

I'll develop tools to extract information from the filings stored in EDGAR (this will be done in a Python module, edgar_utils.py) and we'll use those tools to analyze user behavior in main.ipynb.
