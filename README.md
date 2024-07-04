# JWT-GIN

JWT authentication api using [gin](https://github.com/gin-gonic/gin?tab=readme-ov-file) web framework.

## Prerequisites

- [MySQL](https://dev.mysql.com/downloads/mysql/)
- Environment Variables
  - `DB_HOST`
  - `DB_DRIVER`
  - `DB_USER`
  - `DB_PASSWORD`
  - `DB_NAME`
  - `DB_PORT`
  - `API_SECRET`
  - `TOKEN_HOUR_LIFESPAN`

## Running the Server

### Using Justfile (Recommended)

```bash
just run
```
