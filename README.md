# simple-portainer-deployment

Portainer has a feature for browsing volumes. (see: https://documentation.portainer.io/v2.0/volumes/browse/)

But, this feature can only be used on so called "Docker Swarm nodes".

To turn a host in to such an "Docker Swarm node" simply requires to run a portainer agent on it.

This projects helps in setting up and running a separate agent alongside portainer on a single host.

simply clone and run `docker-compose up -d`


