# Jenkins

## Description

Extends official Jenkins image with Docker to be able run jobs inside containers.

* Based on: Official `Jenkins 2.176.1` and `Alpine 3.9`
* Included:
    - Docker

> Note: Provided images require additional configuration for development, staging and production use.

## Tags

| Tag     | Jenkins version     | Details     | Dockerfile     |
| :------------- | :------------- | :------------- | :------------- |
| [spryker/jenkins:latest](https://hub.docker.com/r/spryker/jenkins/tags) | 2.176.1 | [![](https://images.microbadger.com/badges/image/spryker/jenkins:latest.svg)](https://microbadger.com/images/spryker/jenkins:latest "Get your own image badge on microbadger.com") | [:link:](https://github.com/spryker/docker-jenkins/blob/master/2.176/Dockerfile) |
| [spryker/jenkins:2.176](https://hub.docker.com/r/spryker/jenkins/tags)  | 2.176.1 | [![](https://images.microbadger.com/badges/image/spryker/jenkins:2.176.svg)](https://microbadger.com/images/spryker/jenkins:2.176 "Get your own image badge on microbadger.com") | [:link:](https://github.com/spryker/docker-jenkins/blob/master/2.176/Dockerfile) |

## How to use

### Pull image
```bash
$ docker pull spryker/jenkins:2.176
```

### Dockerfile
```dockerfile
FROM spryker/jenkins:2.176
```

### docker-compose.yml
```yaml
jenkins:
    image: spryker/jenkins:2.176
```


## More information
* [Jenkins official images](https://github.com/jenkinsci/docker)
