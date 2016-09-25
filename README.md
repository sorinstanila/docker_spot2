# docker_spot2
Docker instances to speed up develop&amp;testing  using spot2. 

To use the repo you clone the repo as submodule to the root of the project:

- `git submodule add  git@github.com:sorinstanila/docker_spot2.git docker`
- `cd docker`
- `docker-compose up -d`
- `git rm --cached .gitmodules docker` ( optional: will remove the folder from git about the submodule just added; please use with caution! )

To use xdebug in Phpstorm:
- create a server in PhpStorm with the root of the directory mapper to /var/www/html on the server side
- change in docker-compose.yaml `serverName=spot2` to the new name if necesary
