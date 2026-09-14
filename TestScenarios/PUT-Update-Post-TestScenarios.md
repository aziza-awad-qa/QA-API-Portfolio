# Test Scenarios

## API

PUT /posts/1

## Objective

Verify the functionality of the Update Post API.

| Scenario ID | Test Scenario |
|-------------|---------------|
| TS-001 | Verify that the API returns status code 200 OK. |
| TS-002 | Verify that an existing post can be updated successfully. |
| TS-003 | Verify that the response contains the `id` key. |
| TS-004 | Verify that the response contains the updated `title`. |
| TS-005 | Verify that the response contains the updated `body`. |