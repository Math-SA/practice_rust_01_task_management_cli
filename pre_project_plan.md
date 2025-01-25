# Pre-Project Plan: Rust CLI To-Do List tool

## Overview
This project involves building a command-line to-do list application with advanced features like priority levels, deadlines, and habit tracking. The application will use a database for persistence and include performance-sensitive features like efficient querying and full-text search. The project will be completed in **two weeks** with the help of AI tools acting as a mentor and product owner.

---

## Goals and Expectations
### Personal Development Goals
- **Broad Career Goals:**  
  My goal is to become a Backend Engineer with expertise in Rust and database management. This project will help me gain hands-on experience with Rust, database integration, and performance optimization, which are essential for backend development roles.

- **Learning Objectives:**  
  - **Technical Skills:**  
    - Learn Rust syntax and core concepts (e.g., ownership, borrowing, error handling).  
    - Gain proficiency in database integration using SQLite or PostgreSQL.  
    - Understand how to optimize queries and implement full-text search.  
  - **Soft Skills:**  
    - Improve problem-solving skills by debugging and optimizing performance.  

### Project Goals
- **Expected Outcomes:**  
  - Build a fully functional to-do list application with priority levels, deadlines, and habit tracking.  
  - Implement database-backed persistence and performance-sensitive features like efficient querying and full-text search.  
  - Document the entire process for future reference.

- **Success Metrics:**  
  - The application is fully functional and meets all specified requirements.  
  - Database queries are optimized and perform efficiently.  

---

## Alignment with Career Goals
This project aligns with my goal of becoming a Backend Engineer by helping me gain hands-on experience with Rust and database management. It will allow me to demonstrate my ability to design, build, and optimize a backend application, which is a key requirement for roles in backend development.

---

## Tools and Resources
### Tools
- **Development:** Rust, SQLite/PostgreSQL, `rusqlite`/`tokio-postgres` crate.
- **Query Optimization:** SQL indexes, full-text search.
- **Testing:** `cucumber` for BDD, `cargo test` for unit tests.
- **Productivity:** GitHub for version control, VS Code for development.
- **AI Tools:** ChatGPT for mentorship, Claude for product ownership.

### Resources
- Rust documentation: [https://doc.rust-lang.org/](https://doc.rust-lang.org/)
- SQLite documentation: [https://www.sqlite.org/docs.html](https://www.sqlite.org/docs.html)
- PostgreSQL documentation: [https://www.postgresql.org/docs/](https://www.postgresql.org/docs/)
- `rusqlite` crate documentation: [https://docs.rs/rusqlite/latest/rusqlite/](https://docs.rs/rusqlite/latest/rusqlite/)
- `tokio-postgres` crate documentation: [https://docs.rs/tokio-postgres/latest/tokio_postgres/](https://docs.rs/tokio-postgres/latest/tokio_postgres/)

---

## Anticipated Challenges
1. **Challenge:** Learning Rust’s ownership and borrowing system.  
   **Solution:** Follow the Rust Book and practice with small examples before implementing the project.

2. **Challenge:** Optimizing database queries for performance.  
   **Solution:** Use indexing and benchmark queries to identify bottlenecks.

3. **Challenge:** Implementing full-text search.  
   **Solution:** Use SQLite’s `FTS5` extension or PostgreSQL’s full-text search capabilities and follow documentation/tutorials.

---

## Risk Assessment
1. **Risk:** Difficulty learning Rust’s advanced concepts.  
   **Mitigation:** Break the project into smaller tasks and focus on one concept at a time.

2. **Risk:** Database performance issues with large datasets.  
   **Mitigation:** Use indexing and connection pooling to optimize performance.

3. **Risk:** Overwhelmed by the complexity of full-text search.  
   **Mitigation:** Start with a simple implementation and gradually add complexity.

---

## Stakeholder Analysis
### **1. AI Mentor**
- **Role:** Provide technical guidance, best practices, and troubleshooting assistance for Rust and database integration.  
- **Expectations:**  
  - Help me understand Rust concepts like ownership, borrowing, and error handling.  
  - Assist with database design, query optimization, and performance tuning.  
  - Provide feedback on code quality and architecture.  
- **Communication Plan:**  
  - Daily check-ins for technical questions and progress updates.  
  - Use specific prompts to get actionable advice (e.g., “How can I optimize this SQL query?”).  
- **Dependencies:**  
  - Clear and specific prompts to ensure useful outputs.  
  - Your ability to implement the mentor’s suggestions.

### **2. AI Product Owner**
- **Role:** Define and prioritize project requirements, provide feedback on feature implementation, and ensure the project aligns with user needs.  
- **Expectations:**  
  - Help you refine user stories and prioritize features.  
  - Provide feedback on the user experience and functionality.  
  - Ensure the project meets its goals and success metrics.  
- **Communication Plan:**  
  - Weekly check-ins to review progress and adjust priorities.  
  - Use specific prompts to get feedback on features (e.g., “Does this implementation meet the user story requirements?”).  
- **Dependencies:**  
  - Clear and specific prompts to ensure useful outputs.  
  - Your ability to incorporate feedback into the project.

---

## Skill Tracking Plan
1. **Rust Programming:**  
   - **Proficiency Level Before:** None  
   - **Proficiency Level After:** Beginner  
   - **Evidence:**  
     - Implemented a functional to-do list application in Rust.  
     - Demonstrated understanding of ownership, borrowing, and error handling.

2. **Database Integration:**  
   - **Proficiency Level Before:** Intermediate  
   - **Proficiency Level After:** Intermediate  
   - **Evidence:**  
     - Integrated SQLite/PostgreSQL into the application.  
     - Optimized queries using indexing and connection pooling.

3. **Performance Optimization:**  
   - **Proficiency Level Before:** Beginner  
   - **Proficiency Level After:** Beginner  
   - **Evidence:**  
     - Benchmarked and optimized database queries.  
     - Implemented full-text search efficiently.

4. **AI Collaboration:**  
   - **Proficiency Level Before:** Beginner  
   - **Proficiency Level After:** Beginner  
   - **Evidence:**  
     - Effectively used AI tools to guide project development.  
     - Documented and implemented AI feedback to improve the project.

---

## Two-Week Timeline
### **Week 1: Core Features and Database Integration**
**Day 1–2: Setup and Basic Task Management**
- Set up the development environment (Rust, SQLite/PostgreSQL).  
- Implement basic task management features:  
  - Add, remove, and view tasks.  
  - Save and load tasks from the database.  
- Write unit tests for core functionality.

**Day 3–4: Priority Levels and Deadlines**
- Add priority levels (High, Medium, Low) to tasks.  
- Implement deadlines for tasks.  
- Display reminders for overdue tasks.  
- Optimize database queries for filtering and sorting tasks by priority and deadline.

**Day 5: Habit Tracking**
- Implement habit tracking:  
  - Allow users to create habits with a description and frequency (Daily/Weekly).  
  - Link habits to related tasks (e.g., “Exercise daily” → “Go for a run”).  
- Save and load habits from the database.

**Day 6: Integration and Testing**
- Integrate habits with tasks (e.g., suggest tasks based on habits).  
- Write integration tests for task and habit management.  
- Refactor code for readability and maintainability.

---

### **Week 2: Performance Optimization and Final Touches**
**Day 7–8: Performance Optimization**
- Optimize database queries using indexing.  
- Implement connection pooling to handle concurrent database access.  
- Benchmark query performance and refine as needed.

**Day 9: Full-Text Search**
- Implement full-text search for tasks and habits using SQLite’s `FTS5` or PostgreSQL’s full-text search.  
- Allow users to search tasks and habits by keyword (e.g., `search --keyword "groceries"`).  
- Optimize search performance.

**Day 10–11: Testing and Documentation**
- Write comprehensive unit and integration tests for all features.  
- Document the project:  
  - Write a detailed README with setup instructions and usage examples.  
  - Document the database schema and API (if applicable).  
  - Include user stories and success metrics.  
- Refactor code for production readiness (e.g., error handling, logging).

**Day 12: Final Refinement and Deployment**
- Perform final testing and bug fixes.  
- Prepare the project for deployment (e.g., package the application, create a release).  
- Share the project on GitHub or another platform for feedback.

---

## Next Steps
1. Set up communication channels with the AI tools (e.g., ChatGPT for Mentor, Claude for Product Owner).  
2. Define specific prompts and templates for check-ins (e.g., “Here’s my progress this week. Can you review and provide feedback?”).  

---
