
# Student/Teacher - Task

## Overview
This is a real-time polling application where teachers can create live polls and students can respond instantly. The frontend is developed using React with Vite as the build tool, and Socket.IO facilitates real-time communication between the server and connected clients.

## Features

- **For Teachers**:
  - Launch polls with multiple options and a countdown timer.
  - Monitor live voting results as they come in.
  - Access a history of previously created polls.
  - Remove students from the poll room when necessary.

- **For Students**:
  - Enter a poll session using a room code shared by the teacher.
  - Submit votes in real time as polls appear.
  - Automatically redirected to a "kicked out" page if removed by the teacher.

## 🛠 Tech Stack

- **React** (leveraging Vite for blazing-fast builds)
- **Socket.IO** (enabling real-time bidirectional communication)
- **Bootstrap** (used for responsive and clean UI design)
- **Session Storage** (to manage session-based user state)

---

## Frontend Setup

### Prerequisites
Make sure you have the following installed:
- Node.js (developed with 22.5.1)
- npm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vedanshshri7/intervue-task.git
   
   cd intervue-poll-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

