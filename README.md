
# Earnings Data Fetcher
## Requirements
- Python 3
- `requests` library
- `pandas` library

## How It Works
1. The script constructs URLs for the Earnings Whispers calendar and API endpoints using a specified date.
2. It sends a GET request to the API endpoint with the appropriate headers.
3. The response is parsed as JSON and the earnings data is extracted.
4. The script prints out the company name and the date of the earnings report.
5. It also collects the tickers, estimated EPS for Q1, and estimated revenues for Q1 in separate lists.
6. Finally, it creates a pandas DataFrame with the collected data.

## Example Output
The script will output the company names and their earnings report date, followed by a detailed JSON response for each company. Additionally, it will create a DataFrame with the tickers, estimated EPS, and estimated revenues.
{'ticker': 'DRI',
 'company': 'Darden Restaurants, Inc.',
 'total': 17,
 'nextEPSDate': '2023-12-15T00:00:00',
 'releaseTime': 1,
 'qDate': '11/2023',
 'q1RevEst': 2740000000.0,
 'q1EstEPS': 1.71,
 'confirmDate': '2023-11-16T16:19:18.39',
 'epsTime': '2023-09-21T07:00:00',
 'quarterDate': '2023-11-30T00:00:00',
 'qSales': 2486.5}
Best,
Ali
