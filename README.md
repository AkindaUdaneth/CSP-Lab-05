# SE3022 - Case Study Project: Lab 05 ☁️

This repository contains the source code and deployment workflows for Lab 05: Deploying React Front-End and .NET Back-End to Microsoft Azure. 

It demonstrates a complete cloud-hosted full-stack architecture with automated Continuous Integration and Continuous Deployment (CI/CD) pipelines via GitHub Actions.

## 🚀 Live Deployments

* **Front-End (React):** https://polite-pond-09db4b000.6.azurestaticapps.net
* **Back-End (.NET API):** https://csp-lab05-backend-akinda-f3byepc3hgh8adf8.eastasia-01.azurewebsites.net/weatherforecast

## 🛠️ Technology Stack

**Front-End:** React.js (via Vite)
**Back-End:** ASP.NET Core Web API (.NET)
**Cloud Hosting:**
  * Azure Static Web Apps (Front-End)
  * Azure App Service (Back-End)
**CI/CD:** GitHub Actions

## 📂 Project Structure

The repository is divided into two main directories:

* `/frontend`: Contains the Vite + React source code.
* `/backend`: Contains the .NET Web API source code.
* `/.github/workflows`: Contains the YAML configuration files for Azure deployment automation.

## 💻 Local Development Setup

To run this project locally on your machine, follow these steps:

### Prerequisites
* [Node.js](https://nodejs.org/) installed
* [.NET SDK](https://dotnet.microsoft.com/download) installed

### Running the Front-End
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```
   npm install
   ```
3. Start the development server:
   ```
   npm run dev
   ```

### Running the Back-End
1. Open a new terminal and navigate to the backend directory:
   ```
   cd backend
   ```
2. Start the .NET API:
   ```
   dotnet run
   ```
