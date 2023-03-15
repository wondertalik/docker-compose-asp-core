# Dockerfile build
```
pwd
/study/WebApplication2

ls
WebApplication2     WebApplication2.sln

# commands
docker build  -f WebApplication2/Dockerfile -t test/webapp:latest .
docker run --rm -it --name testwebapp -p 80:80 test/webapp:latest   
```

# Docker compose
```
pwd
/study/WebApplication2

ls
WebApplication2     WebApplication2.sln

# commands
docker compose -f WebApplication2/docker-compose.yaml --project-directory . up --build
```