# Ejemplo de .env

Copia este archivo como `.env` en la raíz del repo y completa los valores.

```dotenv
# --- Obligatorio ---
OPENAI_API_KEY=

# --- Requerido si usas memoria en Supabase ---
SUPABASE_URL=
SUPABASE_SERVICE_ROLE_KEY=

# --- Opcional: checkpointing LangGraph (Postgres) ---
SUPABASE_DB_URL=

# --- Opcional: Redis (event streaming) ---
REDIS_URL=redis://localhost:6379/0

# --- Opcional: LangSmith ---
LANGSMITH_API_KEY=
LANGSMITH_PROJECT=chinook-multiagent
LANGCHAIN_TRACING_V2=true
LANGCHAIN_ENDPOINT=https://api.smith.langchain.com

# --- Opcional: SQLite (override) ---
SQLITE_DB_PATH=./data/Chinook.sqlite
```

