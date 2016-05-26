Use repo: https://github.com/phusion/open-vagrant-boxes

Copy Vagrant file definition from README.md

Fire `vagrant up`, ssh to virtual machine with `vagrant ssh` and
play with docker.

    # run docker container
    # -t creates terminal
    # -i makes vm interactive (it goes to background by default)
    docker run -t -i ubuntu:16.04 /bin/bash

    # to se running containers
    docker ps

    # to se also history of docker containers
    docker ps -a
