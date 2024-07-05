# JWT-GIN

JWT authentication api using [gin](https://github.com/gin-gonic/gin?tab=readme-ov-file) web framework.

## Prerequisites

- [MySQL](https://dev.mysql.com/downloads/mysql/)
- Environment Variables
  - `DB_HOST`: Database Host Name
  - `DB_DRIVER`: Database Driver Name
  - `DB_USER`: Database Username
  - `DB_PASSWORD`: Database Password
  - `DB_NAME`: Database Name
  - `DB_PORT`: Database Port
  - `API_SECRET`: API Secret text
  - `TOKEN_HOUR_LIFESPAN`: Token Lifespan (in hours)

## Running the Server

### Using Justfile (Recommended)

```bash
just run
```
