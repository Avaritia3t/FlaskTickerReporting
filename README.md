# Ticker Reporting (v1)

## Description
A simple Flask application to fetch and display stock prices. API integration to query some individual (pre-selected) stocks. 

## Prerequisites
- Python 3.9
- Other dependencies are listed in `requirements.txt`

## Installation & Setup
1. Clone the repository: `git clone <repo-url>`
2. Navigate to the repo: `cd <repo-name>`
3. Install the requirements: `pip install -r requirements.txt`

## Usage
To run the application, use the command: `python ticker_reportingv1.py`

### API Endpoints
- `/`: Home page.
- `/stocks`: Stocks display page.
- `/api/latest_stocks`: Fetches the latest stock prices. Accepts an optional `ticker` parameter.
- `/stock/<ticker>`: Fetches the price of the specified ticker.

## Contributing
Feel free to raise issues or submit pull requests. Future developments include more robust front-end development, expanded API endpoints, improved polling logic, concurrent db read/write, and so on. Intended to be an on-going portfolio project. Please feel free to reproduce/contribute at your leisure.

## License
This project is licensed under the MIT License.
