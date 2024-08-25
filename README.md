# UiPath Calculate Client Security Hash - Solution
This repository contains the complete solution for the Calculate Client Security Hash exercise from UiPath Academy Automation Developer Professional Training. The project demonstrates key concepts in Robotic Process Automation (RPA) using UiPath Studio, including data extraction, data manipulation, and automation of repetitive tasks.

# Features
- Orchestrator Integration: Automates the extraction of work items from the UiPath Orchestrator Queue.
- Data Scraping: Efficiently scrapes client information from the ACME System 1 website.
- Data Manipulation: Processes the extracted data to calculate the security hash by concatenating the client's ID, Name, and Country.
- SHA1 Encryption: Implements SHA1 hashing for generating the security hash for each client.
- Error Handling: Robust error handling and logging for monitoring the workflow’s execution.
- Modular Design: The workflow is structured into reusable components to enhance maintainability and scalability.

# How to Use
1. Clone this repository to your local machine.
2. Open the project in UiPath Studio.
3. Update the Orchestrator and ACME System credentials in the config file.
4. Run the workflow to calculate and update the security hash for each client work item.

# Prerequisites
1. UiPath Studio installed
2. Access to UiPath Orchestrator
3. An account on the ACME System 1 platform
