# Picasso Project

Welcome to the Picasso Backend repository! This repository contains the backend of our application.

## Backend Setup

### Prerequisites

- Node.js (v16+)
- Git
- PostgreSQL (either your own installation or a Railway PostgreSQL instance)

### Clone the Backend Repository

```bash
git clone https://github.com/your-username/picasso-backend.git
cd picasso-backend
cd picassov2
```

### Install Backend Dependencies

```bash
npm install
```

### Setup Environment Variables

1. Create a .env file based on .env.template.

```bash
cp .env.template .env
```

2. Update the .env file with the environment variables:

```bash
DATABASE_URL=postgres://your-username:your-password@your-host:5432/your-database
JWT_SECRET=your_jwt_secret
PORT=3000
```
Replace DATABASE_URL, JWT_SECRET, and PORT with your actual database connection string, JWT secret, and desired port number respectively.

### Run the Backend

```bash
npm run dev
```
