# django-pipeline 🚀

A robust, production-ready Django boilerplate with a complete CI/CD pipeline, Dockerized environments, PostgreSQL integration, and AWS deployment support.

---

## 🔧 Features

- 📦 **Docker** support with separate environments for `dev`, `staging`, and `prod`
- 🧪 **Pytest** for testing across all environments
- 🐘 **PostgreSQL** integration out of the box
- 🔁 **GitHub Actions CI/CD** for automated testing and build
- ☁️ **AWS Deployment** setup with Docker and ECR

---

## 📁 Project Structure

├── app/ # Django project │ └── myproject/ │ └── settings/ # base.py, dev.py, staging.py, prod.py ├── docker-compose.yml # Development environment ├── docker-compose.staging.yml ├── docker-compose.prod.yml ├── .env.dev # Environment variables for dev ├── .env.staging ├── .env.prod ├── requirements.txt ├── pytest.ini ├── tests/ # Example test ├── .github/workflows/ci.yml # GitHub Actions CI └── deploy/ # AWS deploy script & docs


---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sfantaye/django-pipeline.git
cd django-pipeline

### 2. Run in Development
docker-compose up --build

### 3. Run Tests
docker-compose exec web pytest


BY SINTAYEHU FANTAYE
UNDER MIT LICENSE

