# go-python-sqlite-api-example

## Overview

Basic example API that uses Python & Go to read from a SQLite database and return a JSON response.

### Commands

**Python API**

```bash
# Start the API

cd python
docker-compose up
```

```bash
# Query the API

curl localhost:5000/employees
```

**Go API**

```bash
# Start the API

cd go
docker-compose up
```

```bash
# Query the API

curl localhost:5001/employees
```