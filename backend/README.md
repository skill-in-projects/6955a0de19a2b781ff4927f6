# Backend API

This is the backend API for the project.

## Database Connection

The API connects to the database using the `DATABASE_URL` environment variable provided by Railway.

## API Endpoints

### TestProjects
- GET `/api/test` - Get all test projects
- GET `/api/test/{id}` - Get a specific test project by ID
- POST `/api/test` - Create a new test project
- PUT `/api/test/{id}` - Update a test project
- DELETE `/api/test/{id}` - Delete a test project

## Running Locally

1. Set the `DATABASE_URL` environment variable with your database connection string
2. Run `dotnet restore`
3. Run `dotnet run`
4. The API will be available at `http://localhost:5000`
5. Swagger documentation is available at `http://localhost:5000/swagger`

## Deployment

This backend is deployed on Railway. The `DATABASE_URL` environment variable is automatically set by Railway.


## API URL

Your API is available at: https://railway.app/project/021c6c50-6805-4c2a-b1f4-cb3794a35ace
