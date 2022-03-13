# MyProApp
---
My Todo api, This api uses python FastAPI and MongoDB.

[![build](https://github.com/idokrn/WorkTest/actions/workflows/build.yaml/badge.svg)](https://github.com/idokrn/WorkTest/actions)


# Getting started
___
Clone this repository with
``` bash
git clone https://github.com/idokrn/WorkTest.git && cd WorkTest
```

Login to my Jfrog artifact registry

``` bash
docker login idokrn.jfrog.io -u anonymous -p anonymous
```

Bring the API up
``` bash
docker-compose up -d
```

Now you can verify the deployment by accessing the api docs [Here](http://localhost/docs)


