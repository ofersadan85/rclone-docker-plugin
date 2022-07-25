# rclone-docker-plugin

This ansible role will install the rclone docker volume plugin

Note: you need to have the `community.docker` collection installed to use this role

## Install

    ansible-galaxy role install ofersadan85.rclone_docker_plugin
    # IF dependancies are not resolved, you will also need:
    ansible-galaxy collection install community.docker
    
## Run on localhost

    ansible localhost -m include_role -a name=ofersadan85.rclone_docker_plugin --become

## Example Playbook

The simplest version without variables:

    - hosts: servers
      roles:
        - ofersadan85.rclone_docker_plugin

See `defaults/main.yml` for possible variables
