# React + PostgreSQL Dev Environment

**Services**  
- **db:** PostgreSQL  
- **pgadmin:** pgAdmin 4  
- **react-dev:** Node.js hot-reload (CRA)  
- **filebrowser:** Web UI for editing `/app`

## Quickstart

1. Copy `.env.example` → `.env` and fill in your secrets.  
2. Place your React source in `app/` (or start with `npx create-react-app app`).  
3. Run:
   ```bash
   docker-compose up -d
