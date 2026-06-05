# Azure .NET Web App

This ZIP contains a simple ASP.NET Core web app for Azure App Service.

Recommended Azure settings:
- Publish: Code
- Runtime stack: .NET 8 (LTS)
- Operating System: Linux or Windows
- Pricing plan: Free F1 if available

File structure:
- AzureDotNetWebApp.csproj
- Program.cs
- wwwroot/index.html
- wwwroot/style.css
- wwwroot/script.js
- wwwroot/images/logo.svg

Health check:
- /health

Important:
If Azure still shows "Current Limit (Total VMs): 0", the issue is your Azure subscription quota,
not this ZIP file.
