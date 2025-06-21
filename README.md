# WiredBrain API

A simple ASP.NET Core Web API for managing inventory, featuring continuous integration and deployment (CI/CD) with GitHub Actions and deployment to Azure App Service.

## Features

- RESTful API built with ASP.NET Core 8.0  
- Inventory management service (`IInventoryService`)  
- Swagger/OpenAPI documentation enabled in development  
- Automated build, test, and deploy using GitHub Actions  
- Azure App Service deployment  
- Health check endpoint `/health` for monitoring  

## Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)  
- Azure account with App Service  
- GitHub repository with GitHub Actions enabled  

### Running Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd WiredBrainApi.Web
