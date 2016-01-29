[![](https://badge.imagelayers.io/unws/gh-pages:latest.svg)](https://imagelayers.io/?images=unws/gh-pages:latest 'Get your own badge on imagelayers.io')
# Jekyll docker
This Docker image can be used for Jekyll build which needs to be compatible with GitHub pages (gh-pages). This is a one-shot way to generate the site local and test if you like Docker :)

## HowTo
 - git clone https://github.com/UNwS/jekyll-docker or wget -o build -c https://raw.githubusercontent.com/UNwS/jekyll-docker/master/build
 - ./build -r {your jekyll github repo}
 - console show the url to open ->

## Custom
 - Add a script "build" in repo with specific Jekyll commands - build will be run instead of standard Jekyll command
   - [optional] use build -r -l {no} -p {port no} : -r can be used to seprate running and other operations -l accept the no of pages -p for the port
 - Options
   - Generate only specific number of posts -l default: all
   - dockerimage -t {latest:bleeding} default: latest
   - port -p default: 4000
   - help -h

## Prerequisite
 - [Install docker](https://docs.docker.com/engine/installation/)
 - [Install docker-compose](https://docs.docker.com/compose/install/)

## Problem?
File bug at [GitHub new issue](https://github.com/UNwS/jekyll-docker/issues/new)

