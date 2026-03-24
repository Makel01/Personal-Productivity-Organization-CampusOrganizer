# Data Model

## Entity 1: User
- id
- name
- email
- password_hash

## Entity 2: Task
- id
- user_id (FK)
- title
- due_date
- category
- status

## Entity 3: ProductivityStats
- id
- user_id (FK)
- tasks_completed
- completion_rate
- recommended_focus_hours

Relationships:
- One User → Many Tasks
- One User → One ProductivityStats record
