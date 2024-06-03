# A drone ci project
code structure

- woodpecker-installation: for woodpecker installation
- .woodpecker.yaml       : define the pipeline

- drone-installation     : i use this to install drone-ci via docker compose
- .drone.yml             : define the pipeline

- src                    : a simple Golang program, for go build, go test and docker build

**Drone Dashboard**
![drone ci](./drone-ci.png "drone ci snapshot")


**Drone Pipeline**
![drone pipeline](./drone-ci-pipeline.png "drone pipeline snapshot")


**Woodpecker Dashboard**
![woodpecker ci](./woodpecker-ci.png "woodpecker ci dashboard snapshot")


**Woodpecker Pipeline**
![woodpecker pipeline](./woodpecker-ci-pipeline "woodpecker ci pipeline snapshot")
