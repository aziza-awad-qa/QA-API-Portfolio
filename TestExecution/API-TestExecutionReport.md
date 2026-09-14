# API Test Execution Report

| Test Case ID | API | Execution Status | Actual Result |
|---------------|-----|------------------|---------------|
| TC-001 | GET /posts | Pass | Status code = 200 OK |
| TC-001 | GET /posts | Pass | Response body is not empty |
| TC-001 | GET /posts | Pass | Response contains the `posts` key |
| TC-001 | GET /posts/1 | Pass | Status code = 200 OK |
| TC-001 | GET /posts/1 | Pass | Returned post ID = 1 |
| TC-001 | GET /posts/1 | Pass | Response contains the `title` key |
| TC-001 | POST /posts/add | Pass | Status code = 201 Created |
| TC-001 | POST /posts/add | Pass | Response contains the `id` key |
| TC-001 | POST /posts/add | Pass | The returned title matches the request |
| TC-001 | PUT /posts/1 | Pass | Status code = 200 OK |
| TC-001 | PUT /posts/1 | Pass | Response contains the `id` key |
| TC-001 | PUT /posts/1 | Pass | Post ID = 1 |
| TC-001 | PUT /posts/1 | Pass | The returned title matches the updated value |
| TC-001 | PUT /posts/1 | Pass | The returned body matches the updated value |
| TC-001 | PATCH /posts/1 | Pass | Status code = 200 OK |
| TC-001 | PATCH /posts/1 | Pass | Response contains the `id` key |
| TC-001 | PATCH /posts/1 | Pass | Post ID = 1 |
| TC-001 | PATCH /posts/1 | Pass | The returned title matches the updated value |
| TC-001 | DELETE /posts/1 | Pass | Status code = 200 OK |
| TC-001 | DELETE /posts/1 | Pass | Response contains the `id` key |
| TC-001 | DELETE /posts/1 | Pass | Post ID = 1 |
| TC-001 | DELETE /posts/1 | Pass | `isDeleted` = true |
| TC-001 | DELETE /posts/1 | Pass | Response contains the `deletedOn` key |
| TC-002 | GET /posts/999999 | Pass | Status code = 404 Not Found |
| TC-002 | POST /posts/add | Pass | Status code = 400 Bad Request |