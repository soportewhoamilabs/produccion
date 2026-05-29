# produccion

Repositorio de una aplicación web en producción con frontend, API y base de datos PostgreSQL.

Stack
Frontend: React + Vite

Backend: Node.js + Express

DB: PostgreSQL + Prisma

Infra: Docker Compose + Nginx

CI: GitHub Actions

Estructura
bash
prod-web-repo/
├─ apps/
│  ├─ web/
│  └─ api/
├─ infra/
│  └─ nginx/
├─ scripts/
├─ docs/
├─ .github/workflows/
├─ docker-compose.yml
├─ .env.example
└─ package.json
Cómo levantar
bash
cp .env.example .env
docker compose up --build
Servicios
web: http://localhost:5173

api: http://localhost:3000

proxy nginx: http://localhost:8080

postgres: localhost:5432
