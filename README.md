# Devops-Course-FALL-2024
This repository contains a detailed walkthrough of the concepts and technologies I learned during the DevOps Course FALL-2024, taught by @Saim Safdar.

## What I Have Learned
Throughout this course, I gained hands-on experience with various DevOps tools and practices, including:

* Version Control: GitHub
* Containerization: Docker, Podman
* Orchestration: Kubernetes, Istio
* Cloud Services: ECS/EKS
* Infrastructure as Code (IaC):
* Terraform
* Pulumi
* Policy as Code: Kyverno
* Serverless Frameworks: Knative
* Networking: Ingress

## Blog 1

**Handling Environment Variables in Docker Compose for Secure and Flexible Configurations**

Secure handling of sensitive data in Docker Compose is very important when working with a DevOps environment. Using this data securely means that credentials, keys, or tokens that are sensitive such as database credentials, API, and Tokens do not go into the code repository or be build.

This article will explain the proper usage of environment variables and secrets in docker-compose, and show how to deal with different environments such as development, staging, and production.

Handling environment variables securely in Docker Compose is essential for both development flexibility and production security. By externalizing sensitive information into .env files, secrets, and CI/CD pipelines, you can manage configurations more securely and efficiently. Using tools like dotenv-linter error checking and container scanners for security ensures that your Docker setup is both robust and secure.

## Blog 2

**HELM: The Tool Every DevOps Professional Needs to Simplify Kubernetes Management**

Have you ever found yourself struggling to manage complex applications in Kubernetes? If the answer is yes, then HELM might be your missing tool.

Managing a large number of Kubernetes clusters in the fast-moving world of DevOps with hundreds of microservices, configurations, and dependencies can grow to be overwhelming. HELM, better known as “the package manager for Kubernetes,” is here to make our lives easier for developers and students.

Open source HELM is an application running on top of K8s to define, install, and upgrade even the most complex applications. It's based on a concept of charts: preconfigured packages of Kubernetes resources. Because these charts are reusable, you can deploy applications with the same configurations in different environments.

HELMS simplifies the hours we spend managing, deploying, and upgrading Kubernetes applications so we can spend more time building great applications. Adopting HELM in your DevOps workflow because of its superpowers like Version control, Templating, and easy rollbacks will add the final level to your Kubernetes management. So, why not give HELM a try? Once you start using it, you'll wonder how you managed Kubernetes without it!

## Blog 3

This blog explains how to use GitHub Actions to automate the process of testing and deploying a Flask application. GitHub Actions is a tool that helps developers set up automatic workflows for tasks like checking code for errors, running tests, and deploying the app to a server. 

1. **Flask App Setup**: You first need a working Flask application with necessary files, such as `app.py` and `requirements.txt`, which lists the app's dependencies.

2. **GitHub Actions Workflow**: You create a YAML file (`main.yml`) in your repository to define the steps for automation. The main steps include:
   - **Triggering** the workflow when changes are made to the code.
   - **Setting up Python** for your application.
   - **Installing dependencies** (like Flask).
   - **Running tests** to make sure everything works correctly.
   - **Deploying** the app to a platform like AWS or Heroku after the tests pass.

The blog emphasizes how GitHub Actions makes the deployment process more efficient, helping developers focus on coding instead of manual tasks.

### Links
- [Medium](https://medium.com/@sh.hamzarauf/automating-deployments-with-github-actions-523828f40c4e)
- [Github](https://github.com/Sheikh-Hamza-Rauf/GitHub-Actions)

## Contacts

## **🌐 Platforms**  

### **1. Medium**  
- **Explore my articles and insights:**  
  [Visit Medium Profile](https://medium.com/@sh.hamzarauf)

---

### **2. GitHub**  
- **Discover my projects, contributions, and open-source work:**  
  [Visit GitHub Profile](https://github.com/Sheikh-Hamza-Rauf)

---

### **3. Linkedin**  
- **Get a glimpse of my accomplishment:**  
  [Visit Linkedin Profile](https://www.linkedin.com/in/hamza-rauf-mernprogrammer)  

---

