# just a role for rustic docker (standalone) deployments

Note: **There are many good alternatives witch truly worth, go for them.**

This role configure services in var *docker_services* on a folder structure.

If systemd_create is setted on a service (by default it is) the role will create a systemd service for handle start, reload, restart, stop.

If ingress is true (by default it is) configured for a service, it aditionaly configure exports ports through nginx-proxy.

## Requirements

* docker
* docker-compose
* systemd (optional)