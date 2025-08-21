### This is learning of Rust Actix Web which is very fast

## I learned:
---
- How to build a REST API using Actix Web.
- How to use `Mutex` for safe shared state in a web server.
- How to implement CRUD operations for tasks and users.
- How to serialize and deserialize data with Serde.
- How to persist data to a JSON file.
- How to handle CORS in Actix Web.
- How to structure a Rust web project.

## Features

- Task management: create, read, update, delete tasks.
- User management: add users, query by username.
- Persistent storage using `database.json`.
- Simple authentication logic (username/password).
- CORS support for frontend integration.

## How to run

```bash
cargo run
```

## API Endpoints

- `GET /task` - List all tasks
- `POST /task` - Create a new task
- `PUT /task` - Update a task
- `GET /task/{id}` - Read a task by id
- `DELETE /task/{id}` - Delete a task
- `POST /register` - Add a user
- `POST /login` - Log in
---
