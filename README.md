# Redis-Vault

## Project Overview

A hands-on learning sandbox for Redis integration with a **Node.js / TypeScript** backend.
The project covers Redis fundamentals, REST API design, Docker orchestration, and basic testing workflows.

## Features

- Redis connection management (connect, disconnect, retry)
- CRUD REST API endpoints backed by Redis
- Docker Compose setup for Redis and the app
- Full TypeScript codebase with strict type-checking
- Postman collection for manual API testing
- Environment variable configuration via .env

## Tech Stack

| Layer       | Technology               |
|-------------|--------------------------|
| Runtime     | Node.js                  |
| Language    | TypeScript               |
| Database    | Redis                    |
| Containers  | Docker / Docker Compose  |
| Build       | tsc (TypeScript compiler)|

## Project Structure

```
5_Redis/
â”œâ”€â”€ src/                  # TypeScript source files
â”œâ”€â”€ examples/             # Usage examples / snippets
â”œâ”€â”€ docker-compose.yml    # Redis + app container setup
â”œâ”€â”€ .env.example          # Environment variable template
â”œâ”€â”€ tsconfig.json         # TypeScript compiler config
â”œâ”€â”€ package.json          # Node.js project manifest
â””â”€â”€ postman-test.txt      # Postman API test notes
```
