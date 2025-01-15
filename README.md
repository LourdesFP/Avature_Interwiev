# 🐳 Virtualization<br><small>[Avature](https://careers.avature.net/en_US/main/Dashboard#who-we-are) Home Project</small>

![Python Version](https://img.shields.io/badge/Python->=3.8.10-informational?style=flat-square&logo=python)
![pip3 Version](https://img.shields.io/badge/pip3->=22.2.1-informational?style=flat-square&logo=python)

## The task

You have been asked to implement a deployment of a Python application called
“[storeapi](/storeapi/)” using Docker. Please do the following exercises:

### 1. Write a Dockerfile

The `storeapi` documentation explains how to install this application directly to a server or VM. Your goal is to design this installation using Docker, by writing a Dockerfile.

### 2. How would you deploy it?

Since the application has multiple elements, some orchestration needs to be applied for the solution to work properly. This could be accomplished using Docker Compose, Docker Swarm, k8s, etc.

### 3. Python knowledge

Some basic programming knowledge might be required in order to hack or troubleshoot the application code.

The `storeapi` app implements different methods to interact with a database. You can consume information and inject information. So, additionally, if you have experience coding, you could modify the application code by adding one more method. For example, a “ping” functionality could be added, but it could also be something a little more complex. It’s up to you!

## General suggestions

- Before you start working on the Docker deployment, you might want to make sure the application works outside a container.
- Take your time to organize the project as you like.
- Feel free to use any tools to write or debug your code.

## F.A.Q.

### Do I need to create a UI?

We will only assess the backend, but you can build one if you feel like it.

### Does the app require authentication?

No, it doesn't.

### Can I use an external framework?

Yes, feel free to choose any framework that suits your needs.

### What language should I comment my code in?

English, please.

### Can I add technical documentation or a README?

Anything you feel will expand on your thought process behind the implemented solution will be a great addition.

### Do I have to show my code running during the technical interview?

It's expected that after completing and delivering the home project, it'll be showcased during the technical interview. Please get things ready so you have whatever components you need running on your own computer before the meeting (for example, Docker, minikube/k3d/MicroK8s/others).

### Can I add changes after submitting the project?

Of course! Feel free to add whatever you consider will display your
knowledge and experience.

### Can I change the API port?

If 5000 doesn’t work on your OS, feel free to change it.
