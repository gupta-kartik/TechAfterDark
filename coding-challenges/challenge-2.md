# Coding Challenge 2 – Simple REST API Endpoint

## Difficulty: Intermediate

## Time Limit: 10–15 minutes

---

## Brief

Build a small REST API in Python (Flask) or Node.js (Express) that manages a simple in-memory to-do list.

---

## Requirements

Implement the following endpoints:

| Method | Path | Description |
|--------|------|-------------|
| `GET` | `/todos` | Return all to-do items |
| `POST` | `/todos` | Add a new to-do item |
| `DELETE` | `/todos/<id>` | Remove a to-do item by ID |

### To-Do Item Structure

```json
{
  "id": 1,
  "task": "Buy milk",
  "done": false
}
```

---

## Example Requests

**Add a task:**
```
POST /todos
{ "task": "Write tests" }
```

**Expected response:**
```json
{ "id": 2, "task": "Write tests", "done": false }
```

---

## Judging Criteria

- All three endpoints work correctly
- Sensible error handling (e.g. deleting a non-existent ID)
- Code clarity
- Effective use of GitHub Copilot
- Speed of completion
