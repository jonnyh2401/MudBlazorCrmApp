# MudBlazor CRM App

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/donpotts/MudBlazorCrmApp/MudBlazorCrmApp.yml?logo=github)

Blazor WASM Sample CRM application using MudBlazor

## Overview

This repository contains an ASP.NET Core application with a Blazor WebAssembly (WASM) UI in .NET 9. It also includes user authentication using ASP.NET Core 9 Identity, uses Entity Framework Core SQLite as the database, and supports OData for efficient querying.

## Features

- ASP.NET Core Kestrel web server: A robust and high-performance server.
- Blazor WASM UI: A modern web UI framework for .NET.
- MudBlazor components: Using side navigation.
- Swagger UI: An interactive documentation for your API.
- ASP.NET Core 9 Identity: A membership system that adds login functionality to your application.
- Entity Framework Core SQLite: A lightweight database provider for Entity Framework Core.
- OData Support: A standard for building and consuming RESTful APIs.
- Kanban Todo Tasks: A simple Kanban board to manage tasks.

## Getting Started

### Prerequisites

- Visual Studio 2022
- .NET 9
- ASP.NET Core
- Blazor WASM
- Swagger UI
- ASP.NET Core 9 Identity
- MudBlazor Components
- Entity Framework Core SQLite
- OData

### Installation

1. Clone the repo
  git clone https://github.com/donpotts/MudBlazorCrmApp.git
2. Install .NET packages
3. Install MudBlazor packages
4. Install any missing packages
5. dotnet restore
   
## Authentication

This application uses ASP.NET Core 9 Identity for user authentication. To log in, navigate to the login page and enter your credentials.

Administrator

Username:  adminUser@example.com

Password:  testUser123!

Normal user

Username:  normalUser@example.com

Password:  testUser123!

## OData Support

This application supports OData for efficient querying. You can use OData query options on the API endpoints.

## Contact

Don.Potts@DonPotts.com
