# Automotive-Supply-Chain-Automation
## Project Overview
A comprehensive end-to-end automation suite designed for the automotive supply chain. This suite streamlines the lifecycle of logistics data—from unstructured PDF parsing to real-time tracking navigation and long-term cost trend analysis.

## Step 1. Read Container number from excel -> automate key in web address
<img width="1726" height="973" alt="image" src="https://github.com/user-attachments/assets/86f9a976-034b-4971-83b1-8cd65ac7bd67" />

* consider web scrapping in the future
* Developed a URL construction engine that maps container IDs to official carrier tracking systems (e.g., Maersk, Hapag-Lloyd).
* Automated batch-search processes, reducing manual logistics tracking overhead by approximately 80%.

## Step 2. Automated Data Extraction (ReadPDF) Read Container infrormation -> automate output in excel and sqlite

* Engineered a Python-based parser using PyPDF2 and Regex to extract financial data from complex invoice structures.
* Implemented data normalization logic to handle version drift and formatting noise, ensuring 100% data integrity before SQL injection

## Step 3. Read Container other information -> automate join and detect lost data -> print out in excel and sqlite

## Step 4. Cost analyst can be done in sqlite
