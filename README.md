Setup
I deployed my notes application to Azure VM using Docker containers.

What I did

Opened ports 5000 and 8080 in Azure VM firewall settings
Connected to VM via SSH
Pulled my Docker images from Docker Hub (polina0602/devops-course-backend and polina0602/devops-course-frontend)
Created a Docker network so containers can communicate
Started backend container on port 5000
Started frontend container on port 8080

Result

Frontend runs on http://172.209.208.63:8080
Backend API available at http://172.209.208.63:5000/api/notes
