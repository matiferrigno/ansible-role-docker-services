# just a role for rustic docker (standalone) deployments

Note: **There are many good alternatives witch truly worth, go for them.**

This role configure services in var *docker_services* on a folder structure.

If ingress is true (by default it is) aditionaly configure exports ports through traefik.

## Requirements

* docker
* docker-compose
