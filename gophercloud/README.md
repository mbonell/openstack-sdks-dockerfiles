Gophercloud
==========

This image builds a development environment to work with the OpenStack Golang SDK: Gophercloud http://gophercloud.io/

Build
-----
```
    docker build -t mbonell/openstack-gophercloud .
```

Or just pull it from Docker Hub
------------------------------
```
    docker pull mbonell/openstack-gophercloud
```

Run the OpenStack Gophercloud SDK container
----------------------------
```
    docker run -it mbonell/openstack-gophercloud
```

Or run the container using a host directory as a data volume
----------------------------
```
    docker run -it -v <host_directory>:/root/workspace mbonell/openstack-gophercloud
```

Extra configurations for the vim-go IDE
----------------------------
The container uses [vim-go](https://github.com/farazdagi/vim-go-ide) as IDE for Golang.
To make sure that all extra Go tools (godep, gocode etc) are present on the container,  run the following command from within Vim:
```
:GoInstallBinaries
```
