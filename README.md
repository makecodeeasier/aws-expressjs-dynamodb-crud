# AWS Lambda DynamoDB Task Manager

This project is a simple Task Manager using AWS Lambda and DynamoDB.  
It provides CRUD operations (Create, Read, Update, Delete) on a `Tasks` table.

---

## Features

- Fetch all tasks (`fetchTasks`)
- Create a new task (`createTasks`)
- Update an existing task (`updateTasks`)
- Delete a task (`deleteTasks`)

Each task has the following fields:

- `id` – unique identifier (UUID)
- `name` – task name
- `completed` – task completion status (`true`/`false`)

---

## Technologies

- Node.js
- AWS Lambda
- AWS SDK v3 (`@aws-sdk/client-dynamodb` and `@aws-sdk/lib-dynamodb`)
- DynamoDB
- Node.js built-in `crypto` for generating UUIDs

---

## Installation

1. Clone the repository:

```
git clone https://github.com/YourUsername/aws-lambda-dynamodb-tasks.git
cd aws-lambda-dynamodb-tasks
```

2.Install dependencies:

```
npm install
```

3. Configure AWS
```
Create credentials using AWS CLI or environment variables (AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, AWS_REGION).
```
