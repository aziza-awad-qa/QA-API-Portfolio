# Test Scenarios

## API

GET /posts/1

## Objective

Verify the functionality of the Get Single Post API.

---

| Scenario ID | Test Scenario |
|-------------|---------------|
| TS-001 | Verify that the API returns status code **200 OK**. |
| TS-002 | Verify that the API returns the post with ID = **1**. |
| TS-003 | Verify that the response body contains the `title` key. |
| TS-004 | Verify that the response body contains the `body` key. |
| TS-005 | Verify that the response body contains the `userId` key. |