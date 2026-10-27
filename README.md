
# ci-cd-final-project

## Project Overview

This project implements a Continuous Integration and Continuous Delivery (CI/CD) pipeline using GitHub Actions, Tekton, and Red Hat OpenShift.

## Technologies Used

- Python
- Flask
- Git and GitHub
- GitHub Actions
- flake8
- nose
- Tekton Pipelines
- Buildah
- Red Hat OpenShift

## Project Tasks

### 1. Continuous Integration with GitHub Actions
Install dependencies, run flake8 linting, and execute unit tests using nose.

### 2. Continuous Delivery with Tekton
Run cleanup, clone the source repository, perform linting and unit tests, build the application image, and deploy the application.

### 3. Application Deployment
Deploy the application as `cicd-app` on port 8000.

## Verification
Verify the GitHub Actions workflow, Tekton PipelineRun, OpenShift deployment, and application logs.

**Project name:** ci-cd-final-project
