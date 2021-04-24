# docker-multi-container

This shows: 
- 4 separate docker images
  - docker-multi-client
  - docker-multi-nginx
  - docker-multi-server
  - docker-multi-worker 
- all images pushed to docker hub
- docker-multi-client: simple React Fib calculator UI
- docker-multi-server: nodejs server with postgres and redis setup
- docker-multi-worker: worker image for redis
- docker-multi-nginx: client and server routing
- AWS elastic beanstalk to deploy and run this project
- travis for:
  - CI/CD with react test
  - automatic push of images to docker hub
  - after iamge push, auto deploy to AWS elasticbeanstalk
