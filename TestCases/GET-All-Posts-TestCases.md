# Test Cases

## API

GET /posts

## Test Case Summary

| Test Case ID | Related Scenario | Title | Priority |
|---------------|------------------|--------|----------|
| TC-001 | TS-001 | Verify the API returns status code 200 OK | High |
| TC-002 | TS-002 | Verify the API returns the expected response body | High |
| TC-003 | TS-003 | Verify the response body contains the `posts` key | High |
| TC-004 | TS-004 | Verify the `posts` array is not empty | Medium |
| TC-005 | TS-005 | Verify each post contains the required fields | High |

---

# TC-001

**Related Scenario:** TS-001

**Title**

Verify the API returns status code 200 OK.

**Priority**

High

**Preconditions**

- Postman is installed.
- Internet connection is available.
- DummyJSON API is accessible.

**Test Steps**

1. Open Postman.
2. Select **GET** method.
3. Enter the endpoint: `https://dummyjson.com/posts`
   ```
4. Click Send to execute the request.


### Expected Result

- The API returns status code **200 OK**.
- The response body is not empty.
- The response body contains the `posts` key.