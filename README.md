Dummy image for Docker
===

[![Circle CI](https://circleci.com/gh/William-Yeh/docker-dummy.svg?style=shield)](https://circleci.com/gh/William-Yeh/docker-dummy)


A dummy Docker image useful for demonstrating continuous integration/deployment workflows.

Released to public domain.  Feel free to clone or fork it.



## Docker Hub

Useful for simple automated build workflows in Docker Hub:

- **Automated Build**: from GitHub to Docker Hub (see example [here](https://registry.hub.docker.com/u/williamyeh/dummy/)).
- **Webhooks**: from Docker Hub to your RESTful server (e.g., [RequestBin](http://requestb.in)).
- **Repository Links**: triggered from specified base images.


## CircleCI

Also useful for more sophisticated CI/CD workflows, such as in CircleCI:

- **Automated Build**: from GitHub to CircleCI (see example [here](https://circleci.com/gh/William-Yeh/docker-dummy)).
- **Webhooks**: from CircleCI to your RESTful server (e.g., [RequestBin](http://requestb.in)).
- **Chatroom Integrations**: from CircleCI to specified chatroom channels (e.g., Slack, HipChat, IRC).
- **Continuous Deployments**: from CircleCI to specified staging or production servers (see [official document](https://circleci.com/docs/docker) for details).
