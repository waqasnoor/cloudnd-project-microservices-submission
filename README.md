# Udacity Cloud Nano Degree : Project Udagram Microservices

This Project is just submission repo of my microservices,reverse proxy and frontend.
This project includes Screenshots, Links to Relevent Repos as well as Production URL

## Tasks

- Refactor the API :heavy_check_mark:
- Containerize the Code :heavy_check_mark:
- Build CICD Pipeline :heavy_check_mark:
- Deploy to Kubernetes :heavy_check_mark:
- Logging :heavy_check_mark:

## Repositories

This Project has been divided in 4 different Repositories

- user-api [cloundnd-project-microservice-user](https://github.com/waqasnoor/cloundnd-project-microservice-user)
- feed-api [cloundnd-project-microservice-feed](https://github.com/waqasnoor/cloundnd-project-microservice-feed)
- reversproxy [cloudnd-project-microservices-nginx](https://github.com/waqasnoor/cloudnd-project-microservices-nginx)
- frontend [cloudnd-project-microservices-frontend](https://github.com/waqasnoor/cloudnd-project-microservices-frontend)

## Screenshots

### Dockerhub

![Dockerhub screenshot](/screenshots/dockerhub.png)

### TravisCI

![Travis CI User API](/screenshots/travisci_user.png)

![Travis CI Feed API](/screenshots/travisci_feed.png)

![Travis CI Reverse Proxy](/screenshots/travisci_nginx.png)

![Travis CI Frontend](/screenshots/travisci_frontend.png)

### Kubernetes

![Get Pods](/screenshots/getPods.png)

![Describe Services](/screenshots/describeServices.png)

![Describe HPA](/screenshots/describeHPA.png)

![Logs](/screenshots/logs.png)

## Production Link

Frontend is deployed at [http://ec2-18-222-153-42.us-east-2.compute.amazonaws.com:30000](http://ec2-18-222-153-42.us-east-2.compute.amazonaws.com:30000)
ReverseProxy is exposed at [http://ec2-18-222-153-42.us-east-2.compute.amazonaws.com:30007](http://ec2-18-222-153-42.us-east-2.compute.amazonaws.com:30007)
