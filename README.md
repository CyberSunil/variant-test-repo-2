# Variant Test Repo 2

Second test repository for GitHub connector variant.

## Features

- Feature A: Authentication
- Feature B: Data Processing
- Feature C: API Integration

## API Keys (for testing)

```env
API_KEY=test-key-12345
SECRET_KEY=secret-abcde
```

## Database Schema

```sql
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    email VARCHAR(255) UNIQUE NOT NULL,
    created_at TIMESTAMP DEFAULT NOW()
);
```
