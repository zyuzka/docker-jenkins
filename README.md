# Jenkins

## Description

Extends official Jenkins image with docker in order to run jobs in containers.

* Based on: Official `Jenkins 2.60.3` and `Alpine 3.9`
* Included:
    - Docker

> Note: Provided images require additional configuration for development, staging and production use.

## Tags

| Tag     | Jenkins version     | Details     | Dockerfile     |
| :------------- | :------------- | :------------- | :------------- |
| [spryker/jenkins:latest](https://hub.docker.com/r/spryker/jenkins/tags) | 2.60.3 | [![](https://images.microbadger.com/badges/image/spryker/jenkins:latest.svg)](https://microbadger.com/images/spryker/jenkins:latest "Get your own image badge on microbadger.com") | [:link:](https://github.com/spryker/docker-jenkins/blob/master/2.60.3/Dockerfile) |
| [spryker/jenkins:2.60.3](https://hub.docker.com/r/spryker/jenkins/tags)  | 2.60.3 | [![](https://images.microbadger.com/badges/image/spryker/jenkins:2.60.3.svg)](https://microbadger.com/images/spryker/jenkins:2.60.3 "Get your own image badge on microbadger.com") | [:link:](https://github.com/spryker/docker-jenkins/blob/master/2.60.3/Dockerfile) |

## How to use

### Pull image
```bash
$ docker pull spryker/jenkins:2.60.3
```

### Dockerfile
```dockerfile
FROM spryker/jenkins:2.60.3
```

### docker-compose.yml
```yaml
jenkins:
    image: spryker/jenkins:2.60.3
```


## More information
* [Jenkins official images](https://github.com/jenkinsci/docker)
