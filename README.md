# ci-docker-image
The image that we can use for our CI/CD pipeline

## node image
```bash
cd node
docker build . -t stateofct/ctoec-node
docker push stateofct/ctoec-node
```


## php image
```bash
cd php
docker build . -t stateofct/ctoec-php
docker push stateofct/ctoec-php
```