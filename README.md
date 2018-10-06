My repository of Dockerfiles.

To publish an image to Dockerhub:
- `docker build -t goldenshun/$DOCKER_REPO:$IMG_TAG -f $DOCKERFILE .`
- `docker push goldenshun/$DOCKER_REPO:$IMG_TAG`

Example:
- `docker build -t goldenshun/node-chrome:8 -f Dockerfile.node-chrome .`
- `docker push goldenshun/node-chrome:8`
