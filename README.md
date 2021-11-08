# Learning Objectives

---

- Use a source code management tool to integrate work in one codebase with multiple contributors
- Design and build an architecture that has a front-end application consuming data from a database-backed API
- Use Agile ceremonies including standups and retrospectives to develop software in a team
- Explain how Continuous Delivery / Integration fits in to the software development lifecycle

# Project Requirements

---

### Planning Stage

**Note: Please have one person fill in this form to provide links to your diagrams, stories, wireframes etc: https://docs.google.com/forms/d/1GB3i173mTpsIF4nL4CANUZ68_oholGbl-_G1fU661bA/edit**

- Must have User Stories for core application features
- Must have Entity Relationship Diagrams which are kept up to date
- Must have Wireframes for the frontend application
- Must have domain models for *some* User Stories
- Must have a GitHub project board, kept up to date, with the following columns:
    - `Backlog` containing all tasks (user stories)
    - `To Do` containing only the tasks chosen for the current sprint
    - `In Progress` containing tasks in progress
    - `Done` containing completed tasks

### Build Stage

---

- Project must have separate GitHub repositories for backend and frontend with these names:
    - `boolean-uk-final-group-project-server` for the backend
    - `boolean-uk-final-group-project-client` for the frontend
- Backend must use `Prisma`, `Express` and must not expose authentication information (e.g. using `dotenv`), with a fresh ElephantSQL database
- Frontend must use `React`
- Any `localhost` URL's must be provided by environment variables, not hard coded strings
- Project must have full CRUD
- Application must have a filter or search feature
- Client and Server must be built vertically, side by side

### Bonus Stage

---

- Use the domain models you designed to create some unit tests

# Assessment

---

- Students will work on their own branches and create Pull Requests to give each other feedback daily. Once group feedback has been given, a teacher will then review the PR and provide their feedback. When the PR has been marked as accepted by a teacher, the PR can be merged into the main branch. There will be no merging outside of PR's.

# Groups

---

1. Viktorija, Lana, Rafael
2. Bruce, Josh, Benedict
3. Emmanuel, Valentin, Connor

# Monday

---

- User Stories
- ERD's
- Wireframes
- Project Boards - *Backlog, To Do, In Progress, Done*
- Domain models
- Workshop on using git with branches and simple rebase, following this workflow:
    
    ```jsx
    git clone <repository>
    git checkout -b student_name/feature_name
    ... write code ...
    git add .
    git commit -m ""
    git pull origin main
    ... write code, resolve any conflicts ...
    git add .
    git commit -m ""
    git pull origin main
    ... resolve any conflicts ...
    git add .
    git commit -m ""
    git push origin student_name/feature_name
    // Create a PR
    ```
    