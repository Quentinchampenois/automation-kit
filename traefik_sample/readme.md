# Traefik sample

In this folder you can find a very basic traefik configuration.

## Files

* `.env` - Environment variables used in docker-compose file for example
* `traefik.toml` - Traefik configuration used in Traefik container
* `docker-compose.yml` - Docker-compose file running traefik and basic applications

## Getting started

### Use Makefile

A stupid makefile is available to rename automatically all `*.example` files in this directory.  
You can use it using the `make` command 
~~~
    make
~~~

After you replaced all variable according to your own configuration, you can run a configuration checking with : 

~~~
    make check
~~~

### Proceed manually 
Please remove all `.example` in filenames and updates variables with your own configuration.

Test your docker-compose configuration if you want using config command

~~~
    docker-compose config
~~~

## Note

Please note that it is a very simple traefik configuration, refer to documentation (https://docs.traefik.io) for a full and secured configuration.

## Sources

* https://docs.traefik.io/
* https://docs.docker.com/
* https://www.digitalocean.com/community/tutorials/how-to-use-traefik-as-a-reverse-proxy-for-docker-containers-on-ubuntu-18-04
