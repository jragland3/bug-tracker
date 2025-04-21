# Bug Tracker App
<p>This is a project meant to demonstrate full stack development skills as well as concepts such as testing (Unit, Component, Integration, E2E, etc.), containerization, etc.

## Backend:  Node.js + Express + TypeScript
Directory: `server`
Uses:
- Node
- Express
- TypeScript
- Jest + Supertest for testing

### Starting server
#### Dev mode
- Run using `npm run dev`

#### Production (or for deployment like Docker)
`npm run build`    # Compiles TypeScript → JavaScript into /dist
`npm start`        # Runs the compiled server

### Resetting the database
- `npx prisma generate`
- `npx prisma migrate reset --force`

## Frontend:  React + TypeScript + Vite
Directory: `client`
Uses:
- Node
- React + Vite
- TypeScript
- Vitest + React Testing Library for testing

