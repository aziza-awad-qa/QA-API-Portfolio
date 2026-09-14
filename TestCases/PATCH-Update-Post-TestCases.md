# Test Cases

## API

PATCH /posts/1

## Test Case Summary

| Test Case ID | Related Scenario | Title | Priority |
|---|---|---|---|
| TC-001 | TS-002 | Verify an existing post can be partially updated successfully | High |

---

# TC-001

**Related Scenario**

TS-002

**Title**

Verify an existing post can be partially updated successfully.

**Priority**

High

**Preconditions**

- Postman is installed.
- Internet connection is available.
- DummyJSON API is accessible.
- Post with ID 1 exists.

**Test Steps**

1. Open Postman.
2. Select the **PATCH** method.
3. Enter the endpoint:
   `https://dummyjson.com/posts/1`
4. Open the **Body** tab.
5. Select **raw → JSON**.
6. Enter:

```json
{
  "title": "Updated with PATCH"
}