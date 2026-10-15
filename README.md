
# CI/CD Final Project

## Project Description
A Python application demonstrating Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions, Tekton, Buildah, and OpenShift.

## Technologies
- Python
- GitHub Actions
- flake8
- nose
- Tekton
- Buildah
- OpenShift

## Installation

```bash
pip install -r requirements.txt
```

## Run Linting

```bash
flake8 app.py tests/
```

## Run Unit Tests

```bash
nosetests
```

## GitHub Actions
The workflow is located at `.github/workflows/workflow.yml`. It installs dependencies, runs flake8, and executes unit tests.

## Tekton
Tekton task definitions are located in `.tekton/tasks.yml`.

## OpenShift
The application can be built and deployed through the course-provided OpenShift pipeline after configuring the required cluster resources and credentials.
