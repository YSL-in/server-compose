# Introduction

This is an era of containerization. Plus, life is short. The project is a demo setup to centralize management for local servers with reversed proxy so that each server can be configured with a canonical URL instead of a pair of a local IP and port. Also, the database system can be shared and backed up in one place.

In order to add a new server to the server-compose, you need to

- create a *docker-compose.yaml* file,
- use *proxy-server/init-db* to initialize a database if needed,
- add a reverse proxy record in *proxy-server/nginx.conf*, and
- reload the nginx server.

The details of the latter three steps are available in the *proxy-server/README.md*.

## Server-kompose

TODO: Add a k8s version.
