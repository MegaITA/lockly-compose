# Lockly-Compose
---
Tutto ciò che serve per startare Lockly-BOT e Lockly-DB, sarà sufficiente clonare la repo, creare un file .env secondo lo schema di seguito ed eseguire `docker compose up -d` all'interno della cartella.

### File .env

```
DB_USER=lockly (mettere così per facilità)
DB_PASS=lockly2023 (mettere così per facilità)
DB_NAME=lockly (mettere così per facilità)
DB_HOST=lockly-db (mettere così per facilità)
STATE_SIZE=3 (1-3, più alto è meno random sono i messaggi)
MAX_MESSAGES=10000000 (numero massimo di messaggi che salva per ogni gruppo)
```

### Requisiti
- Docker
- Docker compose