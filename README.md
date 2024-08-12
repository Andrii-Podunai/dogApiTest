# QA API Automation Test - Dog CEO API

## Project Description

This project contains automated tests for the [Dog CEO API](https://dog.ceo/dog-api/), which provides data on dog breeds. The tests were created using Postman and include status code validation, schema checks, and data validation.

## Requirements

- Postman
- GitHub account to store the test collection

### 1. Documentation

Logic Explanation

1. Status Code Validation:
Ensures the API is responding correctly by checking for a 200 status code.

2. Schema Validation:
The test verifies that the response follows a predefined JSON schema. This ensures that the structure of the data returned by the API is consistent, reducing the risk of errors when the data is used by other systems or applications.

4. Data Validation - Specific Breeds:
Verifies that the breeds list is not empty, includes specific breeds, and contains no duplicates.

5. Performance Check - Response Time:
The test measures the response time of the API, verifying that it is below a certain threshold (e.g., 200 milliseconds). This helps ensure that the API meets performance standards, providing a smooth user experience.

6. Breed Extraction:
The test script extracts individual dog breeds from the API response. It handles cases where breeds have sub-breeds by combining them into a single string (e.g., "Australian shepherd"). The extracted list is logged and can be stored as an environment variable for further use, making it accessible for other tests or processes.

### 2. Running the Tests

1. To run the tests, import the `.json` collection file into Postman.
2. Open the collection and click the "Run" button to execute all the tests.
