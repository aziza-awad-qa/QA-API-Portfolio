# Test Scenarios

## API

GET /posts

## Objective

Verify that the Get All Posts API returns the expected response.

---

| Scenario ID | Test Scenario |
|-------------|---------------|
| TS-001 | Verify the API returns status code 200. |
| TS-002 | Verify the response body is returned successfully. |
| TS-003 | Verify the response contains the `posts` array. |
| TS-004 | Verify the `posts` array is not empty. |
| TS-005 | Verify each post contains the required fields. |