# Deploy Node.js on AWS Using GitHub, ECR, CodeBuild, and ECS

![nodejs](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*J45ZT_aD8kaPIwV4tjcKlg.png)

**GitHub (Source)** : The source code is stored and managed in GitHub.
**CodeBuild (Build & Test)** : CodeBuild fetches the source code, builds the Docker image, runs tests, and prepares the application for deployment.
**ECR (Docker Image)** : The Docker image is stored in the Amazon Elastic Container Registry (ECR).
**ECS (Cluster)** : The ECS cluster hosts the application’s tasks.
**ECS (Services)** : Services manage the tasks and ensure the desired number of instances are running.
**ECS (Tasks & Containers)** : Tasks run the Docker containers, which are instances of the application.

https://medium.com/@Vaibhavihole31/deploy-node-js-on-aws-using-github-ecr-codebuild-and-ecs-fd4304b93510
