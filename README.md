# Spring Boot AWS CI/CD Demo

This project demonstrates a CI/CD pipeline using:
- AWS CodePipeline
- AWS CodeBuild
- AWS ECR & ECS Fargate
- Spring Boot + Docker

## Steps

1. Fork this repo and push changes
2. Create ECR repo and update URI in `buildspec.yml`
3. Setup CodeBuild project and ECS task definition
4. Create a pipeline in CodePipeline to connect everything

Push any changes to the `main` branch to auto-deploy.

## Endpoints

| Path | Response |
|------|----------|
| `/`  | `Hello from Spring Boot on AWS ECS!` |