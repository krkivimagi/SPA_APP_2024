1.1 Creating a postgresql database in a docker container:
    docker run -d -p 5432:5432 --name spaapp-db -e POSTGRES_PASSWORD=parool postgres
1.2 Add necessary package
    dotnet add package Npgsql.EntityFrameworkCore.PostgreSQL