# .NET API Authentication

This repository contains a .NET Core API project with authentication features. The project is designed to demonstrate how to implement and manage authentication in a .NET API application.

## Features

- **User Registration**: Allows new users to register by providing necessary details.
- **User Login**: Authenticates users using JWT (JSON Web Tokens).
- **Token Refresh**: Refreshes JWT tokens to maintain user sessions.
- **Secure Endpoints**: Protects API endpoints using authentication and authorization mechanisms.

## Getting Started

### Prerequisites

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) or any other supported database

### Running the Application

1. Run the application:

    ```sh
    dotnet run
    ```

2. The API will be available at `https://localhost:5001` or `http://localhost:5000`.

## API Endpoints

### Authentication

- **Register**: `POST /api/auth/register`
- **ResetPassword**: `PUT /api/auth/reset-password`
- **Login**: `POST /api/auth/login`
- **Refresh Token**: `POST /api/auth/refresh-token`

### Protected Endpoints

- **Get User Info**: `GET /api/user`

## License

This project is licensed under the MIT License.
