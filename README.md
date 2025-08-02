# Spend Smart 💰

**Spend Smart** is a full-stack budgeting tool crafted to help users monitor and manage their personal finances. It provides an intuitive interface for logging transactions, reviewing spending trends, and generating visual insights — all using modern web technologies.

---

## 🔥 Key Features

- **Manage Your Transactions**: Seamlessly add, modify, or remove income and expenses.
- **Category-Based Insights**: Group and review expenses by category to spot habits.
- **Track Financial History**: View long-term spending data for deeper understanding.
- **Interactive Charts**: Gain insights through dynamic, data-driven visualizations.
- **Customizable Icons**: Personalize categories with icon selections for clarity.

---

## 🛠 Tech Stack

### Frontend

- **Next.js 14** – Modern React framework with server-side rendering.
- **TypeScript** – Enhances JavaScript with type definitions.
- **Tailwind CSS** – Utility-first CSS framework for fast and responsive UI.
- **Shadcn UI** – Component system tailored for Tailwind and Next.js.
- **Recharts** – A powerful charting library for React-based applications.
- **React Query** – Handles API requests and caching for smooth user experience.

### Backend

- **Next.js API Routes** – Build backend functionality directly into the app.
- **Server Actions** – Manage complex server-side operations with ease.
- **SQLite / Vercel PostgreSQL** – Stores all financial records and user data.
- **Prisma** – Simplifies database interaction with an intuitive ORM.
- **Clerk** – Provides authentication and user session management.

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Setup Instructions

1. **Clone the repository**:

   ```bash
   git clone https://github.com/thala192/SpendSmart
   cd SpendSmart
Install project dependencies:

bash
Copy
Edit
npm install
# or
yarn install
Configure environment variables:

Create a .env file in the root directory and add:

Your Clerk API keys

Your database connection string

Initialize the database:

bash
Copy
Edit
npx prisma migrate dev --name init
Launch the development server:

bash
Copy
Edit
npm run dev
# or
yarn dev
Open your browser and go to:
http://localhost:3000

