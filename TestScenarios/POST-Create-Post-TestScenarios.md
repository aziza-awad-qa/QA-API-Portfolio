# Test Scenarios

## API

POST /posts/add

## Objective

Verify the functionality of the Create Post API.

---

| Scenario ID | Test Scenario |
|-------------|---------------|
| TS-001 | Verify that the API returns status code **201 Created**. |
| TS-002 | Verify that a new post is created successfully. |
| TS-003 | Verify that the response contains the `id` key. |
| TS-004 | Verify that the response contains the `title` key. |
| TS-005 | Verify that the response contains the `userId` key. |