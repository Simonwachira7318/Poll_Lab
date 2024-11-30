# Poll_Lab
# Online Polling System

![Project Preview](https://github.com/Simonwachira7318/Poll_Lab/blob/main/image.png)

## 1. Problem Statement

### Context
In the era of online and remote learning, engaging students during virtual lectures has become increasingly challenging. Traditional lecture methods often struggle to maintain student attention and participation in digital environments.

### Identified Challenges
- Lack of real-time student interaction in online lectures
- Difficulty in measuring student understanding and engagement
- Limited tools for immediate feedback and assessment
- Need for an accessible and user-friendly polling mechanism

### Project Objectives
- Develop an interactive online polling system
- Create a simple, intuitive interface for both educators and students
- Enable real-time quiz creation and participation
- Provide graphical visualization of poll results
- Prevent multiple voting to ensure result integrity

---

## 2. System Architecture and Design

### Overall System Architecture
```mermaid
graph TD
    A[Web Browser] -->|HTTP Requests| B[Django Web Server]
    B --> C[URL Routing]
    C --> D[Views/Controllers]
    D --> E[Models/Database]
    E --> F[SQLite/Database]
    D --> G[Templates]
    G --> A
