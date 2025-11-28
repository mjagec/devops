# DevOps Practices Showcase – Software Engineering Methods Course

![CI Build](https://github.com/mjagec/devops/actions/workflows/ci.yml/badge.svg)
![Unit Tests](https://github.com/mjagec/devops/actions/workflows/tests.yml/badge.svg)
![Docker Build](https://github.com/mjagec/devops/actions/workflows/docker.yml/badge.svg)
![Code Coverage](https://codecov.io/gh/mjagec/devops/branch/main/graph/badge.svg?token=XXXXXX)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A university group project demonstrating core **DevOps principles** through a Java-based full-stack web application. Developed as part of the Software Engineering Methods course, this repository implements CI/CD pipelines, containerization, automated testing, and build automation to model production-ready workflows.

## 🚀 Key DevOps Practices Implemented

| Area                  | Technologies & Tools                  | Purpose                                      |
|-----------------------|---------------------------------------|----------------------------------------------|
| **Version Control**  | Git + GitHub                          | Collaborative development & branch protection|
| **CI/CD**            | GitHub Actions (build, test, deploy)  | Automated pipelines for code quality gates   |
| **Containerization** | Docker + Docker Compose               | Portable environments across dev stages      |
| **Automated Testing**| JUnit (unit tests), integration tests | Comprehensive coverage with Codecov reporting|
| **Build Automation** | Maven, Shell scripting                | Reproducible builds and dependency management|
| **Static Analysis**  | Built-in GitHub checks, pre-commit    | Code quality and security scanning           |
| **Deployment**       | Local Docker, extensible to cloud     | Simulated production deploys                 |

## 🛠 Tech Stack

**Backend** – Java (Maven)  
**Containerization** – Docker + Docker Compose  
**Testing** – JUnit + Codecov  
**CI/CD** – GitHub Actions  
**Build Tools** – Maven, Shell  

## 📊 Current Coverage
![coverage](https://codecov.io/gh/mjagec/devops/branch/main/graph/badge.svg?token=XXXXXX)

We target >80% test coverage on the Java backend, tracked via continuous Codecov integration.

## 🎯 Learning Outcomes & Professional Skills Demonstrated

- Configuring GitHub Actions for multi-stage CI/CD pipelines
- Building and orchestrating Docker containers for Java applications
- Implementing automated unit and integration tests with JUnit
- Managing dependencies and builds with Maven
- Enforcing code standards through workflows and hooks
- Simulating deployment processes for scalability
- Learning about agile development practices, project management, sprints, etc.

This project mirrors entry-level DevOps workflows at tech firms and highlights practical skills for **DevOps Engineer, Backend Developer, or Build/Release Engineer internships**.

## 🚀 Quick Start (Local Development)

```bash
# Clone and enter repo
git clone https://github.com/mjagec/devops.git
cd devops

# Build and start with Docker Compose
docker compose up --build
```

## 👥 Contributors & Attribution

This repository is a **fork** of the original group project maintained at:  
[https://github.com/antnyyy/devops](https://github.com/antnyyy/devops) ← replace with the real upstream URL

Additional improvements and polishing in this fork:
- Enhanced README and badge layout for recruitment/portfolio purposes

All core application code, Docker setup, and DevOps practices were developed collaboratively in the original repository during the Software Engineering Methods course (2024/2025).
