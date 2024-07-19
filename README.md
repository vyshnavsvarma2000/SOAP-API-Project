# Number Conversion API Project

This project demonstrates how to use the Number Conversion web service to convert numbers to words using Postman. The project also includes generating reports using Newman.

## Project Overview

The Number Conversion web service provides operations to convert numbers to words. This API project utilizes the `NumberToWords` operation to demonstrate API testing and report generation.

## API Endpoint

- **Service URL:** `https://www.dataaccess.com/webservicesserver/numberconversion.wso`
- **Operation:** `NumberToWords`

## Tools and Technologies

- **Postman:** For creating and managing API requests.
- **Newman:** For running Postman collections from the command line and generating reports.

## Getting Started

### Prerequisites

- **Postman:** Install Postman from [here](https://www.postman.com/downloads/).
- **Newman:** Install Newman globally using npm:

  ```bash
  npm install -g newman

Importing the Postman Collection
Open Postman.

Click on Import in the top left corner.

Select the Import From Link tab.

Paste the following link:
<Link to your Postman Collection>
Click Continue to import the collection.
Running the Collection in Postman
Select the imported collection.
Click the Run button to execute the requests.
Running the Collection with Newman
Export the Postman collection to a JSON file.

Use the following command to run the collection with Newman:

newman run <path_to_your_postman_collection.json>

Here's a README.md file for your API project using the Number Conversion web service. This file includes sections about the project, how to use it with Postman, and generating reports with Newman.

markdown
Copy code
# Number Conversion API Project

This project demonstrates how to use the Number Conversion web service to convert numbers to words using Postman. The project also includes generating reports using Newman.

## Project Overview

The Number Conversion web service provides operations to convert numbers to words. This API project utilizes the `NumberToWords` operation to demonstrate API testing and report generation.

## API Endpoint

- **Service URL:** `https://www.dataaccess.com/webservicesserver/numberconversion.wso`
- **Operation:** `NumberToWords`

## Tools and Technologies

- **Postman:** For creating and managing API requests.
- **Newman:** For running Postman collections from the command line and generating reports.

## Getting Started

### Prerequisites

- **Postman:** Install Postman from [here](https://www.postman.com/downloads/).
- **Newman:** Install Newman globally using npm:

  ```bash
  npm install -g newman
Importing the Postman Collection
Open Postman.

Click on Import in the top left corner.

Select the Import From Link tab.

Paste the following link:

css
Copy code
<Link to your Postman Collection>
Click Continue to import the collection.

Running the Collection in Postman
Select the imported collection.
Click the Run button to execute the requests.
Running the Collection with Newman
Export the Postman collection to a JSON file.

Use the following command to run the collection with Newman:

bash
Copy code
newman run <path_to_your_postman_collection.json>
Generating Reports with Newman
Newman allows you to generate various types of reports. Here is an example of generating an HTML report:

Run the following command to generate an HTML report:
newman run <path_to_your_postman_collection.json> -r html
Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.
