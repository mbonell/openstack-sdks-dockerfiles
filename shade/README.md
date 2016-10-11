Shade
==========

This build a development environment to work with the OpenStack Python SDK: Shade http://docs.openstack.org/infra/shade/

Build
-----
```
    docker build -t mbonell/openstack-shade .
```

Or just pull it from Docker Hub
------------------------------
```
    docker pull mbonell/openstack-shade
```

Run the OpenStack Shade SDK container
----------------------------
```
    docker run -it mbonell/openstack-shade
```

Or run the container using a host directory as a data volume
----------------------------
```
    docker run -it -v <host_directory>:/root mbonell/openstack-shade
```
