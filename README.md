# Docker Network Utilities Container

A lightweight docker container with a set of networking tools. This container is built off the latest alpine image and will rebuild automatically when its updated. This is designed to be an interactive debuigging container but could also be used as the base for a container requiring these utils.

The image contains:

- iproute2
- bind-tools
- curl
- openssl
- nmap (with nmap-scripts)
- tcpdump

If there are useful tools not listed here that you would like then suggestions will be taken.
