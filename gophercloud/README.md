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
Test
set t_Co=256

Test
:GoInstallBinaries
