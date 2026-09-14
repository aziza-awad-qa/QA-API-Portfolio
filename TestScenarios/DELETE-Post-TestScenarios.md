# Test Scenarios

## API

DELETE /posts/1

## Objective

Verify the functionality of the Delete Post API.

| Scenario ID | Test Scenario |
|-------------|---------------|
| TS-001 | Verify that the API returns status code 200 OK. |
| TS-002 | Verify that an existing post can be deleted successfully. |
| TS-003 | Verify that the response contains the `id` key. |
| TS-004 | Verify that the post is marked as deleted. |
| TS-005 | Verify that the response contains the `deletedOn` key. |