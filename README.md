# Ete-service-backend


## Prerequisites

- Node.js (v18.x), also npm 
- PostgreSQL local setup


## Local development

- Update .env.local file 
```sh
PORT=4000

DB_HOST="localhost"
DB_USERNAME=<DB_USERNAME>
DB_PASSWORD=<DB_PASSWORD>
DB=<DB_NAME>
DB_PORT=5432
```


### 1. Install all packages
```sh
npm i
```

### 2. Start server
```sh
npm run start:local
```

server will start on http://localhost:4000/

