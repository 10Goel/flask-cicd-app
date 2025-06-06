# Flask CI/CD App

A simple Flask web application demonstrating a basic **CI/CD pipeline** using **GitHub Actions**.

---

## Project Overview

This project includes a minimal Flask web app and an automated deployment pipeline configured with GitHub Actions. The pipeline runs on every push to the `main` branch and simulates building and testing the app.

---

## Features

- Simple Flask app returning a friendly message at the root URL (`/`)
- Python dependencies managed with `requirements.txt`
- GitHub Actions workflow (`.github/workflows/deploy.yml`) to automate:
  - Code checkout
  - Python environment setup
  - Dependency installation
  - Simulated build/test step

---

## Getting Started

### Prerequisites

- Python 3.9+
- Git
- [Optional] A GitHub account to use GitHub Actions and push code

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/flask-cicd-app.git
   cd flask-cicd-app
