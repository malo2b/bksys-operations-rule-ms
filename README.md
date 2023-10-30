# bksys-operations-rule-ms

Operations Rule Micro Service

## Setup project

requirements:
- python 3.11
- poetry

### Install dependencies and load environment
```
poetry install && poetry shell
```

### Run application for development
```
uvicorn bksys-operations-rule-ms:app --reload --port 8081
```

## Lint project
```
poetry run flake8
```