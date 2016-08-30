# Development environment
  * Host machine: Win7
    - run startup [batch file](https://github.com/5003/SDO/blob/master/Startup%20Wizard.bat) scripts

# Dockerfiles on Alpine edge
## build dependency packages
See also: [view tags](https://hub.docker.com/r/5003/builder/tags/)
## compare base images
  * Elixir x.x.x: [own](https://github.com/5003/dockerfile-elixir/branches/all) [approximately 50 MB]
    - official [approximately 760 MB]
  * Elasticsearch x.x.x: [own](https://github.com/5003/dockerfile-elasticsearch/branches/all) [approximately 160 MB]
    - official [approximately 350 MB]
  * Kibana x.x.x: [own](https://github.com/5003/dockerfile-kibana/branches/all) [approximately 180 MB]
    - official [approximately 300 MB]