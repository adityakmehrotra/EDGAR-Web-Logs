# EDGAR-Web-Logs

## Overview

In the US, public companies need to regularly file various statements and reports to the SEC's (Securities and Exchange Commission) EDGAR database. EDGAR data is publicly available online; furthermore, web requests to EDGAR from around the world are logged and published. EDGAR logs are huge. Logs for just one day might be about 250 MB compressed as a .zip (or 2 GB uncompressed!).

I'll develop tools to extract information from the filings stored in EDGAR (this will be done in a Python module, edgar_utils.py) and we'll use those tools to analyze user behavior in main.ipynb.

## Conclusion

The EDGAR logs are supposedly anonymized (with the last three docs left), but we can still tell where the users live and what they're looking at.

By connecting the filing information with the logs, we can learn a lot about the behavior of the investment firms which use the database - for example, we might learn which companies (or industries) a hedge fund might be considering investing in, and the extent to which it relies on automated vs manual research in its trading.

Others have used this same data to make good guesses about what docs various hedge funds and others are looking at, then correlate that with success. For those interested in the nitty-gritty details of what could be done with this data, take a look at this early-stage work: Hedge Funds and Public Information Acquisition.

## Last Updated: 04/12/2024
