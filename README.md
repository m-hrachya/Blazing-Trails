# Blazing Trails

Blazing Trails is a Blazor-based web application for discovering, exploring, and managing hiking trails.
The project demonstrates a full-stack Blazor architecture with a backend API, client application,
shared libraries, and tests.

## Project Structure

- **BlazingTrails.Api** – ASP.NET Core Web API backend  
- **BlazingTrails.Client** – Blazor WebAssembly frontend  
- **BlazingTrails.ComponentLibrary** – Reusable UI components  
- **BlazingTrails.Shared** – Shared models and utilities  
- **BlazingTrails.Tests** – Automated tests  
- **BlazingTrails.sln** – Solution file  

## Features

- Browse and view hiking trails  
- Create and manage trail data  
- Shared models between client and server  
- Component-based UI architecture  

## Requirements

- .NET SDK 8.0 or later  
- Visual Studio 2022 / VS Code / Rider  

## Build and Run

Clone the repository and build the solution:

```bash
dotnet build
```

Run the API:

```bash
dotnet run --project BlazingTrails.Api
```

Run the Blazor client:

```bash
cd BlazingTrails.Client
dotnet watch
```

Open your browser at:

```
https://localhost:5001
```

## Testing

Run all tests with:

```bash
dotnet test
```

## Contributing

1. Fork the repository  
2. Create a feature branch  
3. Commit your changes  
4. Push to your branch  
5. Open a Pull Request  

## License

This project is licensed under the MIT License.
