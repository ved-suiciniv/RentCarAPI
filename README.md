﻿# Rent a car API (.NET)
### The project has the goal to build a API that provide the datas from a store of rent cars.
---
#### The goals
- [ ] Build a API in .NET (in progress);
- [x] Create a new User;
- [x] Create a new Car;
- [x] Create a new Register;
- [ ] Update a Register;
- [ ] Update a Car;
- [ ] Update a User;
- [x] Provide Registers data (registes of cars rented);
- [x] Provide Users data;
- [x] Provide Cars data;
- [x] SQL Server; 
- [x] User Authentication (You need to create a login in the SQL Server).
---
#### The technologies
- .NET Core;
- SQL Server (you can use another DB, but you need to change the [1]);
- Visual Studio (but you can you Visual Studio Code);
- Postman (to test the requests).
---
#### Dependencies
- Microsoft.EntityFrameworkCore;
- Microsoft.EntityFrameworkCore.Design;
- Microsoft.EntityFrameworkCore.SqlServer [1];
---
#### Migrations
- "dotnet toll install --global dotnet-ef" => to install the "dotnet-ef if you dont have installed in your PC";
- "dotnet ef migrations add InitialMigration" => to add a new migration with the name "InitialMigration";
- "dotnet ef migrations remove" => remove all migrations created; 
- "dotnet ef database update" => create the DB or update the tables from the DB.
---
```diff
 This project it was create only to pratice .NET.
 ```
