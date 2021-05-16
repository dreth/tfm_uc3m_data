# Development of an automatic tool for periodic surveillance of actuarial and demographic indicators

Repository for my final master project at UC3M titled "Development of an automatic tool for periodic surveillance of actuarial and demographic indicators"

## My tutors for the project:

- [María Luz Durbán Reguera](https://researchportal.uc3m.es/display/inv18373)
- [Bernardo D'Auria](https://portal.uc3m.es/portal/page/portal/dpto_estadistica/home/members/bernardo_d_auria)

## How to run:

### Docker image

The repository contains a Dockerfile which can be built and run as follows given [docker](https://www.docker.com/products/docker-desktop) is installed:

```bash
sudo docker build https://github.com/dreth/tfm_uc3m.git#main:docker
```

After building, copy the name of the docker container just built ()

Given your system meets the following requirements:



```R
library(shiny)
runGitHub(repo='tfm_uc3m', username='dreth', ref='main', subdir='dashboard')
```

Optionally, if R is not in your PATH (R does this automatically during install), you could add the following line to your .bashrc or .bash_profile file:

```bash
export PATH="$PATH:**PATH TO R BINARY**"
```

In the bold part, just replace with the location of your R binary.