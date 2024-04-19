# Retake_tests

# Petstore API Tests

This repository contains a set of tests for the Petstore API.

## Prerequisites

To run the tests, you will need the following:

- Python 3.x
- requests library
- unittest library

You can install the required libraries using pip:


## Running the Tests

To run the tests, simply execute the `main.py` script:



This will run all the tests and output the results to the console.

## Logging

The tests use the `logging` module to log information about their execution. The log messages are written to a file named `test_results.log` in the same directory as the `main.py` script.

You can adjust the logging level by changing the `level` parameter in the `logging.basicConfig()` call in the `setUp()` method of the `PetStoreAPITests` class.

## Test Descriptions

The following tests are included:

- `test_successful_request_status_code`: Tests that a successful request to the Petstore API returns a 200 status code.
- `test_successful_request_content_type`: Tests that a successful request to the Petstore API returns data in JSON format.
- `test_invalid_parameters_status_code`: Tests that a request to the Petstore API with invalid parameters returns a 404 status code.
- `test_invalid_parameters_content_type`: Tests that a request to the Petstore API with invalid parameters returns data in JSON format.
- `test_additional_test`: An additional test that can be used to demonstrate how to add new tests to the suite.

