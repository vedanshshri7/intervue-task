
# Student/Teacher - Task

## Overview
This is a real-time polling application where teachers can create live polls and students can respond instantly. The frontend is developed using React with Vite as the build tool, and Socket.IO facilitates real-time communication between the server and connected clients.

## Features
- **Teacher Features**:
  - Create polls with options and set a timer for voting.
  - View real-time results as students vote.
  - View poll history.
  - Kick students out of the room.

- **Student Features**:
  - Join a poll room created by a teacher.
  - Vote in real-time on polls.
  - Redirect to a "kicked out" page if removed by the teacher.

## Tech Stack
- **React** (with Vite for fast development)
- **Socket.IO** (for real-time communication)
- **Bootstrap** (for styling)
- **Session Storage** (for session management)

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

