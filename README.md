Spend Smart 💰

Spend Smart is a full-stack budgeting tool crafted to help users monitor and manage their personal finances. It provides an intuitive interface for logging transactions, reviewing spending trends, and generating visual insights — all using modern web technologies.

🔥 Key Features
Manage Your Transactions: Seamlessly add, modify, or remove income and expenses.
Category-Based Insights: Group and review expenses by category to spot habits.
Track Financial History: View long-term spending data for deeper understanding.
Interactive Charts: Gain insights through dynamic, data-driven visualizations.
Customizable Icons: Personalize categories with icon selections for clarity.

🛠 Tech Stack
Frontend
Next.js 14 – Modern React framework with server-side rendering.
TypeScript – Enhances JavaScript with type definitions.
Tailwind CSS – Utility-first CSS framework for fast and responsive UI.
Shadcn UI – Component system tailored for Tailwind and Next.js.
Recharts – A powerful charting library for React-based applications.
React Query – Handles API requests and caching for smooth user experience.

Backend
Next.js API Routes – Build backend functionality directly into the app.
Server Actions – Manage complex server-side operations with ease.
SQLite / Vercel PostgreSQL – Stores all financial records and user data.
Prisma – Simplifies database interaction with an intuitive ORM.
Clerk – Provides authentication and user session management.

🚀 Getting Started
Prerequisites

Node.js version 14 or newer
npm or yarn installed

Setup Instructions
Clone the repository:

bash
Copy
Edit
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

Create a .env file and provide your Clerk credentials and database URLs.

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
Visit http://localhost:3000 to start using the app.

💡 How to Use
🏦 Transactions Page
Add new financial records with details like amount, category, and date.

Edit or remove entries as needed for accurate tracking.

📊 Category Analytics
Analyze spending trends per category.

Filter records to narrow down financial insights.

🧮 Financial Overview
Explore changes in income and expenses over time.

Use graphs to detect behavioral patterns and shifts.

📈 Visual Charts
Access the Charts section for graphical breakdowns.

Experiment with various visual formats for deeper insights.

😁 Category Icons
Assign meaningful icons to your spending categories.

Enhance the visual clarity of your budgeting dashboard.