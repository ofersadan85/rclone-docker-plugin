# rclone-docker-plugin

This ansible role will install the rclone docker volume plugin

Note: you need to have the `community.docker` collection installed to use this role

## Install

    ansible-galaxy role install ofersadan85.rclone-docker-plugin

## Example Playbook

The simplest version without variables:

    - hosts: servers
      roles:
        - ofersadan85.rclone-docker-plugin

See `defaults/main.yml` for possible variables
