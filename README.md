# go-python-sqlite-api-example

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