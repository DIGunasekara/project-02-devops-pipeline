Project Requirements
Functional Requirements
Users must be able to access the frontend through a web browser.
The frontend must communicate with the backend API.
The backend must process requests and communicate with the database.
The chatbot must communicate with the backend and return responses.
Application data must persist across container restarts.
The application must expose a health endpoint for deployment checks.
DevOps Requirements
Source code must be version-controlled using Git.
Changes must be proposed through pull requests.
Automated tests must run through a CI pipeline.
Frontend, backend, and chatbot services must be containerized.
Docker Compose must start the application services together.
Container images must be published to a registry.
Staging deployment must be automated.
Production-like releases must require validation and approval.
Logs, health checks, backups, and recovery procedures must be documented.
Security Requirements
Secrets must not be committed to Git.
The Linux server must use appropriate access controls and firewall rules.
Only required ports must be exposed.
Application dependencies and container images must be checked for vulnerabilities.
Database access must be restricted to authorized application services.
Non-Functional Requirements
Repeatable deployments.
Reliable application startup and health checks.
Maintainable configuration.
Clear operational documentation.
Recoverable application data.
Minimal cost using existing local lab resources where possible.
Scope

The project will begin with a single Rocky Linux VM. Separate database infrastructure and Kubernetes-based deployment will be considered in later phases after the initial workflow is working.
