# ProductLaunch

**Attribution:** This Project is derived from [Modernizing ASP .NET Sample App](https://github.com/docker/labs/tree/master/windows/modernize-traditional-apps/modernize-aspnet) repository which is originally published under Apache 2 License. This project is available under the same license, terms for which are available in this repo.

This is an ASP .NET Core application which runs with Kestrel web server and connects to a MSSQL backend.

## Architecture

![architecture](arch.jpg)

## Running the Backend and Frontend Modules Separately

### Backend

1. Navigate to the `ProductLaunch.Model` directory.
2. Run the following command to start the backend:
   ```
   dotnet run
   ```

### Frontend

1. Navigate to the `ProductLaunch.Web` directory.
2. Run the following command to start the frontend:
   ```
   dotnet run
   ```

## Running Unit Tests

Unit tests are included for both the backend and frontend code. The tests use NUnit and cover a minimum of 80% of the code.

To run the unit tests, navigate to the test project directory (e.g., `ProductLaunch.Model.Tests`) and run the following command:
```
dotnet test
```
