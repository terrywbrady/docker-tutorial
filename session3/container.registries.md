---
title: "Container Registries"
nextpage: running.docker.on.a.server
---

{% include nav.html %}

## Registry Examples

Note: Registries contain repositories. 

- [DockerHub](https://hub.docker.com/)
  - Public and private repositories are supported. Private respositories are a paid feature.
  - [UC3 DockerHub Repository](https://hub.docker.com/u/cdluc3)
  - [DSpace DockerHub Repository](https://hub.docker.com/u/dspace)
- [Amazon ECR](https://aws.amazon.com/ecr/)
  - [Public Registry](https://gallery.ecr.aws/)
  - An ECR **Private Registry** is used to make your code available
    - To Lambda (for Docker Deployment)
    - To ECR
    - To other AWS services?
- [GitHub Container Registry](https://docs.github.com/en/free-pro-team@latest/packages/guides/about-github-container-registry)

## Docker Commands for working with Registries
- docker login
  - log into a registry (dockerhub is the default)
- docker pull
  - pull and image from a repository
  - login is required to pull from a private repository
- docker push
  - push and image to a repository (login is required)




{% include next.html %}
