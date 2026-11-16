# Qafila AI

A fleet and trip management system for managing users, vehicles, trips, schedules, and reports.

## Features

- User management
- Vehicle management
- Trip creation and tracking
- Scheduling
- Reports

<!-- Add or remove features to match what the app actually does -->

## Tech Stack

- Backend: [ASP.NET Core / .NET version]
- Database: [SQL Server / PostgreSQL / other]
- Frontend: [Angular / React / Razor Pages / other]
- Other: [Entity Framework Core, authentication method, etc.]

## Screenshots

<!-- Add screenshots using fake data only -->

![Dashboard](docs/screenshots/dashboard.png)

## Getting Started

### Prerequisites

- [.NET SDK version]
- [Database engine and version]
- [Node.js version, if there's a frontend]

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/farhanKhanmazk/qafila-ai.git
   cd qafila-ai
   ```

2. Configure settings. Copy the example settings file and fill in your own values. Do not commit real secrets.

   ```bash
   cp appsettings.Example.json appsettings.Development.json
   ```

   Or use user secrets:

   ```bash
   dotnet user-secrets set "ConnectionStrings:Default" "<your-connection-string>"
   ```

3. Apply database migrations:

   ```bash
   dotnet ef database update
   ```

4. Run the app:

   ```bash
   dotnet run
   ```

   Then open `https://localhost:[port]` in your browser.

### Sample Data

The seed data uses fictional users, vehicles, and trips. No real personal data is included.

## Project Structure

```
qafila-ai/
├── src/            # Application code
├── tests/          # Unit and integration tests
└── docs/           # Documentation and screenshots
```

<!-- Update this to match your actual folder layout -->

## Roadmap

- [ ] [Next feature]
- [ ] [Next feature]

## License

MIT. See [LICENSE](LICENSE).
