# Testcontainer - Example

This Projekt should help determine if testcontainers can run successful on "this" maschine.

``` bash

# ----------------------------------------
# Podman Setup
# ----------------------------------------
# 1) Setting up Podman for Testcontainer on Windows Mashine:
# Set the DOCKER_HOST environment variable to your Podman pipe location. 
# You'll need to replace back slashes with forward slashes and add the npipe:// scheme to the path retrieved previously:
# set DOCKER_HOST=npipe://<inspect_command_output>
#
# 2) Disable RYUK Testcontainer: TESTCONTAINERS_RYUK_DISABLED=true
#
alias pmhost="podman machine inspect --format '{{.ConnectionInfo.PodmanPipe.Path}}'"


```

