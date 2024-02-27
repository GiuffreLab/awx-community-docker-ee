# Ansible AWX-Operator Docker Execution Environment

This is a repo to build an Ansible Execution Environment that can communicate with Docker containers using the `community.docker` collection.

This was built on `community.docker` version `3.4.9`

The compiled version of this is hosted on docker hub [Check Here](https://hub.docker.com/r/giuffrelab/awx-community-docker-ee) and can be used directly in your AWX environment.

If you wish to learn how to build Execution Environments, [Check Here](https://github.com/GiuffreLab/building-execution-environments).

# Using the new Execution Environment in AWX-Operator

**Add the new Execution Environment**

Under `Administration` and `Execution Environments`
- Select `Add`
- Fill out the `name` field
- Under Pull select `Always Pull`
- Under image put `giuffrelab/awx-community-docker-ee:tagname`
- `Save`
