# ProductCatalog


## Commands

### Executed on project:
- Installed "Microsoft.EntityFrameworkCore.Sqlite" (NuGet Package Manager)
- dotnet add package Microsoft.EntityFrameworkCore
- dotnet add package Microsoft.AspNetCore.Mvc
- dotnet add package Flunt
- dotnet add package Microsoft.AspNetCore.ResponseCompression
- dotnet add package Swashbuckle.AspNetCore (this is to document the API - here we are using Version 4.0.1, so you can execute: dotnet add package Microsoft.AspNetCore.ResponseCompression --version 4.0.1)

### Database/Migrations:
- dotnet ef migrations add Initial
- dotnet ef database update


### To execute:
- dotnet watch run


### Api Documentation:
- Access to see on UI: http://localhost:5000/swagger
- Access to see json: http://localhost:5000/swagger/v1/swagger.json