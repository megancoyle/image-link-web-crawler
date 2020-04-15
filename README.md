# Image/Link Web Crawler

## Overview

The Image/Link Web Crawler is a Python script used to check if there are any broken images/links for a given list of sites. The `urls.py` file was created since I had a list of several subdomains for a given domain that I needed to crawl with this project.

## Setup
1. Set up your environment with:
```
python3 -m venv venv
. venv/bin/activate
```
2. Install the dependencies:
```
pip install scrapy
```
3. To run the script, make sure you `cd` into the `image-link-web-crawler` directory. Then run the following command:
```
scrapy runspider script.py -o report.csv
```

The script will pull a CSV report letting you know which pages have 404ed for various external links and images.