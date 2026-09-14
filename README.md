# QA API Portfolio

## Project

DummyJSON REST API

## Objective

This repository demonstrates practical API Testing skills using Postman.

## Tools

- Postman
- REST API
- JSON
- Git & GitHub
  
## API Endpoints Tested

| Method | Endpoint | Purpose |
|---|---|---|
| GET | `/posts` | Get all posts |
| GET | `/posts/1` | Get a single post |
| POST | `/posts/add` | Create a new post |
| PUT | `/posts/1` | Update a post |
| PATCH | `/posts/1` | Partially update a post |
| DELETE | `/posts/1` | Delete a post |

## Testing Scope

### Functional Testing

- Verify HTTP status codes
- Validate response body
- Verify response properties
- Validate returned data
- Verify created and updated data

### Positive Testing

- Successful GET requests
- Successful POST request
- Successful PUT request
- Successful PATCH request
- Successful DELETE request

### Negative Testing

- Requesting a non-existing post
- Sending invalid data types

## Test Documentation

- [Test Plan](TestPlan/API-TestPlan.md)
- [Test Scenarios](TestScenarios/)
- [Test Cases](TestCases/)
- [Test Execution Report](TestExecution/API-TestExecutionReport.md)
## Postman Collection

The complete Postman collection is available in:

`Collections/Postman/QA-API-Portfolio.postman_collection.json`

The collection contains the API requests and Postman assertions used during testing.

## Test Execution

The collection was executed using Postman Collection Runner.

**Result:** 22 Tests Passed / 0 Failed
## Project Status

Completed
