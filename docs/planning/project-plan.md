Project Delivery Plan
Milestones
Milestone	Completion target	Deliverables
M1	Server prepared and secured	Rocky Linux updates, Git, Docker, firewall, SSH security and server documentation
M2	Repository and pull-request workflow ready	Git branches, GitHub issues, milestone tracking, pull-request template and branch protection
M3	Application works in development	Frontend, backend, chatbot and database working together locally
M4	Docker Compose deployment works	Containerized services, persistent storage, environment configuration and health checks
M5	CI pipeline and image registry work	Automated tests, image builds, vulnerability checks and registry publishing
M6	Automated staging and production release work	Staging deployment, validation, approval-controlled production-like release and rollback procedure
M7	Monitoring, backups, and recovery work	Logs, health monitoring, scheduled backups, restoration testing and operational documentation
Execution Order
Complete M1 before deploying application services.
Complete M2 before collaborating on application changes.
Complete M3 before containerizing the complete application.
Complete M4 before building the image publishing pipeline.
Complete M5 before automating deployment.
Complete M6 before final operational validation.
Complete M7 and perform an end-to-end review.
Definition of Done

A milestone is complete when:

Its GitHub issues meet their acceptance criteria.
Required changes are reviewed and merged.
Documentation is updated.
Tests or verification evidence are available.
No unresolved critical issue prevents the next phase.
Delivery Strategy

Work on one milestone at a time. Break each milestone into GitHub issues, assign a clear completion condition to each issue, and close issues only after verifying the result.
