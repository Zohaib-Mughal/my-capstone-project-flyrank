# Flyrank AI Capstone Project

Capstone project for the **AI Engineering track** at Flyrank. This repository will host a full-stack web application built as part of the internship program.

## Overview

<!-- TODO: Replace with a 2–3 sentence description of what the app does and who it is for. -->

This project is under active development. Check back for updates as features are implemented.

## Tech Stack

| Layer    | Technology |
| -------- | ---------- |
| Frontend | React      |
| Backend  | Node.js, Express |
| Database | MongoDB    |

## Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- [MongoDB](https://www.mongodb.com/) (local instance or [MongoDB Atlas](https://www.mongodb.com/cloud/atlas))
- npm or yarn

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Zohaib-Mughal/my-capstone-project-flyrank.git
cd my-capstone-project-flyrank
```

### 2. Install dependencies

```bash
# Frontend
cd client && npm install

# Backend
cd ../server && npm install
```

### 3. Configure environment variables

Create a `.env` file in the project root (or in `server/`, depending on layout):

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

> **Note:** Never commit `.env` files. See `.gitignore` for excluded paths.

### 4. Run the application

```bash
# Start the backend (from server/)
npm run dev

# Start the frontend (from client/)
npm run dev
```

<!-- TODO: Add actual URLs/ports once the app is scaffolded. -->

## Project Structure

<!-- TODO: Update once the codebase is in place. -->

```
my-capstone-project-flyrank/
├── client/          # React frontend
├── server/          # Express API
├── .gitignore
├── CLAUDE.md        # AI assistant project guidelines
└── README.md
```

## Development

- Use **ES6+** syntax and **async/await** for asynchronous code.
- Prefer small, functional React components.
- Follow [Conventional Commits](https://www.conventionalcommits.org/) for commit messages.

## License

See [LICENSE](./LICENSE) for details.

## Author

**Zohaib Mughal** — [GitHub](https://github.com/Zohaib-Mughal)
