# Flash Feed News App Authorization Backend

This repository contains the .NET Core backend for user authorization in the Flash Feed application.

## Installation

1. Clone the repository:

   ```bash
    git clone https://github.com/SKSritharan/flash-feed-backend.git

    cd flash-feed-backend
   ```

2. Set Up Database:

   Update the connection string in appsettings.json under the "DefaultConnection" section. After configuring the connection string, apply migrations and update the database:

   ```bash
   dotnet ef database update

   ```

3. Run the app:
   ```bash
   dotnet run
   ```
