
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
gh
Importance of resource planning when deploying services in cloud.

📌 Next Plan:

Use upgraded AWS instance as arranged by the manager.

Reconfigure and finalize SonarQube setup.gg

Integrate full CI/CD pipeline including build, test, SonarQube scan, and artifact storage in Nexus.



Day 2: 8th August 2025
✅ Tasks Completed:

Developed a full-stack application including both web and mobile frontends, backend, and MongoDB database.

Mobile app connected to local MongoDB instance for development and testing.

Initially used local MongoDB for the web app as well, but realized it wouldn't work for production.

Migrated the web application’s database connection to MongoDB Atlas (cloud database service) for accessible and synchronized data across web and mobile apps.

🐞 Issues Faced:

Local MongoDB cannot be accessed from external web clients, causing data sync problems for the web app.

Had to set up MongoDB Atlas cluster and connection URI for web app.

📘 What I Learned:

Difference between local MongoDB and MongoDB Atlas in terms of accessibility and deployment.

How to configure and use MongoDB Atlas for cloud-based database access.

Importance of central database for synchronized data between mobile and web apps.

📌 Next Plan:

Secure MongoDB Atlas connection using environment variables and access control.

Integrate authentication and authorization in both web and mobile apps.

Test real-time data synchronization between mobile and web apps.

