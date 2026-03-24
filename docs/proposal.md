Project Overview
Problem Statement

Explain what real-world problem your app solves.

Example (Personal Productivity & Organization App):

Students often struggle to keep track of assignments, deadlines, study sessions, and personal tasks. Existing tools are either too complicated, too generic, or require multiple separate apps. This leads to missed deadlines, disorganization, and extra stress.

Target Users

Who will use the app?

Example:

The primary users are college students who need a simple system to track tasks, events, study goals, and personal productivity.

Value Proposition

Why is your app valuable?

Example:

The system provides a single, centralized dashboard where students can plan tasks, track progress, and improve productivity. It reduces stress by combining multiple tools into one simple interface.

Minimum Viable Product (MVP)

Your MVP must include only core essential features.

Example:

Create tasks (with due date, priority, category)
Mark a task as complete
View a productivity dashboard
Sync with external API (e.g., Google Calendar or weather API)
Basic user login
2. External API Integration

You MUST pick one external API.

Example (Weather API):

API: OpenWeatherMap
Data Provided: Temperature, forecast, weather conditions
Usage in the App:
The dashboard will display daily weather so students can plan outdoor study sessions, morning routines, or travel time before class.

Other acceptable APIs:

Google Calendar API
News API
Mapbox API
Eventbrite API
Foursquare Places API
3. System Decomposition
System Modules

List 3–5 major components.

Example:

Authentication Module – user login/register
Task Management Module – create, update, delete tasks
Dashboard Module – summary of productivity + weather API
Notification Module – reminders
User Profile Module – personal settings
Data Flow Diagram (Level 0 DFD)

Describe the diagram (or put an image in /docs/diagrams).

Example text version:

User → React Frontend → Spring Boot API → Database
                                ↓
                         External Weather API

Entities / Data Objects

Example:

User
id
name
email
password_hash
Task
id
user_id
title
description
due_date
priority
status
DashboardSummary
total_tasks
tasks_completed
daily_weather

Include relationships:

A User can have many Tasks.
The DashboardSummary aggregates data from Tasks and the weather API.

Architecture Diagram

A simple diagram showing:

React Frontend  →  Spring Boot Backend  →  PostgreSQL Database  
                                   ↓  
                             External Weather API

4. Demo-Centric Planning

Describe how you’ll demonstrate the app live.

Example:

During the demo, a user logs in, creates a new task, marks a task as complete, views weather data from the external API on the dashboard, and shows how the backend saves data in the database.

5. Responsible AI Usage Log

This goes in ai_usage_log.md but your proposal should say:

“See ai_usage_log.md for full documentation of AI contributions.”
