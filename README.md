[![](https://badge.imagelayers.io/absolootly/docker-jenkins:v1.0.svg)](https://imagelayers.io/?images=absolootly/docker-jenkins:v1.0 'Get your own badge on imagelayers.io')

# About

This jenkins image is pre-built with the following github plugins:

```
credentials:1.24
git:2.4.2
git-client:1.19.4
scm-api:0.2
rebuild:1.25
jobConfigHistory:2.12
plugin-usage-plugin:0.3
groovy:1.29
job-dsl:1.42
github-api:1.72
github:1.17.0
plain-credentials:1.1
cloudbees-credentials:3.3
config-file-provider:2.10.0
token-macro:1.10
parameterized-trigger:2.29
clone-workspace-scm:0.6
chucknorris:1.0
xvfb:1.1.2
ws-cleanup:0.28
ansicolor:0.4.2
junit:1.10
xunit:1.100
docker-build-publish:1.1
docker-commons:1.3
cloudbees-folder:5.1
icon-shim:2.0.2
authentication-tokens:1.1
```

## Adding/removing plugins

You can add/remove plugins by editing plugins.txt and rebuilding the image.

## Jenkins Docker Container

Usage:

```
$ docker build -t absolootly/docker-jenkins .
$ docker run -d -p=18080:8080 jenkins
```

Once Jenkins is up and running go to http://localhost:18080

### Links

- Job DSL API https://jenkinsci.github.io/job-dsl-plugin/
