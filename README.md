# QA API Automation Test - Dog CEO API

## Project Description

This project contains automated tests for the [Dog CEO API](https://dog.ceo/dog-api/), which provides data on dog breeds. The tests were created using Postman and include status code validation, schema checks, and data validation.

## Requirements

- Postman
- GitHub account to store the test collection

### 1. Documentation

Logic Explanation
1. Status Code Validation:
The status code validation ensures that the API endpoint is functioning properly by checking if the response status is 200 OK. This confirms that the request was successful and the server responded as expected.

2. Schema Validation:
Schema validation checks that the structure of the API's response matches the expected format. It verifies that the response includes the required fields and that these fields are of the correct data types. This helps ensure that the data returned by the API is in the correct format and can be used reliably.

3. Data Validation - Breeds List:
This test ensures that the API returns a list of dog breeds and that the list is not empty. It confirms that the API is providing the expected data and that there are no issues with data retrieval.

4. Data Validation - Specific Breeds:
The specific breeds validation checks that certain expected dog breeds are included in the API's response. This helps verify that the API is returning a complete and accurate list of breeds.

5. Data Integrity - No Duplicate Breeds:
This test checks that there are no duplicate entries in the list of dog breeds. It ensures the integrity of the data, preventing any misleading or redundant information from being included in the response.

6. Performance Check - Response Time:
The response time check ensures that the API responds quickly, with a response time below a specified threshold (e.g., 200 milliseconds). This is important for maintaining a good user experience, as slow response times can lead to frustration and inefficiency.

### 2. Running the Tests

1. To run the tests, import the `.json` collection file into Postman.
2. Open the collection and click the "Run" button to execute all the tests.
