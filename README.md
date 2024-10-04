# DBtest

## First steps in console after write models or changing models BEFORE USE

1. numero uno 

```
alembic -c src/alembic.ini revision --autogenerate
```

2. numero does

```
alembic -c src/alembic.ini upgrade head
```

