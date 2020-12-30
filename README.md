# docker-build-push
GitHub Action for Build and Push to Docker registry 

## Inputs

| Name       | Description                                                                                              | Required |
|------------|----------------------------------------------------------------------------------------------------------|----------|
| image      | Docker image name                                                                                        | Yes      |
| tag        | Docker Image tag                                                                                         | No       |
| registry   | Docker registry host                                                                                     | Yes      |
| dockerfile | Location of Dockerfile (defaults to `Dockerfile`)                                                        | No       |
| directory  | Directory to pass to `docker build` command, if not project root                                         | No       |
| buildArgs  | Docker build arguments in format `KEY=VALUE,KEY=VALUE`                                                   | No       |
| username   | Docker registry username                                                                                 | No       |
| password   | Docker registry password or token                                                                        | No       |
