# 🌍 World Population Reporting System

## 📌 Project Overview
This is a **desktop-based population reporting system** built using **C# (WinForms)** with a **MySQL** backend. It provides dynamic and structured reports on countries, cities, continents, regions, and languages. The system is designed for educational and analytical purposes, reflecting real-world population data.

---

## 💻 Technologies Used
- **C# (.NET WinForms)** – For building a user-friendly desktop interface  
- **MySQL** – As the relational database storing population data  
- **Docker** – For setting up and managing the database environment  
- **Git & GitHub** – For version control and collaboration  
- **Zube.io + GitHub Projects** – For agile Scrum task management  
- **Visual Studio** – Main IDE for development

---

## 🚀 Getting Started

### 🔧 Prerequisites
To run this project locally, ensure you have the following:

- [Visual Studio](https://visualstudio.microsoft.com/) (with .NET Desktop Development)
- MySQL Server (local or Docker-based)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/) (optional, for containerized DB)
- .NET SDK (latest version)

---

## 🐳 Run MySQL Using Docker (Optional)

```bash
docker run --name mysql-db -e MYSQL_ROOT_PASSWORD=yourPassword -p 3306:3306 -d mysql:latest
