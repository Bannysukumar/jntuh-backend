# JNTUH Results BACKEND

This FastAPI-based service provides access to student results, academic records, and backlog details. It integrates with PostgreSQL, Redis, and RabbitMQ for efficient data handling and messaging.

[![License](https://img.shields.io/github/license/Bannysukumar/jntuh-backend)](https://github.com/Bannysukumar/jntuh-backend/blob/main/LICENSE) [![Stars](https://img.shields.io/github/stars/Bannysukumar/jntuh-backend)](https://github.com/Bannysukumar/jntuh-backend/stargazers) [![Last commit](https://img.shields.io/github/last-commit/Bannysukumar/jntuh-backend)](https://github.com/Bannysukumar/jntuh-backend/commits/main) [![Build](https://img.shields.io/github/actions/workflow/status/Bannysukumar/jntuh-backend/deploy.yml)](https://github.com/Bannysukumar/jntuh-backend/actions)

## Overview

This FastAPI-based service provides access to student results, academic records, and backlog details. It integrates with PostgreSQL, Redis, and RabbitMQ for efficient data handling and messaging.


What is actually in the repository: `.github/`, `api/`, `assests/`, `config/`, `data/`, `database/`. GitHub reports the primary language as Python.

## Tech Stack

| Technology | Where it shows up |
|---|---|
| Python | Application or script code |
| API routes | Server endpoints in the api directory |

## Project Structure

```text
jntuh-backend/
├── .github/
├── api/
├── assests/
├── config/
├── data/
├── database/
├── messaging/
├── prisma/
├── scrapers/
├── service/
├── subscriptions/
├── utils/
├── .dockerignore
├── .env.example
├── Dockerfile
├── docker-compose.yml
├── entrypoint.sh
├── main.py
├── main2.py
├── prometheus.yml
├── pyrightconfig.json
├── requirements.txt
```

## Getting Started

```bash
git clone https://github.com/Bannysukumar/jntuh-backend.git
cd jntuh-backend
pip install -r requirements.txt
# Copy .env.example to .env and fill in the values that file lists.
```

## API

Endpoint files present in `api/`:

- `api/routes.py`

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

Licensed under GPL-3.0. See [LICENSE](LICENSE).

## Author

[Banny Sukumar](https://github.com/Bannysukumar)

- GitHub: [@Bannysukumar](https://github.com/Bannysukumar)
- Portfolio: [adepu-sukumar.vercel.app](https://adepu-sukumar.vercel.app/)
- LinkedIn: [Adepu Sukumar](https://www.linkedin.com/in/adepu-sukumar-59b423351)
