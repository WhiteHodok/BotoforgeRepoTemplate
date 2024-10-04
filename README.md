# BotoforgeRepoTemplate

## Зависимости

| Frame    |   Ver                                                |
|-----------|---------------------------------------------------------|
|aiogram  | 3.13.1 |
|asyncpg    | 0.29.0|
|pydantic   | 2.9.2 | 
|pydantic_settings    | 2.5.2 |
|python-dotenv  | 1.0.1 |
|SQLAlchemy    | 2.0.35 |
|Python   | 3.11.x or older |







## First steps in console after write models or changing models BEFORE USE

1. numero uno 

```
alembic -c src/alembic.ini revision --autogenerate
```

2. numero does

```
alembic -c src/alembic.ini upgrade head
```

