# Test Cases

## API

GET /posts/1

## Test Case Summary

| Test Case ID | Related Scenario | Title | Priority |
|---------------|------------------|--------|----------|
| TC-001 | TS-001 | Verify the API returns status code 200 OK | High |
| TC-002 | TS-006 | Verify the API returns 404 for a non-existing post | Medium |
---

# TC-001

**Related Scenario**

TS-001

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
2. Select the **GET** method.
3. Enter the endpoint: `https://dummyjson.com/posts/1`
4. Click **Send**.

**Expected Result**

- The API returns status code **200 OK**.
- The response body is not empty.
- The response contains the `id` key.
- The value of `id` is **1**.
---

# TC-002

**Related Scenario**

TS-006

**Title**

Verify the API returns 404 for a non-existing post.

**Priority**

Medium

**Preconditions**

- Postman is installed.
- Internet connection is available.
- DummyJSON API is accessible.

**Test Steps**

1. Open Postman.
2. Select the **GET** method.
3. Enter the endpoint:
   `https://dummyjson.com/posts/999999`
4. Click **Send**.

**Expected Result**

- The API returns status code **404 Not Found**.
- The API indicates that the requested post does not exist.

**Actual Result**

- The API returned **404 Not Found**.
