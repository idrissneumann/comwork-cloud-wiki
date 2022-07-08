# Portainer as a service

Get your infrastructure to the next level using [portainer](https://www.portainer.io) on our cloud platform !

## Table of content

[[_TOC_]]

## Usecases

Here is a non exhaustive list of portainer usecases we're enjoying the most:

1. You can manage you other environments/instances with a portainer agent and list them like that:

![portainer_manage_envs](./img/portainer_manage_envs.png)

2. You can manage the containers that are deployed on the edge agents or directly on your portainer instance:

![portainer_containers](./img/portainer_containers.png)

3. You can manage a container: see it's stdout/stderr output or connect directly with a shell session:

![portainer_shell_session](./img/portainer_shell_session.png)

Multiple other actions:
* Clean the docker/OCI images
* Connect to a private docker/OCI registry
* Kubernetes integration
* Deploy directly your containers from a catalog or a docker-compose file you just have to upload like a real Heroku/Netlify like PaaS

## First connection

Beware: you have to set an admin password to the first connection and there is a portainer timeout, so do not wait to connect to your instance after creating it.

## Sizing and pricing

Check it out [here](./sizing_pricing.md).

You can also choose to do it by yourself, it's completely free, enjoy [our repositories](https://gitlab.comwork.io/oss/ansible-iac/portainer) with the docker images and ansible roles in order to install it by yourself.