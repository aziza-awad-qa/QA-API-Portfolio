# Test Cases

## API

DELETE /posts/1

## Test Case Summary

| Test Case ID | Related Scenario | Title | Priority |
|---|---|---|---|
| TC-001 | TS-002 | Verify an existing post can be deleted successfully | High |

---

# TC-001

**Related Scenario**

TS-002

**Title**

Verify an existing post can be deleted successfully.

**Priority**

High

**Preconditions**

- Postman is installed.
- Internet connection is available.
- DummyJSON API is accessible.
- Post with ID 1 exists.

**Test Steps**

1. Open Postman.
2. Select the **DELETE** method.
3. Enter the endpoint:
   `https://dummyjson.com/posts/1`
4. Click **Send**.

**Expected Result**

- The API returns status code **200 OK**.
- The post is marked as deleted successfully.
- The response contains the `id` key.
- The response `id` is **1**.
- The response contains `isDeleted` with value **true**.
- The response contains the `deletedOn` key.
