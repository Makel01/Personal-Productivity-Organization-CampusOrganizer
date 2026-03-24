# System Diagrams

## Level-0 Data Flow Diagram (DFD)

User 
  → React Frontend  
  → Spring Boot Backend  
  → Database  
  → External Weather API

Text Version:

[User]
   → (1.0 Submit Action) → [Frontend]
   → (2.0 API Request) → [Backend]
   → (3.0 Query/Store) → [Database]
   → (4.0 Fetch Data) → [Weather API]
   ← Response Data ←

## Architecture Diagram (Text)

[React Frontend]
    ↓ REST API
[Spring Boot Backend]
    ↓ JPA/Hibernate
[Database]
    ↓ External Call
[Weather API]
