
# Kubernetes GitHub Playground

This project demonstrates how to deploy a static website hosted on GitHub using Kubernetes. It serves an `index.html` file from a GitHub repository and configures it using an `app.yaml` file.

## Overview

This project provides a simple way to use Kubernetes to deploy a static website directly from a GitHub repository. By connecting your Kubernetes environment to GitHub, the project automatically serves the `index.html` file (or any other static files) defined in your repository.

## Features:
- **Serve static content**: Serve an `index.html` (or any other static files) directly from GitHub using Kubernetes.
- **App.yaml integration**: Easily configure and deploy using the `app.yaml` file.
- **Kubernetes Deployment**: A simple, scalable deployment of a static website using Kubernetes' native tools.

## How it works:
1. The project connects to your GitHub repository.
2. It fetches and serves the `index.html` file (or any static content) hosted in the repository.
3. It uses an `app.yaml` to configure the Kubernetes deployment and manage the resource settings.

## Prerequisites:
- Kubernetes cluster setup.
- Access to a GitHub repository with the `index.html` (or static files) you want to serve.
- Basic understanding of Kubernetes and configuration with `app.yaml`.

## Setup:
1. Clone the repository to your local machine.
2. Update the `app.yaml` to point to your GitHub repository where the `index.html` file is hosted.
3. Apply the Kubernetes configuration using `kubectl apply -f app.yaml`.
4. Access the website via the external IP or domain configured in the Kubernetes cluster.

## Example:

1. **`app.yaml`**  
   This file connects your Kubernetes deployment with your GitHub repository and specifies the settings for serving the static website.

2. **Access the Site**  
   After deployment, the website will be accessible via the assigned IP or domain.

## Conclusion:
This project provides a simple, efficient way to serve static websites using Kubernetes and GitHub. It's a great starting point for exploring Kubernetes in web hosting and cloud environments.
