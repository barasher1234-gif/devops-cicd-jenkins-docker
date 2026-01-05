\# CI/CD Pipeline with Jenkins and Docker (Local)



A local DevOps project demonstrating an automated CI/CD pipeline using Jenkins and Docker.

The pipeline builds a Docker image and deploys a containerized Python (Flask) application automatically.



\## Tech Stack

\- Jenkins (running in Docker)

\- Docker (Docker socket mounted)

\- Python (Flask)

\- Git / GitHub



\## Pipeline Stages

1\. List workspace files

2\. Build Docker image

3\. Remove existing container (if exists)

4\. Run a new container



\## How to Run

1\. Run Jenkins in Docker (local setup)

2\. Create a Jenkins Pipeline job

3\. Paste the Pipeline script (or use Jenkinsfile)

4\. Click \*\*Build Now\*\*

5\. Open: http://localhost:5000



\## Notes

\- Jenkins was run as root in this local Docker Desktop environment to access Docker socket.

\- In production, a more secure setup would be used (dedicated permissions / remote daemon).



