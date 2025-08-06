
# DevOps Internship Log

## 📅 Day 2: 2nd August 2025

**✅ Tasks Completed:**
- Integrated GitHub webhook with Jenkins.
- Built and pushed Docker image to Docker Hub.

**🐞 Issues Faced:**
- Pipeline failed due to missing Docker credentials.

**📘 What I Learned:**
- Jenkins credentials setup
- Docker image tagging and pushing

**📌 Next Plan:**
- Deploy app using Kubernetes and Minikube


###################################################


📅 Day 2: 5th August 2025
✅ Tasks Completed:

Implemented CI/CD pipeline for code quality checks.

Set up SonarQube for static code analysis.

Tested pipeline with GitHub integration and Jenkins.

🐞 Issues Faced:

Faced crashes while running SonarQube on AWS Free Tier EC2 instance due to insufficient resources.

Tried twice but the service failed to stay up.

📘 What I Learned:

SonarQube requires higher memory and CPU; not suitable for t2.micro instance.

Importance of resource planning when deploying services in cloud.

📌 Next Plan:

Use upgraded AWS instance as arranged by the manager.

Reconfigure and finalize SonarQube setup.

Integrate full CI/CD pipeline including build, test, SonarQube scan, and artifact storage in Nexus.
