# Jenkins lab

# log

## Jenkins Init

- checkout the repo
- create a folder named `jenkins_home`
- `docker-compose build`
- `docker-compose -d`
- add a line to /etc/hosts

```bash
127.0.0.1 jenkins.local
```

- open chrome and visit [[http://jenkins.local:8080]]

## artifactory Init

- open chrome and visit [[http://artifactory.local:8081]]

## docker in docker

to run tf pipeline in jenkins, you need to enable docker inside docker in jenkins docker build. check [[https://docs.google.com/document/d/1z5XWSybgZxpxrGJVwI6fcFZpQU9Fw8HWX55Bnxk5OCI/edit?usp=sharing]] for details.
