# AutomationAnywhereCertification

*****************************************GRATUITY ANALYSIS*****************************************

Process Use Case

Open the Employee.xml file.

The XML contains Employee Information for all the employees in an organization.
Every month the eligibility of employees for gratuity should be reviewed using the XML file.
The eligible candidate list should be extracted in the given Employee.xlsx file format
Business Rules/Conditions to Automate the Process

The Bot you develop is expected to do the following:

The Bot needs to open the XML file.  
In the XML, the Bot needs to read data row by row and do the check for gratuity eligibility for all the employee.
The organization checks gratuity eligibility of their employees based on the given criteria:
Number of years in the organization >= 5
Overall performance rating >= 5
City should be NY
State should be New York.
 

Extracted data must be entered in the Employee.xlsx file
The Bot should read the Excel row by row and send an email notification to each employee with the following details:
Years of Service in the Organization
Rating
Eligibility for gratuity
Rename the Employee.xlsx file to “YourEmailID_Bot_1_Output.xlsx”
Submit the output file with given naming convention – Very Important!
“YourEmailID_Bot_1_Output.xlsx”
Submit these Files

Developed Bot (*atmx) file.
Save the Bot file as text file with the given naming convention – Very Important!
“YourEmailId_Bot_1”
Submit the Bot file and output file

*************************BFSI (Banking Financial Services and Insurance) Macros***************************

Process Use Case

Open the Data.xlsx file.
The file contains data for payment mode, bank, and RRN.
Open the Macro Sheet.xlsx file.
This file contains macro names for the Data file.
Develop a Bot to capture the right macro names and update the Data file.
Business Rules/Conditions to Automate the Process

The Bot you develop is expected to do the following:

The Bot needs to open the Data file.
In the Data file, the Bot needs to read payment mode, bank name, and RRN number row by row.
The Bot needs to check for all the given data in the Macro Sheet file.
If payment mode, bank name, and RRN number is a (Match) (Valid) then pick up the first macro name and dump it into the Data file in Column E.
If the bank name is SBI, Corporation Bank, HDFC, or ICICI then consider bank name in Macro Sheet as – (Hyphen)
Copy the Data file and rename the file as given – Very Important!
“YourEmailID_Bot_2_Output.xlsx”
Submit these Files

Developed Bot (*atmx) file.
Save the Bot file as text file with the given naming convention – Very Important!
“YourEmailId_Bot_2”

*****************************************Invoice Processing*****************************************

Introduction

In this use case, you are expected to develop a Bot using Automation Anywhere Enterprise to automate a process and business rules outlined below. Submit the files as per the Instructions given in the Certification portal.

Process Use Case

Open the web page: http://rpademo.automationanywhere.com/master-pdf.php
Use the given credential.
Username: candidate
Password: LetMeIn123!
Download all the PDF and invoice_template.xlsx file from the web page.
Extract the data from the PDF and enter them in the downloaded Excel file.
Business Rules/Conditions to Automate the Process

The Bot you develop is expected to do the following:

Extract the data from the downloaded PDF based on the following condition:
Quantity should be greater than or equal to 2.
Unit price should be greater than or equal to 2.
Line total should be greater than or Equal to 100.
Due date should be greater than 01-April-2019.
Payment term should be due on receipt.
Enter the extracted data in the invoice_template.xlsx.
Rename the invoice_template.xlsx file to “YourEmailID_Bot_3_Output.xlsx”
Submit the output file with given naming convention – Very Important!
“YourEmailID_Bot_3_Output.xlsx”
Submit these Files

Developed Bot (*atmx) file.
Save the Bot file as text file with the given naming convention – Very Important!
“YourEmailId_Bot_3”
Submit the Bot file and output file
