# Elearn Platform: Next.js 13, React, Stripe, Mux, Prisma, Tailwind, Postgres

Key Features:

- Browse & Filter Courses
- Purchase Courses using Stripe
- Mark Chapters as Completed or Uncompleted
- Progress Calculation of each Course
- Student Dashboard
- Upload thumbnails, attachments UploadThing
- Rich text editor for chapter description
- Authentication using Clerk
- ORM using Prisma
  -Postgres Using Neon Db

### Prerequisites

**Node version 18.x.x**

### Cloning the repository

```shell

```

### Install packages

```shell
npm i
```

### Setup .env file

See .env.sample file

### Setup Prisma

Add Postgres Database (Neon Db)

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```
