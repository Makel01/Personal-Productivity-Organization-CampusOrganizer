# Use Cases for Personal Productivity System

## Use Case 1: Create Task
Use Case ID: UC-001
Priority: High
Primary Actor: Student/User

Description:
The user creates a new task with a title, due date, and category to organize their academic or personal responsibilities.

Trigger: User selects "Add New Task".
Type: External

Preconditions:
1. User is logged into the system.
2. Database is available.
3. Internet connection is active.

---

## Use Case 2: View Dashboard
Use Case ID: UC-002
Priority: Medium
Primary Actor: Student/User

Description:
The user views their dashboard which shows today’s tasks, upcoming deadlines, and productivity metrics.

Trigger: User opens the dashboard page.
Type: External

Preconditions:
1. User is authenticated.
2. Task data exists.
3. Database is functioning normally.

---

## Use Case 3: Get Weather API Data
Use Case ID: UC-003
Priority: Low
Primary Actor: Student/User

Description:
The system retrieves weather data from the external API to customize the user’s productivity recommendations.

Trigger: User opens the homepage.
Type: External

Preconditions:
1. External weather API is available.
2. System has a valid API key.
3. User is authenticated.
