# go-python-sqlite-api-example

![Maintained Label](https://img.shields.io/badge/Maintained-No-red?style=for-the-badge)
![Deprecated Label](https://img.shields.io/badge/Deprecated-Yes-lightgray?style=for-the-badge)
![Archived Label](https://img.shields.io/badge/Archived-Yes-lightgray?style=for-the-badge)

> Code Migrated to [andy-jarombek-research](https://github.com/AJarombek/andy-jarombek-research)

## Overview

Basic example API that uses Python & Go to read from a SQLite database and return a JSON response.

### Commands

**Python API**

```bash
# Set your desired port
PORT=5001

# Start the API
cd python
PORT=$PORT docker-compose up
```

```bash
# Query the API

curl localhost:$PORT/employees
```

**Go API**

```bash
# Set your desired port
PORT=5002

# Start the API
cd go
PORT=$PORT docker-compose up
```

```bash
# Query the API

curl localhost:$PORT/employees
```
