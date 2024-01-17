# 5P1D3R-GDORKER
## Description
The 5P1D3R-GDORKER is a Python-based command-line utility that leverages Google search operators to perform advanced searches. 
It's designed to help users efficiently gather information from the web by using specialized search queries.

## Features
Utilizes Google search operators like filetype:, site:, inurl:, etc.
Allows setting the number of results to retrieve.
Outputs the results to a text file for easy review and analysis.

## Requirements
Python 3.x
Libraries: googlesearch, urllib, termcolor, argparse, subprocess
## Installation
Clone the repository:
`git clone https://github.com/0X5P1D3R/5P1D3R-GDORKER`
Install the required libraries:
`pip install googlesearch-python termcolor`
Usage
Run the script with the desired parameters:

`python 5P1D3R-GDORKER.py -o [operator] -d [domain] -n [number_of_results]`
Example:

`python 5P1D3R-GDORKER.py -o filetype:pdf -d example.com -n 5`
The results will be saved in a text file named [domain].txt.

Supported Operators
--daterange: Return results in a specified range.
--link: Find pages that link to the target domain.

## Contributing
Contributions to the Google Dorking Tool are welcome.

## Disclaimer
This tool is for educational and ethical testing purposes only. The author is not responsible for misuse or damage caused by this tool.
