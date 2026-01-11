# .NET 8 and React 19 with PostgreSQL and Observability
A production-grade dotnet new template that scaffolds a complete full-stack application with .NET 8 Web API, React frontend, PostgreSQL database, and Nginx reverse proxy, including monitoring stack (Prometheus, Grafana, cAdvisor, Node Exporter) with Alpine-based multistage Docker builds, security hardening, and CI/CD-ready configuration.

## Features
- **Backend**: .NET 8 Web API with Entity Framework Core for PostgreSQL
- **Frontend**: React application created with Create React App
- **Database**: PostgreSQL with Docker Compose setup
- **Reverse Proxy**: Nginx for serving the React app and proxying API requests
- **Observability**: Integrated monitoring stack with Prometheus, Grafana, cAdvisor, and Node Exporter
- **Dockerized**: Multistage Docker builds for optimized images

## Technologies Used

| Technology | Version | Purpose |
|-------------|----------|----------|
| **DotNet** | 8.x | Framework for building the web application |
| **EF Core** | 8.x | Object-Relational Mapper (ORM) framework  for data access.|
| **React** | 19.x | Frontend library for building user interfaces |
| **PostgreSQL** | 16.x | Database for storing contact information |
| **Nginx** | 1.2.x | Reverse proxy server |
| **Docker** | 28.x+ | Containerization platform |

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/kraftcoding/items-web-api-react-19-postgresql-.net-8  
   ```
2. Build and run the application using Docker Compose:
   ```bash
   docker compose up -d --build
   ```
3. Access the application at 
   
    - **Application**: http://localhost:80

    - **Prometheus**: http://localhost:9090

    - **Grafana**: http://localhost:3000
    - 
    - **cAdvisor**: http://localhost:8080

    - **Node Exporter**: http://localhost:9100

    - **PostgreSQL**: http://localhost:5432

