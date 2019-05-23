# ContosoUniversity on ASP.NET Core with .NET Core

Contoso University, the way Jimmy Bogard would write it.

To run, create a database "ContosoUniversity" and run the SchemaAndData.sql script against it. Modify the connection string in appsettings and go!

## Things demonstrated

- CQRS and MediatR
- AutoMapper
- Feature folders and vertical slices
- HtmlTags
- Entity Framework Core

## How to run

First run the build script (Build.ps1). This will set up the local database using RoundhousE. Open the solution and run!

## Prior art

This is a fork of <https://github.com/jbogard/ContosoUniversityDotNetCore>
repository with following changes:

- source code moved under `src`
- build scripts moved under `build`
- migrated to .NET Core 2.2
- build script for Linux
- using Docker Compose for integration tests and running the application in local environment
