# This is a Next.js + TypeScript + Prisma + Neon Postgres Starter

A Repo for building with **[Next.js](https://nextjs.org)**, **TypeScript**, **Prisma ORM**, and **[Neon Postgres](https://neon.com/)** (serverless Postgres). This starter project provides a solid foundation with a clean architecture, environment configuration, and database integration.

## ✨ Features

- ⚡ Next.js 15+ (App Router)
- 🔷 TypeScript for type safety
- 🗄️ Prisma ORM for database access)
- 🐘 Neon Postgres serverless database
- 🔐 Environment variable support

## Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later)
- [npm](https://www.npmjs.com/) or [pnpm](https://pnpm.io/)
- A [Neon](https://neon.tech/) account (free tier available)

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ZinHt9tHlaing/Nextjs-Prisma-Testing.git
cd your-repo-name
```

### 2. Install dependencies

```bash
npm install
```
or

```bash
pnpm install
```

### 3. Set up environment variables

```bash
DATABASE_URL="postgresql://<user>:<password>@<host>/<dbname>?sslmode=require"
```

### 4. Set up Prisma and the database

Generate Prisma client.
```bash
npx prisma generate
```

Run database migrations.
```bash
npx prisma migrate dev
```

Open Prisma Studio.
```bash
npx prisma studio
```

### 5. Run the development server

```bash
npm run dev
```
or

```bash
pnpm dev
```

📁 Project Structure
```
.
├── app
│   └── page.tsx
│
├── lib
│   └── prisma.ts
│
├── prisma
│   └── schema.prisma
│
├── public
│
├── .env
├── package.json
├── tsconfig.json
└── README.md
```

## 🐘 Neon Database

This project uses **Neon serverless PostgreSQL**.

Steps:

1. Go to https://neon.tech

2. Create a new project

3. Copy the connection string

4. Add it to .env
