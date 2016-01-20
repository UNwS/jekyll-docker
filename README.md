# jekyll docker
This Docker image can be used for Jekyll build which needs to be compatible with GitHub pages (gh-pages). This is a one-short way to generate the site local and test, if you like docker :)

## HowTo
 1) [Install docker](https://docs.docker.com/engine/installation/)
 2) [Install docker-compose](https://docs.docker.com/compose/install/)
 3) git clone https://github.com/UNwS/jekyll-docker
 4) ./build -r <your jekyll github repo>

## Custom
 - Add a script "build" in repo with specific jekyll commands
 - build will be run insted of standard jekyll command
 - "-l" option to generate only specific number of posts

## Problem?
Contact in [![Gitter](https://badges.gitter.im/UNwS/jekyll-docker.svg)](https://gitter.im/UNwS/jekyll-docker?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
File bug at [GitHub new issue](https://github.com/UNwS/jekyll-docker/issues/new)

## More
