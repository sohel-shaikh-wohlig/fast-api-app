# FAST API

### Activate virtual environment & run application

```
poetry shell
uvicorn app.main:app --reload
```

### Inital build and run

```
poetry install
poetry shell
alembic upgrade head
uvicorn app.main:app --reload
```
