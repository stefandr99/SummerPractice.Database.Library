# Summer Practice Library

Library .NET 10 API created with purpose of learning Entity Framework and repository pattern.

## I. Setup

### I.1. Create database

1. Go to ```scripts``` folder
2. Open powershell in this folder
2. Run: ```.\createDatabase.ps1```

### I.2. Install dotnet tool

1. Open powershell
2. Run ```dotnet tool install --global dotnet-ef```
3. Check ```dotnet ef --version```

### I.3. Run first migration

1. In Visual Studio, open Library solution
2. Right click on Library.Infrastructure project
3. Click "Open in terminal"
4. Run in terminal ```dotnet ef migrations add InitialMigration```
5. Check migration in ```Migrations``` folder
6. Run ```dotnet ef database update``` to apply migration
7. In case migrations do not work: 
    - copy content of file ```createDatabases.sql```
    - paste in SSMS query tab
    - run / F5

