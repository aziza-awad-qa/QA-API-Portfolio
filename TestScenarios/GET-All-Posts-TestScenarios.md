# Test Scenarios

## API

GET /posts

## Objective

Verify the functionality of the Get All Posts API.

---

| Scenario ID | Test Scenario |
|-------------|---------------|
| TS-001 | Verify that the API returns status code 200 OK. |
| TS-002 | Verify that the API returns the expected response body. |
| TS-003 | Verify that the response body contains the `posts` key. |
| TS-004 | Verify that the `posts` array is not empty. |
| TS-005 | Verify that each post contains the required fields (`id`, `title`, `body`, and `userId`). |