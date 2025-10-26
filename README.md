🚀 Next.js + Drizzle + Auth.js Auth Template

A modern, production-ready authentication starter built with Next.js, Drizzle ORM, and Auth.js.
This template provides a clean and scalable foundation for integrating secure authentication, type-safe database access, and API routes in full-stack web applications.

🧩 Tech Stack

Next.js 14+ – App Router, API routes, and server-side rendering

Drizzle ORM – Type-safe, schema-driven database migrations and queries

Auth.js (NextAuth) – Secure authentication with credentials or OAuth providers

TypeScript – End-to-end type safety

PostgreSQL / MySQL / SQLite – Supported databases

✨ Features

🔐 Authentication Ready – Pre-configured Auth.js setup (Credentials & OAuth)

🧱 Type-safe ORM – Define and query schema with Drizzle

🗂️ Clean Project Structure – Scalable, maintainable folder organization

🔄 Session Management – Built-in session and route protection

⚙️ Environment Ready – Works seamlessly across environments

🧪 Developer Friendly – Perfect base for SaaS apps, dashboards, or internal tools

🛠️ Getting Started
1. Clone the Repository
git clone https://github.com/yourusername/nextjs-drizzle-auth-template.git
cd nextjs-drizzle-auth-template

2. Install Dependencies
npm install
# or
yarn install

3. Configure Environment Variables

Create a .env.local file in the root directory:

DATABASE_URL="your_database_url_here"
NEXTAUTH_SECRET="your_nextauth_secret"
NEXTAUTH_URL="http://localhost:3000"

4. Run Database Migrations
npx drizzle-kit push

5. Start the Development Server
npm run dev
# or
yarn dev

🧩 Folder Structure
├── app/
│   ├── api/
│   │   └── auth/
│   ├── (protected)/
│   └── layout.tsx
├── drizzle/
│   ├── schema.ts
│   └── migrations/
├── lib/
│   ├── auth/
│   ├── db/
│   └── utils/
├── .env.local
├── package.json
└── README.md

🧰 Scripts
Command	Description
npm run dev	Start the development server
npm run build	Create an optimized production build
npm run start	Run the production server
npx drizzle-kit push	Apply database migrations
npx drizzle-kit studio	Visualize and manage your DB
📚 Learn More

Next.js Documentation

Drizzle ORM Documentation

Auth.js Documentation

🤝 Contributing

Contributions are welcome!
Feel free to open an issue or submit a pull request to improve this starter.

🪪 License

This project is licensed under the MIT License – feel free to use and modify it for your own projects.