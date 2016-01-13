# dockerfiles

A repo for holding Dockerfiles, which are used to build Docker images.

About Dockerfiles: https://docs.docker.com/engine/reference/builder/

Best practices for writing Dockerfiles: https://docs.docker.com/engine/articles/dockerfile_best-practices/

Example of building a bwa image:
  
`docker build -f ./bwa-0.7.4 -t mydockerusername/bwa-0.7.4 .`
