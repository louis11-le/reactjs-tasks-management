# Task Management Application

## Introduction
Hello! My name is Louis Le.

This project is a full-stack task management application that I developed. The back-end API is built using NestJS, and the front-end is developed with React.js.

## Deployment

### Front-end Application
The front-end application is deployed and accessible at:
- [React.js Task Management](https://louis11-le.github.io/reactjs-tasks-management/#/)

### Back-end API
The back-end API is deployed and available at:
- [NestJS API](https://app-tasks-management-3644f0514b3a.herokuapp.com)

## Getting Started
To get started with the project locally, follow the instructions below.

### Prerequisites
- Node.js
- npm or yarn
- Docker (optional, for running the database)

### Running the Back-end
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd backend
   ```

2. Install dependencies:
   ```bash
   yarn install
   ```

3. Start the application:
   ```bash
   yarn start:dev
   ```

### Running the Front-end
1. Navigate to the front-end directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   yarn install
   ```

3. Start the application:
   ```bash
   yarn start
   ```

## Docker Setup
If you prefer to use Docker for the database, you can set it up with the following command:

```bash
docker run --name postgres-nest -p 5432:5432 -e POSTGRES_PASSWORD=postgres -d postgres
```
