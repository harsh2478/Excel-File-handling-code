# excel-file-handling-small-app-
I've created a small application named Google-Summary-Portal that utilizes the openpyxl module in Python for Excel file handling. 

Here's a synopsis 

- Web Searching Function:
  Implemented a function called web_searching() using the Wikipedia module for searching information.

- Excel File Creation Function:
  Created a function named create_excel_file() using the openpyxl module.
  The function generates an Excel file with headings for Names, Emails, and Phones.

- User Input and Data Storage Function:
  Developed a function named action() to interact with users.
  Loaded the Excel file, prompted users for basic information (name, email, phone number), and stored the input in the Excel file for each user.

- Emails and Phones List Functions:
  Created Emails_list() and phone_list() functions to retrieve lists of emails and phone numbers from the Excel database using openpyxl.

- Bulk Email Functionality:
  Introduced a function named send_greeting_emails() to demonstrate multiple operations on collected data.
  Used the lists obtained from the Excel file to send bulk greeting emails.
