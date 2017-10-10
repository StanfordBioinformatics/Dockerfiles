# dockerfiles

###Defunct Notice
This repos is no longer active. Most of the Dockerfiles have been migrated to a GitHub organization specifically created to hold individual Dockerfile repos (see https://github.com/StanfordDockerfiles). Having multiple Dockerfiles in a single repo doens't work nicely with automated build systems, such as in Docker Hub or Quay.io, as an update to one Dockerfile triggers image-building in all other linked repositories. 



A repo for holding Dockerfiles, which are used to build Docker images.

About Dockerfiles: https://docs.docker.com/engine/reference/builder/

Best practices for writing Dockerfiles: https://docs.docker.com/engine/articles/dockerfile_best-practices/

Example of building a bwa image:
  
`docker build -f ./bwa-0.7.4 -t mydockerusername/bwa-0.7.4 .`
