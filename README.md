# "Livsplaneraren" (The Life Planner / Productivity App)
A full-scale web application designed to help users manage their daily tasks, habits, and events, with support for user authentication. Developed as a collaborative group project.

[Live Demo](https://desireestrand.github.io/productivity-assistant-app/)

---

### Features
* **Authentication:** Secure user registration and login system using localStorage and sessionStorage, allowing multiple users to maintain unique profiles and persistent data.
* **Dynamic Dashboard:** A personalized overview featuring a greeting and a random inspirational quote fetched from an external REST API.
* **Todo Management:** Full CRUD functionality for tasks, including categories, deadlines, time estimates, and advanced filtering/sorting.
* **Habit Tracker:** Track daily routines and streaks with priority levels and repetition counters.
* **Event Planner:** A module for scheduling events with real-time chronological sorting (Upcoming vs. Past).

### Technical Implementation
I was primarily responsible for the **Authentication architecture** and the **Event Planner module**. Key technical highlights include:
* **Global State Management:** Used React Context API to ensure real-time synchronization of data across the entire application.
* **Chronological Logic:** Developed logic to compare event timestamps against a live state, ensuring the UI automatically updates as time passes.
* **Form Validation:** Implemented robust validation to ensure data integrity, such as preventing end-dates from being set before start-dates.

### Tech Stack
* **Frontend:** React, JavaScript (ES6+), CSS3
* **State Management:** React Context API
* **Build Tool:** Vite
* **Storage:** LocalStorage & SessionStorage
* **Collaboration:** Agile (SCRUM, Kanban), Git-flow, Trello, VS Code Live Share

### Project Methodology
* **Agile Workflow:** Divided into two sprints with daily standups and retrospectives.
* **Git Flow:** Used a strict branching strategy with feature branches and peer-reviewed pull requests.
* **Planning:** Wireframes designed in Figma and project tracking managed via Trello.

### Installation & Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/desireestrand/productivity-assistant-app.git](https://github.com/desireestrand/productivity-assistant-app.git)

    Install dependencies:
    Bash

    npm install

    Start the development server:
    Bash

    npm run dev

Developed by Desirée Strand and team.
