# AbuseIPDB-Bulk IP Reporting Script

[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/hibare)

Python script to report bad IPs to AbuseIPDB in bulk in one go.

## Install requirements
Use following command to install all dependencies
``` 
pip install -r requirements.txt 
```

## Other requirements
To use AbuseIPDB reporting API, you need an API key. Get it by creating an account at [AbuseIPDB](https://www.abuseipdb.com).

## Usage
- Create a input file with all IP addresses one per line.
- Use following command to run script.
```
python3 abuseIPDB.py -k <AabuseIPDB API key> -f <input filename>
```
both options are required.
- Use -h option for help.
- Current submission status will be printed on the screen.
- An output file will be create with name *AbuseIPDB_Submission_Status.csv* containing complete results.
