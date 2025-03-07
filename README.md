# AI Overview Checker

## Description

This script uses the DataForSEO API to check if an AI Overview appears on Google search result pages for a list of keywords. It extracts references from the AI Overview section, including:

- Source

- Domain

- URL

- Title

- Text

and saves the results to a CSV file.

## Features

- ✅ Fetches Google SERP results via the DataForSEO API.
- ✅ Identifies if an AI Overview is present.
- ✅ Extract references from the AI Overview.
- ✅ Saves results to CSV format.
- ✅ Supports batch processing from a keyword list.

## Requirements

Python (3.6+)

DataForSEO API credentials

Required Python libraries:

- requests

- csv

- json

- time

## Installation

Clone this repository:

`git clone https://github.com/yourusername/ai-overview-checker.git
cd ai-overview-checker`

Install dependencies:

` pip install requests `

## Usage

Set up API credentials in the script:

`api_username = "your_username"`
`api_password = "your_password"`

Prepare a keyword list in keywords.csv (one keyword per line).

Run the script:

`python check_ai_overview.py`

Output: Results are saved in ai_overview_results.csv.

## Example Output (CSV Format)

Keyword,Source,Domain,URL,Title,Text

## Notes

The script makes a request to DataForSEO for each keyword, so ensure your API plan supports the required number of requests.

A `time.sleep(2)` delay is included to prevent API rate limits.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author
[Svet Petkov GitHub] (https://github.com/svetoslavseo/google-ai-overview-checker)
[Svet Petkov SEO website ](https://github.com/youractualusername](https://svetoslav.co.uk/)

