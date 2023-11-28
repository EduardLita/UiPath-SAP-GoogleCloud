# UiPath-SAP-GoogleCloud

Process Flow:
Voice Command Creation:

Utilizes the Google Speech module to convert audio commands into text strings.
Offers language translation capabilities for versatile input processing.
Input Analysis:

Extracts key elements (company name, material) from the text string.
SAP Database Query (1st):

Accesses SAP S/4HANA environment to retrieve additional information about the company and requested materials.
Data Processing:

Analyzes extracted information to determine order specifics.
SAP Order Launch:

Initiates a second query to the SAP environment, this time to place the order based on the processed information.
Order Confirmation:

Generates an audio confirmation message using Google Speech, indicating the successful completion of the order.
