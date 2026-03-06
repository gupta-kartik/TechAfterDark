# Coding Challenge 1 – JSON Transformer

## Difficulty: Beginner / Intermediate

## Time Limit: 10–15 minutes

---

## Brief

You have been given a raw JSON dataset containing a list of users. Your task is to transform it into a new format suitable for a reporting dashboard.

---

## Input

```json
[
  { "id": 1, "first_name": "Alice", "last_name": "Smith", "age": 30, "active": true },
  { "id": 2, "first_name": "Bob", "last_name": "Jones", "age": 25, "active": false },
  { "id": 3, "first_name": "Carol", "last_name": "White", "age": 35, "active": true }
]
```

---

## Requirements

Write a function `transform_users(data)` that:

1. Returns only **active** users
2. Combines `first_name` and `last_name` into a single `full_name` field
3. Adds a `senior` boolean field — `true` if age is 30 or above
4. Removes the `active` field from the output

---

## Expected Output

```json
[
  { "id": 1, "full_name": "Alice Smith", "age": 30, "senior": true },
  { "id": 3, "full_name": "Carol White", "age": 35, "senior": true }
]
```

---

## Judging Criteria

- Correctness of output
- Code clarity and readability
- Effective use of GitHub Copilot
- Speed of completion
