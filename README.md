Introduction
- Its a Python-based automation system designed to process receipts directly from emails
- Automatically extracts key receipt details from attachments using OCR
- Reduces manual data entry, saving time and minimizing human errors
- Provides a structured and efficient way to manage receipt data
- Demonstrates real-world use of automation, OCR, and data processing


Features
- Automatically reads emails from the inbox
- Downloads receipt attachments (PDFs/images)
- Uses OCR (PaddleOCR) for text extraction
- Extracts key information:
    Receipt Number
    Vendor Name
    Date
    Total Amount
- Stores extracted data in Excel format
- Sends email notifications with extracted details
- Improves efficiency and reduces manual workload


How It Works
- Connects to the email server using IMAP
- Searches for emails containing attachments
- Downloads receipt files to a local folder
- Applies OCR to convert images/PDFs into text
- Processes the extracted text to identify relevant fields
- Saves the structured data into an Excel file
- Sends a summary email with the extracted information


Outcome
- Faster and automated receipt processing
- Reduced chances of human error
- Organized and structured data storage
- Practical solution for real-world business tasks
