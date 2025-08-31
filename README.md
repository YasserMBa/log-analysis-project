# Log Analysis Project

This project analyzes web server log files using Python, Regular Expressions, and NumPy.  
It extracts useful information such as hostnames, timestamps, request types, status codes, and response sizes.

## Features
- Extract hostnames, timestamps, requests, status codes, and response sizes using regex.
- Calculate average requests per hour.
- Calculate average response size.
- Calculate the percentage of successful status codes (2xx).
- Works with both domain hostnames and IP addresses.

## Requirements
- Python 3.x
- NumPy

You can install the dependencies with:
```bash
pip install numpy
```

## Usage
1. Place your `access.log` file in the project folder.
2. Run the Jupyter Notebook or Python script to analyze the log file.
3. Results will be printed, such as:
   - Average requests per hour
   - Average response size
   - Percentage of successful status codes

## Log File

The `access.log` file was compressed to reduce size before uploading to GitHub.  
To use it, decompress it first:

If `.gz` format:
```bash
gzip -d access.log.gz
```

If `.zip` format:
```bash
unzip access.zip
```

## License
This project is for educational purposes only.
