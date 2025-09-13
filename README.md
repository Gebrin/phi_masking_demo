**PII Masking and Recovery System**
A secure system to mask PII data and recover it back using encryption password.


**How It Works**

- Import required libraries - Load all necessary Python packages
- Load the dataset - Place your CSV file in the data folder and load it
- Detect PII columns - System automatically finds columns with personal information
- Create encryption - System asks you to create a password for this dataset
- Apply masking - All PII data gets masked while preserving original format
- Save masked data - Masked dataset saves to results folder with unique session ID
- For recovery - You need both the session ID and your password to get original data back

**Supported PII Types**

- Names (full names, doctor names)
- Addresses (street, city, zip)
- Contact info (email, phone)
- ID numbers (SSN, license numbers)
- IP addresses
- Dates
- Organization names
