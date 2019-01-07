## Traefik Proxy ##

This repository includes a docker-compose file and a set of ansible steps to set up a [Traefik](https://docs.traefik.io/) proxy for docker local development.

### Setup ###

See [setup/setup.yml](setup/setup.yml) for an ansible playbook to set this up locally (or the steps that need to be done in a bash script or by hand) 

`cd setup; ansible-playbook -K setup.yml`


### Sources ###

The following blog post was instrumental in getting this setup:

https://medium.com/@williamhayes/local-dev-on-docker-fun-with-dns-85ca7d701f0a

With this additional post for information about a docker-compose file for Traefik

https://jtreminio.com/blog/traefik-on-docker-for-web-developers/




