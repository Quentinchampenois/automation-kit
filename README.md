# automation-kit
WIP - Deploy easily containerized applications using Docker, Ansible and Traefik

This repository is still in progress, it contains a very simple Traefik configuration to start using it quickly. And it contains too an Ansible playbook that set up Traefik and Docker on a remote server. It allows to push new applications and deploy it through Traefik immediately. 

## Requirements

* Remote server with ssh access
* Domain name
* Ansible 

## Getting started

Clone this repository.

### Setup Traefik

Rename `traefik.toml.example` as `traefik.toml`, it is the Traefik configuration file.  
Then replace all examples in `traefik.toml` configuration with your own configuration.

For any doubt about configuration variable, you can refer to the appropriate documentation in respective folder.

Now, Traefik shall be able to deliver your applications using Let's Encrypt.

### Setup Ansible 





Clone this repository and remove all `.example` in filenames to get there original names. All `*.example` files are copy of local configuration that contains potentially sensitive data.

 Update all 


## Sources

* https://docs.traefik.io/
* https://docs.ansible.com/
* https://docs.docker.com/