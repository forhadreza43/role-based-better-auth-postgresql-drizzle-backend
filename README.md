# server

Clone the repo to local

```bash
git clone https://github.com/forhadreza43/role-based-better-auth-postgresql-drizzle-backend.git
```

Install dependencies:

```bash
bun install
```

Necessary environment variable

```text
DATABASE_URL=your database connection string
BETTER_AUTH_SECRET=your secret
BETTER_AUTH_URL=backend URL of your app
FRONTEND_URL=frontend URL of your app
GOOGLE_CLIENT_ID=Your clientID
GOOGLE_CLIENT_SECRET=Your client secret

```

To run:

```bash
bun run dev
```

To update schema

```bash
bun run db:generate
```

To sync new schema to database

```bash
bun run db:migrate
```
