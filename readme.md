## Ocelot: Sample Gateway Implementation

This is a sample implementation of a gateway using Ocelot, .net Core 2.0 and docker.

To find out more about Ocelot, you can check their official [documentation](http://ocelot.readthedocs.io) and their [repository](https://github.com/TomPallister/Ocelot)

### Pre-requisites

* Visual Studio 2017 15.3+
* Docker


### docker run

* validate config  
  docker-compose -f docker-compose.ci.build.yml  -f docker-compose.yml -f docker-compose.override.yml  config
* build
  docker-compose -f docker-compose.ci.build.yml  run ci-build     
* run
  docker-compose up 
* list
  docker ps
