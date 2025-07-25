# Interest Subscriber

A full-stack web application that helps users discover and subscribe to events based on their interests.

This monorepo contains both the frontend and backend codebases, along with shared configurations and documentation.


## 🛠️ Tech Stack

**Frontend:**
- Next.js
- React
- Tailwind CSS
- FullCalendar

**Backend:**
- Express.js
- MongoDB with Mongoose
- OpenAI JavaScript SDK (used for event categorization)

**Others:**
- TypeScript
- Context API for state management
- Axios for HTTP requests
- ESLint & Prettier for linting and formatting


## ⚙️ Getting Started

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/interest_subscriber.git
cd interest_subscriber
```

### 2. Install dependencies:

```bash
cd frontend
npm install

# Backend
cd ../backend
npm install
```

### 3. Run the application:

```bash
# Frontend
npm run dev

# Backend
npm run dev
```



### 📌  **Features**

## ✨ Features

- 🔍 Search and discover events based on interests
- 📅 Calendar view using FullCalendar
- 🧠 Uses OpenAI SDK to categorize and enrich event data
- 👥 Custom user interest profiles
- 🔐 Auth-ready (if using tokens or sessions