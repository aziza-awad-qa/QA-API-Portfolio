# Test Cases

## API

POST /posts/add

## Test Case Summary

| Test Case ID | Related Scenario | Title | Priority |
|---|---|---|---|
| TC-001 | TS-001 | Verify the API creates a new post successfully | High |
| TC-002 | TS-006 | Verify the API rejects a request with invalid data types | High |



---

# TC-001

**Related Scenario**

TS-001

**Title**

Verify the API creates a new post successfully.

**Priority**

High

**Preconditions**

- Postman is installed.
- Internet connection is available.
- DummyJSON API is accessible.

**Test Steps**

1. Open Postman.
2. Select the **POST** method.
3. Enter the endpoint:
   `https://dummyjson.com/posts/add`
4. Open the **Body** tab.
5. Select **raw → JSON**.
6. Enter a valid JSON request body.
7. Click **Send**.

**Expected Result**

- The API returns status code **201 Created**.
- A new post is created successfully.
- The response contains the `id` key.
- The response contains the submitted `title`.
- The response contains the submitted `userId`.
---

# TC-002

**Related Scenario**

TS-006

**Title**

Verify the API rejects a request with invalid data types.

**Priority**

High

**Preconditions**

- Postman is installed.
- Internet connection is available.
- DummyJSON API is accessible.

**Test Steps**

1. Open Postman.
2. Select the **POST** method.
3. Enter the endpoint:
   `https://dummyjson.com/posts/add`
4. Open the **Body** tab.
5. Select **raw → JSON**.
6. Enter invalid data types:

```json
{
  "title": 12345,
  "body": true,
  "userId": "invalid"
}