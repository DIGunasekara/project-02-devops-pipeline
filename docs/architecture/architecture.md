Project Architecture
1. Project Overview

This project demonstrates an industry-style software delivery workflow. A web application containing a frontend, backend API, and chatbot will be developed, containerized, tested, and deployed using DevOps practices.

2. Initial Architecture
Frontend: Web user interface.
Backend: REST API and application business logic.
Chatbot: Conversational interface connected to the backend.
Database: Persistent application data.
Docker: Containerize the application services.
Docker Compose: Run the application services together.
Git and GitHub: Version control and collaboration.
CI/CD: Automated testing, image building, and deployment.
Monitoring: Application health, logs, and resource usage.
3. Infrastructure

Development and staging will initially use my Rocky Linux virtual machine. Production-like deployment will be simulated in the same lab until separate infrastructure is available.

The database may initially run as a separate container on the same VM. Later, it can be moved to a separate server to practise network isolation and remote database connectivity.

4. Delivery Flow

Developer → Git branch → Pull request → Code review → Automated tests → Container image build → Image registry → Staging deployment → Validation → Production-like release → Monitoring and backup verification.

5. Security Principles
Never commit passwords, API keys, or database credentials.
Store secrets outside the Git repository.
Use environment variables and protected CI/CD secrets.
Restrict server access and exposed network ports.
Validate application health before releasing changes.
6. Initial Constraints

This is a learning environment, not a real production service. Production deployment, high availability, and disaster recovery will be simulated and documented according to the resources available.
