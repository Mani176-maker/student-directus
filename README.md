# student-directus

Directus admin panel for the Student Print Service.

## Overview
This project deploys a Directus backend on Render, connected to a PostgreSQL database.  
It provides an admin panel to manage student print service data.

## Setup
1. Clone this repository.
2. Ensure you have a PostgreSQL instance running on Render.
3. Update `render.yaml` with your database connection details.
4. Push this repo to GitHub.
5. Connect the repo to Render and deploy.

## Files
- `package.json` → installs Directus and defines start/build scripts.
- `render.yaml` → Render deployment configuration.
- `.gitignore` → ignores environment files, logs, and dependencies.
- `README.md` → project documentation.

## Deployment
Render will:
- Run `npm install` to install Directus.
- Run `directus bootstrap` to initialize.
- Run `directus start` to launch the admin panel.

Once deployed, Directus will be available at your Render service URL.
