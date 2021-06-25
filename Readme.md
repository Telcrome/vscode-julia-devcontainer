# Minimal configuration for setting up julia with VSCode Docker development containers

1. Open the folder in VSCode
1. Use command `remote-containers.rebuildAndReopenInContainer`
1. Test if everything works by launching `main.jl` using your preferred way

## How it works

The container is based on the official example using ubuntu.
It only downloads the julia executable and puts it on path.
