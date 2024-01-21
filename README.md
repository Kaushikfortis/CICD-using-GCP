# CICD-using-GCP

# Building DevOps Pipeline using GCP

This project demonstrates the implementation of a DevOps pipeline using Google Cloud Platform (GCP) to deploy Python applications. The pipeline leverages Git for version control, Docker for containerization, Cloud Build for continuous integration, and Artifact Registry for storing Docker images.

## Overview

The goal of this project is to automate the deployment process and ensure a seamless workflow from development to production. The pipeline is designed to:

1. **Version Control with Git:**
   - Utilize Git for version control to manage source code changes efficiently.

2. **Containerization with Docker:**
   - Package the Python applications into Docker containers to ensure consistency and portability across environments.

3. **Continuous Integration with Cloud Build:**
   - Set up Cloud Build to automatically build and test the Docker images whenever changes are pushed to the Git repository.

4. **Artifact Registry for Docker Image Storage:**
   - Store the Docker images in Google Cloud Artifact Registry, providing a centralized repository for managing and versioning container images.

## Getting Started

Follow these steps to set up and deploy your Python applications using this DevOps pipeline:

### Prerequisites

1. **Google Cloud Platform Account:**
   - Ensure you have a GCP account with the necessary permissions to create and manage resources.

2. **Cloud SDK:**
   - Install the [Google Cloud SDK](https://cloud.google.com/sdk) for command-line access to GCP services.

3. **Git:**
   - Install Git for version control. You can download it [here](https://git-scm.com/downloads).

### Project Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/your-python-app.git
