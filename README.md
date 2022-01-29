This is a simple wordpress build by docker (image can found in docker hub). Please keep in mind to use safe password or encrypted password when deploying this to production.

How to run this app in ubuntu-server:

- install docker (https://docs.docker.com/engine/install/ubuntu/)
- install docker-compose (https://docs.docker.com/compose/install/)
- docker-compose up -d

When we have to scale this app due to user/viewer this app growing we can use docker swarm or kubernetes
We have a lot of choice, we can use amaozon EKS or google GKE to deploy this app, but for me i prefer to use amazon EKS because i usually use amazon EKS for some project in my currently job
