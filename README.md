# CI-CD

The project containers docker files for different micro-services communicating with each other. Each of these containers can be built using docker compose script. Github workflow is also created for micro-services to run testcases.

Commands:

- docker build -t tag -f filename .
- docker run tag
- docker-compose up --build
