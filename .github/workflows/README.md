
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

The GitHub Actions workflow installs dependencies, runs flake8 linting, and executes unit tests using nose.

### 2. Continuous Delivery with Tekton

The Tekton pipeline performs cleanup, clones the source repository, runs linting and unit tests, builds the application image, and deploys the application to OpenShift.

### 3. Application Deployment

The application is deployed as `cicd-app` and listens on port 8000.

## Verification

The project is verified by checking the GitHub Actions workflow, successful Tekton PipelineRun, OpenShift deployment, and application logs.

## Repository

Project name: ci-cd-final-project
