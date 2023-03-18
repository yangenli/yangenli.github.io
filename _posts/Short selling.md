---
title:  "Short Selling amid Stock Market Turmoil: Evidence from 2020 Coronavirus Market Crash"
mathjax: true
author: Yangen Li and Deng, Xiaohu
---

• Present at Southwestern Finance Association (SWFA) Annual Conference 2021
Abstract: Many countries around the world reacted to the COVID-19 crisis by imposing bans on short selling. Using firm level short selling data and order level stock trading data, we identify the effect of short selling on stock price behaviors around the Coronavirus crash. We find that in general short selling is positively associated with both volatility and price discovery, before and during the market crash. Moreover, short selling does not further increase volatility or slow down price discovery during the market crash, relative to pre-crash period. Interestingly, we find that short selling has a negative impact on volatility when stock market crashes most significantly.








## Prereqs

You'll need to install [docker](https://docs.docker.com/get-docker/) on your machine. If you want to borrow our docker-compose.yml file, you can copy from this [repository](https://github.com/pennchildlanglab/docker-compose-demo), or clone it using 

```
git clone https://github.com/pennchildlanglab/docker-compose-demo.git
```


## Docker compose

You'll need a docker-compose.yml file that specifies the [image](https://hub.docker.com/r/jupyter/datascience-notebook/) you want to use, the password, the volume to map to, and the port you want to open on

```yml
version: "3.7"
services: 
  datascience-demo:
    image: jupyter/datascience-notebook:r-4.0.3
    environment: 
      - JUPYTER_TOKEN=hi
    volumes:
      - ./:/home/jovyan/work
    ports: 
      - 8888:8888
    container_name: datascience-demo

```

To bring up the container, navigate to the folder that contains the docker-compose.yml file and use

```
docker-compose up -d --build
```

To bring it down, use

```
docker-compose down
```
