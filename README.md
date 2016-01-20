# jekyll docker
This Docker image can be used for Jekyll build which needs to be compatible with GitHub pages (gh-pages). This is a one-short way to generate the site local and test, if you like docker :)

## HowTo
 - git clone https://github.com/UNwS/jekyll-docker or wget -o build -c https://raw.githubusercontent.com/UNwS/jekyll-docker/master/build
 - ./build -r {your jekyll github repo}
 - open [http://0.0.0.0:4000/](http://0.0.0.0:4000/)

## Custom
 - Add a script "build" in repo with specific jekyll commands - build will be run insted of standard jekyll command
   - [optional] use build -r -l {no} : -r can be used to seprate running and other operations -l accept the no of pages
 - Options
   - Generate only specific number of posts -l default: all
   - dockerimage -t {latest:bleeding} default: latest
   - help -h

## Prerequisite
 - [Install docker](https://docs.docker.com/engine/installation/)
 - [Install docker-compose](https://docs.docker.com/compose/install/)

## Problem?
File bug at [GitHub new issue](https://github.com/UNwS/jekyll-docker/issues/new)

