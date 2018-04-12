# service-fabric-template

Deploys Service Fabric with:

* 2 Node Types
* Managed Disks
* OMS (Service Fabric, Security, Agent Health Solutions)
* Insecure cluster
* Reverse proxy enabled and open to the Internet on `:19081`

## Setup

* Update [parameters.json](https://github.com/jpoon/service-fabric-template/blob/master/parameters.json) to the values you desire for your cluster. 

## Usage

```
./deploy.sh -i <subscription-id> -g <resource-group-name> -n <deployment-name> -l <location>
```


