# Testcontainer - Example

This Projekt should help determine if testcontainers can run successful on "this" maschine.

``` bash

# ----------------------------------------
# Podman Setup
# ----------------------------------------
# Setting Docker host to Podman: DOCKER_HOST=pmhost
# Disable RYUK Testcontainer -> TESTCONTAINERS_RYUK_DISABLED=true
#
alias pmhost="podman machine inspect --format '{{.ConnectionInfo.PodmanPipe.Path}}'"

```

