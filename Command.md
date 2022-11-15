# ASP.Net Core 6 & 7

[official documentation](https://learn.microsoft.com/en-us/aspnet/core/security/cors?view=aspnetcore-7.0)

## 1. Install

### Download Link

> <https://dotnet.microsoft.com/en-us/download/dotnet>

### IDE

- `Rider` : The Cross-Platform .NET IDE from JetBrains`(Suggestion)`
- `Visual Studio` : Official suggest IDE
- `Visual Studio Code` : Visual Studio Code is a code editor redefined and optimized for building and debugging modern web and cloud applications.

### Base Command

- `dotnet new projectName` : create a new project, [Documentation here](<https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-new>)
- `dotnet watch run` : run and hot reload a project
- `dotnet run` : run

## 2. `Nuget` Package management

> `nuget` is a package management tools for .net like `npm`

### official website

> <https://www.nuget.org/packages/>

### Commands

- dotnet nuget install

### Common packages

- Database
  - `Npgsql` : for `PostgreSQL`, an open source ADO.NET Data
  - `Microsoft.Data.SqlClient` for `SQLServer`
  - `MySqlConnector` for `Mysql`
- Cache & MQ
  - `StackExchange.Redis` for `Redis`
  - `Confluent.Kafka` for `Kafka`
- Logger
  - `NLog` for logger
- OSS
  - `AWSSDK.S3` : for amazon s3
- ApiTest
  - `Swagger`
