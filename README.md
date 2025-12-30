# FastAPI Hello World

A minimal FastAPI application to get started with Python web APIs.

## Requirements

- Python 3.12+
- [uv](https://github.com/astral-sh/uv) (Python package manager)

## Setup

```bash

# Install dependencies
uv sync
```

## Run

```bash
uv run fastapi dev main.py
```

The server starts at:
- **API:** http://127.0.0.1:8000
- **Interactive Docs:** http://127.0.0.1:8000/docs

## API

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | `/`      | Returns hello world message |

**Response:**
```json
{"message": "Hello, World!"}
```

## Project Structure

```
fastapi-hello/
├── main.py          # FastAPI application
├── pyproject.toml   # Project configuration
├── uv.lock          # Locked dependencies
└── README.md
```
