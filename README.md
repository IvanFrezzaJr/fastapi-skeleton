


## migration
iniciar arquivo de migracoes
```bash
alenbic init migrations
```

gerar uma migracao
```bash
alembic revision --autogenerate -m "create users table"
```


aplicar migracoes
```bash
alembic upgrade head
```