
---
title: "Documentation"
linkTitle: "Documentation"
weight: 20
menu:
  main:
    weight: 20
---

Welcome to the AWS Copilot CLI developer guide and documentation. Throughout these docs we'll help you use Copilot to 
deploy your container to AWS, grow and release them to production and operate them.

#### What is Copilot?

Copilot is a CLI from Amazon Web Services which helps you build, release and operate your containerized applications on AWS and Amazon ECS.

With Copilot, you focus on the architectures of your application, rather than the infrastructure which supports it. 
Want to deploy a public service? We will provision all the resources for a well architected, secure and load balanced web service on ECS.

Want to add more services to your application? No problem. Beyond helping you spin up new services, 
Copilot also helps you model and operate all of your applicaiton's services together from the comfort of your terminal.

#### Key Features 🔑

Copilot is full of features that help make developing, operating and releasing container apps on AWS delightful, including:
* Multi service applications with built in service discovery
* Model all of your test, staging and production environments in one place
* Continuous delivery pipelines for your services with one command
* Operations built in with loging, alarming and status built in
* Simple yet powerful configuration for your services
* Custom domain name and TLS support
* And much more ...

#### Installing Copilot 💻
Installing the Copilot CLI currently requires you to download our binary from the GitHub releases page manually. 
In the future, we'll distribute the binary through homebrew and other binaries as well.

In the meantime, to install, copy and paste the command into your terminal.

```bash
# MacOS
curl -Lo /usr/local/bin/ecs-preview https://github.com/aws/amazon-ecs-cli-v2/releases/download/v0.0.9/ecs-preview-darwin-v0.0.9 && \
chmod +x /usr/local/bin/ecs-preview && \
ecs-preview --help
```
```bash
# Linux
curl -Lo /usr/local/bin/ecs-preview https://github.com/aws/amazon-ecs-cli-v2/releases/download/v0.0.9/ecs-preview-linux-v0.0.9 && \
chmod +x /usr/local/bin/ecs-preview && \
ecs-preview --help
```