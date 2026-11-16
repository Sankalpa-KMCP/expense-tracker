# Expense Tracker

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-18%2B-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4-000000?style=flat-square&logo=express&logoColor=white)](https://expressjs.com/)
[![SQLite](https://img.shields.io/badge/Database-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)](https://www.sqlite.org/)

A lightweight web application for recording daily expenses with multi-currency tracking, real-time exchange rates, and SQLite data persistence.

---

## Features

- **Multi-Currency Tracking** — Log transactions in LKR and USD with live exchange rate integration.
- **Embedded Database** — Persistent storage using local SQLite (`expenses.db`).
- **Interactive Utility Tools** — Built-in quick calculator and live currency converter inside the dashboard.
- **Categorization & Companion Analytics** — Group expenses by category (Food, Transport, Bills, etc.) and identify top spending companions.

---

## REST API

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/api/expenses` | Fetch all logged transactions (ordered newest first) |
| `POST` | `/api/expenses` | Record a new expense |
| `DELETE` | `/api/expenses/:id` | Remove an expense by ID |

---

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm

### Installation & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Sankalpa-KMCP/expense-tracker.git
   cd expense-tracker
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the application:
   ```bash
   node server.js
   ```

4. Open `http://localhost:3000` in your browser.

---

## License

This project is licensed under the [MIT License](LICENSE).
