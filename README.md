# service-fabric-template

Deploys Service Fabric with:

* 2 Node Types
* Managed Disks
* OMS
* Unsecured cluster
* Reverse proxy enabled on `:19081`

## Setup

* Update **[parameters.json](https://github.com/jpoon/service-fabric-template/blob/master/parameters.json)** to be the values of your cluster setup.

## Usage

```
./deploy.sh -i <subscription-id> -g <resource-group-name> -n <deployment-name> -l <location>
```


