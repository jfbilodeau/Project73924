# BoringApp

This project is a web application built using ASP.NET Core. It includes a simple web interface with a few pages and is designed to be deployed on Azure.

## Prerequisites

- .NET 8.0 SDK
- Azure account
- Git

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/jfbilodeau/Project73924.git
   cd Project73924
   ```

2. Restore the dependencies:
   ```sh
   dotnet restore
   ```

3. Build the project:
   ```sh
   dotnet build
   ```

## Usage

1. Run the application locally:
   ```sh
   dotnet run
   ```

2. Open a web browser and navigate to `https://localhost:7128` or `http://localhost:5093`.

3. To deploy the application to Azure, follow the steps in the GitHub Actions workflow defined in `.github/workflows/BoringApp.yaml`.
