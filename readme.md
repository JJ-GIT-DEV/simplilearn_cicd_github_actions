## Spring boot Application Containerization using Reusable Workflow with Caching

Objective: We are going to create CI/CD workflow for Maven Based source code in which we are going to work with reusable workflows and caching. Using Caching we are going to make sure our maven dependencies get cached, so that during recurring builds maven dependencies don’t get downloaded from fresh and they can be picked up from cache. As part of the CI/CD workflow, we are going to build a custom Docker image and then upload it to the Docker hub registry.

Tools required: GitHub Actions

Prerequisites: None
