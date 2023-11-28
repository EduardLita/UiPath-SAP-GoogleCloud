# UiPath-SAP-GoogleCloud

## Project Overview

This project is designed in the UiPath environment and leverages SAP S/4HANA and Google Cloud technologies. The primary functionality involves automating parts ordering processes within the SAP environment, providing flexibility in specifying both the company name and the desired parts for the order.

## Features

### Voice Command Integration:

* Utilizes the Google Speech module to convert audio commands into text strings.
* Supports language translation for versatile input processing.

### Dynamic Input Analysis:

* Extracts key elements such as company name and material from the processed text string.

### SAP Database Interaction:

* Queries the SAP environment to obtain detailed information about the specified company and materials.

### Order Automation:

* Initiates a second SAP query to launch the order based on the extracted information.

### Confirmation Feedback:

* Generates an audio confirmation message using Google Speech upon successful order completion.

## Usage

1. Clone the repository.
2. Open the project in UiPath Studio.
3. Configure Google Cloud and SAP credentials.
4. Run the main workflow to initiate the parts ordering process.

## Dependencies
UiPath
SAP S/4HANA
Google Cloud

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.
