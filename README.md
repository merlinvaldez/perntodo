# PERN Course Practice

Personal playground for learning the PERN stack (PostgreSQL, Express, React, Node) while following the tutorial video: https://www.youtube.com/watch?v=ldYcgPKEZC8&t=2s

## What's here
- REST API for todos (`server/`) with PostgreSQL storage.
- React client scaffolded with Create React App (`client/`).
- SQL seed in `server/database.sql` to create the `perntodo` database and `todo` table.

## Getting started
1) Install requirements: Node.js, npm, and PostgreSQL.
2) Create the database:
   - `psql -U <user> -f server/database.sql`
3) Install dependencies:
   - Backend: `cd server && npm install`
   - Frontend: `cd client && npm install`
4) Run the app:
   - API: `cd server && node index.js` (starts on port 5000)
   - Client: `cd client && npm start` (runs on port 3000 and can proxy to the API)

## Notes
- This repo is for personal learning; features will mirror the tutorial's progress.
- Feel free to adjust connection settings in `server/db.js` if your Postgres host/port differ.
