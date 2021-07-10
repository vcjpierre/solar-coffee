# SolarCoffee

Web application for a coffee roaster called Solar Coffee using .NET Core, Vue and PostgreSQL.

<p align="center">
<img src="https://res.cloudinary.com/dbpwbtkis/image/upload/v1625899733/screencapture-localhost-8080-i_vasyt7.png" />
</p>

## About 🧐

- REST API development with .NET Core

- Front-End development with Vue.js with TypeScript

- Using SQL with a PostgreSQL database

- Unit testing with Jest, xUnit

- End-to-end testing with Cypress

## Requeriments

- [Docker](https://www.docker.com/get-started) (Optional)
- [.NET Core](https://dotnet.microsoft.com/download/dotnet/3.1)
- [Vue.js](https://vuejs.org/v2/guide/)
- [PostgreSQL](https://www.postgresql.org/)

## Getting started 🚀

### Backend

Create PostgreSQL database:
```
docker-compose up
```

Build the project:
```
dotnet build
```

Run all migrations:
```
cd SolarCoffee.Data/
dotnet ef --startup-project ../SolarCoffee.Api database update
```

Run API project
```
cd SolarCoffee.Api/
dotnet run
```

Then go to http://localhost:5001/api/products

### Frontend

Install dependencies and run the application:
```
cd SolarCoffe.Frontend/
yarn
yarn serve
```

Then navigate to http://localhost:8080/
