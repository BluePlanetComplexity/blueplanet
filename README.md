## How to run the App

```bash

docker-compose build
docker-compose run -d blueplanet /bin/bash

DOCKER_BOX="Docker box Container ID"
winpty docker exec -it $DOCKER_BOX jupyter notebook --port 8080 --ip 172.51.0.2 --allow-root

```

## Description

Our motive is to save the Blueplanet
Please checkout out the link address [https://aswinkv28.wixsite.com/blueplanet](https://aswinkv28.wixsite.com/blueplanet)

Solutions for Food Forests and effective soil testing are modeled in this repository. We take GIS datasets and create Machine Learning models that fit our design for key regions of improvement. 

## Datasets

### Nitrogen fertilizer
![./datasets/nfertilizer_global.png](./datasets/nfertilizer_global.png)

### Phosphorous fertilizer
![./datasets/pfertilizer_global.png](./datasets/pfertilizer_global.png)

## Team

@Jdavid1997
@aswinvk28