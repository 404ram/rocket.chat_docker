# rocket.chat_docker

## Intro

Basic implementation of the rocket.chat server via docker containers. There are for sure better ways for implementing this in an containeraised way, but it works for me KISS !!!

links to technologies used:
- www.docker.com
- www.rocket.chat
- www.mongodb.com

## Container Images

- mongodb:latest
- rocketchat:latest

### Implementation

Created a docker compose file, with specifics for network containers intercommunication and persistant data volume for mongodb

### Configuration

Simple change the environment  ```ROOT_URL``` variable value in the docker-compose.yml file to the one you would be using. 
