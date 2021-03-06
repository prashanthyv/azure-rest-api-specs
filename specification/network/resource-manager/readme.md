# Network

> see https://aka.ms/autorest

This is the AutoRest configuration file for Network.



---
## Getting Started
To build the SDK for Network, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration



### Basic Information
These are the global settings for the Network API.

``` yaml
title: NetworkManagementClient
description: Network Client
openapi-type: arm
tag: package-2018-02
```

### Tag: package-2018-02

These settings apply only when `--tag=package-2018-02` is specified on the command line.

``` yaml $(tag) == 'package-2018-02'

input-file:
- Microsoft.Network/stable/2018-02-01/applicationGateway.json
- Microsoft.Network/stable/2018-02-01/applicationSecurityGroup.json
- Microsoft.Network/stable/2018-02-01/checkDnsAvailability.json
- Microsoft.Network/stable/2018-02-01/ddosProtectionPlan.json
- Microsoft.Network/stable/2018-02-01/endpointService.json
- Microsoft.Network/stable/2018-02-01/expressRouteCircuit.json
- Microsoft.Network/stable/2018-02-01/expressRouteCrossConnection.json
- Microsoft.Network/stable/2018-02-01/loadBalancer.json
- Microsoft.Network/stable/2018-02-01/network.json
- Microsoft.Network/stable/2018-02-01/networkInterface.json
- Microsoft.Network/stable/2018-02-01/networkSecurityGroup.json
- Microsoft.Network/stable/2018-02-01/networkWatcher.json
- Microsoft.Network/stable/2018-02-01/operation.json
- Microsoft.Network/stable/2018-02-01/publicIpAddress.json
- Microsoft.Network/stable/2018-02-01/routeFilter.json
- Microsoft.Network/stable/2018-02-01/routeTable.json
- Microsoft.Network/stable/2018-02-01/serviceCommunity.json
- Microsoft.Network/stable/2018-02-01/usage.json
- Microsoft.Network/stable/2018-02-01/virtualNetwork.json
- Microsoft.Network/stable/2018-02-01/virtualNetworkGateway.json
- Microsoft.Network/stable/2018-02-01/vmssNetworkInterface.json
- Microsoft.Network/stable/2018-02-01/vmssPublicIpAddress.json
```

### Tag: package-2018-01

These settings apply only when `--tag=package-2018-01` is specified on the command line.

``` yaml $(tag) == 'package-2018-01'
input-file:
- Microsoft.Network/stable/2018-01-01/applicationGateway.json
- Microsoft.Network/stable/2018-01-01/applicationSecurityGroup.json
- Microsoft.Network/stable/2018-01-01/checkDnsAvailability.json
- Microsoft.Network/stable/2018-01-01/endpointService.json
- Microsoft.Network/stable/2018-01-01/expressRouteCircuit.json
- Microsoft.Network/stable/2018-01-01/loadBalancer.json
- Microsoft.Network/stable/2018-01-01/network.json
- Microsoft.Network/stable/2018-01-01/networkInterface.json
- Microsoft.Network/stable/2018-01-01/networkSecurityGroup.json
- Microsoft.Network/stable/2018-01-01/networkWatcher.json
- Microsoft.Network/stable/2018-01-01/operation.json
- Microsoft.Network/stable/2018-01-01/publicIpAddress.json
- Microsoft.Network/stable/2018-01-01/routeFilter.json
- Microsoft.Network/stable/2018-01-01/routeTable.json
- Microsoft.Network/stable/2018-01-01/serviceCommunity.json
- Microsoft.Network/stable/2018-01-01/usage.json
- Microsoft.Network/stable/2018-01-01/virtualNetwork.json
- Microsoft.Network/stable/2018-01-01/virtualNetworkGateway.json
- Microsoft.Network/stable/2018-01-01/vmssNetworkInterface.json
- Microsoft.Network/stable/2018-01-01/vmssPublicIpAddress.json
```

### Tag: package-2017-11

These settings apply only when `--tag=package-2017-11` is specified on the command line.

``` yaml $(tag) == 'package-2017-11'
input-file:
- Microsoft.Network/stable/2017-11-01/applicationGateway.json
- Microsoft.Network/stable/2017-11-01/applicationSecurityGroup.json
- Microsoft.Network/stable/2017-11-01/checkDnsAvailability.json
- Microsoft.Network/stable/2017-11-01/endpointService.json
- Microsoft.Network/stable/2017-11-01/expressRouteCircuit.json
- Microsoft.Network/stable/2017-11-01/loadBalancer.json
- Microsoft.Network/stable/2017-11-01/network.json
- Microsoft.Network/stable/2017-11-01/networkInterface.json
- Microsoft.Network/stable/2017-11-01/networkSecurityGroup.json
- Microsoft.Network/stable/2017-11-01/networkWatcher.json
- Microsoft.Network/stable/2017-11-01/operation.json
- Microsoft.Network/stable/2017-11-01/publicIpAddress.json
- Microsoft.Network/stable/2017-11-01/routeFilter.json
- Microsoft.Network/stable/2017-11-01/routeTable.json
- Microsoft.Network/stable/2017-11-01/serviceCommunity.json
- Microsoft.Network/stable/2017-11-01/usage.json
- Microsoft.Network/stable/2017-11-01/virtualNetwork.json
- Microsoft.Network/stable/2017-11-01/virtualNetworkGateway.json
- Microsoft.Network/stable/2017-11-01/vmssNetworkInterface.json
- Microsoft.Network/stable/2017-11-01/vmssPublicIpAddress.json
```

### Tag: package-2017-10

These settings apply only when `--tag=package-2017-10` is specified on the command line.

``` yaml $(tag) == 'package-2017-10'
input-file:
- Microsoft.Network/stable/2017-10-01/applicationGateway.json
- Microsoft.Network/stable/2017-10-01/applicationSecurityGroup.json
- Microsoft.Network/stable/2017-10-01/checkDnsAvailability.json
- Microsoft.Network/stable/2017-10-01/endpointService.json
- Microsoft.Network/stable/2017-10-01/expressRouteCircuit.json
- Microsoft.Network/stable/2017-10-01/loadBalancer.json
- Microsoft.Network/stable/2017-10-01/network.json
- Microsoft.Network/stable/2017-10-01/networkInterface.json
- Microsoft.Network/stable/2017-10-01/networkSecurityGroup.json
- Microsoft.Network/stable/2017-10-01/networkWatcher.json
- Microsoft.Network/stable/2017-10-01/operation.json
- Microsoft.Network/stable/2017-10-01/publicIpAddress.json
- Microsoft.Network/stable/2017-10-01/routeFilter.json
- Microsoft.Network/stable/2017-10-01/routeTable.json
- Microsoft.Network/stable/2017-10-01/serviceCommunity.json
- Microsoft.Network/stable/2017-10-01/usage.json
- Microsoft.Network/stable/2017-10-01/virtualNetwork.json
- Microsoft.Network/stable/2017-10-01/virtualNetworkGateway.json
- Microsoft.Network/stable/2017-10-01/vmssNetworkInterface.json
- Microsoft.Network/stable/2017-10-01/vmssPublicIpAddress.json
```

### Tag: package-2017-09

These settings apply only when `--tag=package-2017-09` is specified on the command line.

``` yaml $(tag) == 'package-2017-09'
input-file:
- Microsoft.Network/stable/2017-09-01/applicationGateway.json
- Microsoft.Network/stable/2017-09-01/applicationSecurityGroup.json
- Microsoft.Network/stable/2017-09-01/checkDnsAvailability.json
- Microsoft.Network/stable/2017-09-01/endpointService.json
- Microsoft.Network/stable/2017-09-01/expressRouteCircuit.json
- Microsoft.Network/stable/2017-09-01/loadBalancer.json
- Microsoft.Network/stable/2017-09-01/network.json
- Microsoft.Network/stable/2017-09-01/networkInterface.json
- Microsoft.Network/stable/2017-09-01/networkSecurityGroup.json
- Microsoft.Network/stable/2017-09-01/networkWatcher.json
- Microsoft.Network/stable/2017-09-01/operation.json
- Microsoft.Network/stable/2017-09-01/publicIpAddress.json
- Microsoft.Network/stable/2017-09-01/routeFilter.json
- Microsoft.Network/stable/2017-09-01/routeTable.json
- Microsoft.Network/stable/2017-09-01/serviceCommunity.json
- Microsoft.Network/stable/2017-09-01/usage.json
- Microsoft.Network/stable/2017-09-01/virtualNetwork.json
- Microsoft.Network/stable/2017-09-01/virtualNetworkGateway.json
- Microsoft.Network/stable/2017-09-01/vmssNetworkInterface.json
- Microsoft.Network/stable/2017-09-01/vmssPublicIpAddress.json
```

### Tag: package-2017-08

These settings apply only when `--tag=package-2017-08` is specified on the command line.

``` yaml $(tag) == 'package-2017-08'
input-file:
- Microsoft.Network/stable/2017-08-01/applicationGateway.json
- Microsoft.Network/stable/2017-08-01/checkDnsAvailability.json
- Microsoft.Network/stable/2017-08-01/endpointService.json
- Microsoft.Network/stable/2017-08-01/expressRouteCircuit.json
- Microsoft.Network/stable/2017-08-01/loadBalancer.json
- Microsoft.Network/stable/2017-08-01/network.json
- Microsoft.Network/stable/2017-08-01/networkInterface.json
- Microsoft.Network/stable/2017-08-01/networkSecurityGroup.json
- Microsoft.Network/stable/2017-08-01/networkWatcher.json
- Microsoft.Network/stable/2017-08-01/publicIpAddress.json
- Microsoft.Network/stable/2017-08-01/routeFilter.json
- Microsoft.Network/stable/2017-08-01/routeTable.json
- Microsoft.Network/stable/2017-08-01/serviceCommunity.json
- Microsoft.Network/stable/2017-08-01/usage.json
- Microsoft.Network/stable/2017-08-01/virtualNetwork.json
- Microsoft.Network/stable/2017-08-01/virtualNetworkGateway.json
- Microsoft.Network/stable/2017-08-01/vmssNetworkInterface.json
- Microsoft.Network/stable/2017-08-01/vmssPublicIpAddress.json
```


### Tag: package-2017-06

These settings apply only when `--tag=package-2017-06` is specified on the command line.

``` yaml $(tag) == 'package-2017-06'
input-file:
- Microsoft.Network/stable/2017-06-01/applicationGateway.json
- Microsoft.Network/stable/2017-06-01/checkDnsAvailability.json
- Microsoft.Network/stable/2017-06-01/endpointService.json
- Microsoft.Network/stable/2017-06-01/expressRouteCircuit.json
- Microsoft.Network/stable/2017-06-01/loadBalancer.json
- Microsoft.Network/stable/2017-06-01/network.json
- Microsoft.Network/stable/2017-06-01/networkInterface.json
- Microsoft.Network/stable/2017-06-01/networkSecurityGroup.json
- Microsoft.Network/stable/2017-06-01/networkWatcher.json
- Microsoft.Network/stable/2017-06-01/publicIpAddress.json
- Microsoft.Network/stable/2017-06-01/routeFilter.json
- Microsoft.Network/stable/2017-06-01/routeTable.json
- Microsoft.Network/stable/2017-06-01/serviceCommunity.json
- Microsoft.Network/stable/2017-06-01/usage.json
- Microsoft.Network/stable/2017-06-01/virtualNetwork.json
- Microsoft.Network/stable/2017-06-01/virtualNetworkGateway.json
- Microsoft.Network/stable/2017-06-01/vmssNetworkInterface.json
- Microsoft.Network/stable/2017-06-01/vmssPublicIpAddress.json
```


### Tag: package-2017-03

These settings apply only when `--tag=package-2017-03` is specified on the command line.

``` yaml $(tag) == 'package-2017-03'
input-file:
- Microsoft.Network/stable/2017-03-01/applicationGateway.json
- Microsoft.Network/stable/2017-03-01/checkDnsAvailability.json
- Microsoft.Network/stable/2017-03-01/expressRouteCircuit.json
- Microsoft.Network/stable/2017-03-01/loadBalancer.json
- Microsoft.Network/stable/2017-03-01/network.json
- Microsoft.Network/stable/2017-03-01/networkInterface.json
- Microsoft.Network/stable/2017-03-01/networkSecurityGroup.json
- Microsoft.Network/stable/2017-03-01/networkWatcher.json
- Microsoft.Network/stable/2017-03-01/publicIpAddress.json
- Microsoft.Network/stable/2017-03-01/routeFilter.json
- Microsoft.Network/stable/2017-03-01/routeTable.json
- Microsoft.Network/stable/2017-03-01/serviceCommunity.json
- Microsoft.Network/stable/2017-03-01/usage.json
- Microsoft.Network/stable/2017-03-01/virtualNetwork.json
- Microsoft.Network/stable/2017-03-01/virtualNetworkGateway.json
- Microsoft.Network/stable/2017-03-01/vmssNetworkInterface.json
- Microsoft.Network/stable/2017-03-01/vmssPublicIpAddress.json
```

### Tag: package-2016-12

These settings apply only when `--tag=package-2016-12` is specified on the command line.

``` yaml $(tag) == 'package-2016-12'
input-file:
- Microsoft.Network/stable/2016-12-01/vmssNetworkInterface.json
- Microsoft.Network/stable/2016-12-01/applicationGateway.json
- Microsoft.Network/stable/2016-12-01/checkDnsAvailability.json
- Microsoft.Network/stable/2016-12-01/expressRouteCircuit.json
- Microsoft.Network/stable/2016-12-01/loadBalancer.json
- Microsoft.Network/stable/2016-12-01/network.json
- Microsoft.Network/stable/2016-12-01/networkInterface.json
- Microsoft.Network/stable/2016-12-01/networkSecurityGroup.json
- Microsoft.Network/stable/2016-12-01/networkWatcher.json
- Microsoft.Network/stable/2016-12-01/publicIpAddress.json
- Microsoft.Network/stable/2016-12-01/routeFilter.json
- Microsoft.Network/stable/2016-12-01/routeTable.json
- Microsoft.Network/stable/2016-12-01/serviceCommunity.json
- Microsoft.Network/stable/2016-12-01/usage.json
- Microsoft.Network/stable/2016-12-01/virtualNetwork.json
- Microsoft.Network/stable/2016-12-01/virtualNetworkGateway.json
```

### Tag: package-2016-09

These settings apply only when `--tag=package-2016-09` is specified on the command line.

``` yaml $(tag) == 'package-2016-09'
input-file:
- Microsoft.Network/stable/2016-09-01/vmssNetworkInterface.json
- Microsoft.Network/stable/2016-09-01/applicationGateway.json
- Microsoft.Network/stable/2016-09-01/checkDnsAvailability.json
- Microsoft.Network/stable/2016-09-01/expressRouteCircuit.json
- Microsoft.Network/stable/2016-09-01/loadBalancer.json
- Microsoft.Network/stable/2016-09-01/network.json
- Microsoft.Network/stable/2016-09-01/networkInterface.json
- Microsoft.Network/stable/2016-09-01/networkSecurityGroup.json
- Microsoft.Network/stable/2016-09-01/networkWatcher.json
- Microsoft.Network/stable/2016-09-01/publicIpAddress.json
- Microsoft.Network/stable/2016-09-01/routeTable.json
- Microsoft.Network/stable/2016-09-01/usage.json
- Microsoft.Network/stable/2016-09-01/virtualNetwork.json
- Microsoft.Network/stable/2016-09-01/virtualNetworkGateway.json
```

### Tag: package-2016-06

These settings apply only when `--tag=package-2016-06` is specified on the command line.

``` yaml $(tag) == 'package-2016-06'
input-file:
- Microsoft.Network/stable/2016-06-01/network.json
```

### Tag: package-2016-03

These settings apply only when `--tag=package-2016-03` is specified on the command line.

``` yaml $(tag) == 'package-2016-03'
input-file:
- Microsoft.Network/stable/2016-03-30/network.json
```

### Tag: package-2015-06split

These settings apply only when `--tag=package-2015-06split` is specified on the command line.

``` yaml $(tag) == 'package-2015-06split'
input-file:
- Microsoft.Network/stable/2015-06-15/applicationGateway.json
- Microsoft.Network/stable/2015-06-15/checkDnsAvailability.json
- Microsoft.Network/stable/2015-06-15/expressRouteCircuit.json
- Microsoft.Network/stable/2015-06-15/loadBalancer.json
- Microsoft.Network/stable/2015-06-15/network.json
- Microsoft.Network/stable/2015-06-15/networkInterface.json
- Microsoft.Network/stable/2015-06-15/networkSecurityGroup.json
- Microsoft.Network/stable/2015-06-15/publicIpAddress.json
- Microsoft.Network/stable/2015-06-15/routeTable.json
- Microsoft.Network/stable/2015-06-15/usage.json
- Microsoft.Network/stable/2015-06-15/virtualNetwork.json
- Microsoft.Network/stable/2015-06-15/virtualNetworkGateway.json
- Microsoft.Network/stable/2015-06-15/vmssNetworkInterface.json
```

### Tag: package-2015-05-preview

These settings apply only when `--tag=package-2015-05-preview` is specified on the command line.

``` yaml $(tag) == 'package-2015-05-preview'
input-file:
- Microsoft.Network/preview/2015-05-01-preview/network.json
```

---
# Code Generation


## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-python
    after_scripts:
      - python ./scripts/multiapi_init_gen.py azure-mgmt-network
  - repo: azure-libraries-for-java
  - repo: azure-sdk-for-go
  - repo: azure-sdk-for-node
```


## C#

These settings apply only when `--csharp` is specified on the command line.
Please also specify `--csharp-sdks-folder=<path to "SDKs" directory of your azure-sdk-for-net clone>`.

``` yaml $(csharp)
csharp:
  azure-arm: true
  license-header: MICROSOFT_MIT_NO_VERSION
  namespace: Microsoft.Azure.Management.Network
  output-folder: $(csharp-sdks-folder)/Network/Management.Network/Generated
  clear-output-folder: true
```


## Go

These settings apply only when `--go` is specified on the command line.

``` yaml $(go)
go:
  license-header: MICROSOFT_APACHE_NO_VERSION
  namespace: network
  clear-output-folder: true
```

### Go multi-api

``` yaml $(go) && $(multiapi)
batch:
  - tag: package-2018-02
  - tag: package-2018-01
  - tag: package-2017-11
  - tag: package-2017-10
  - tag: package-2017-09
  - tag: package-2017-08
  - tag: package-2017-06
  - tag: package-2017-03
  - tag: package-2016-12
  - tag: package-2016-09
  - tag: package-2016-06
  - tag: package-2016-03
  - tag: package-2015-06split
  - tag: package-2015-05-preview
```

### Tag: package-2018-02 and go

These settings apply only when `--tag=package-2018-02 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2018-02' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2018-02-01/network
```

## Suppression
``` yaml
directive:
  - suppress: RequiredPropertiesMissingInResourceModel
    from: networkwatcher.json
    where: $.definitions.PacketCaptureResult
    reason: Packet capture is a non tracked child resource. It has 'name' and 'id' but does not have a 'type'
  - suppress: RequiredPropertiesMissingInResourceModel
    from: networkwatcher.json
    where: $.definitions.NetworkWatcher
    reason: Network watcher has reference on resource in network.json which contain 'name, 'id' and 'type'
  - suppress: DefinitionsPropertiesNamesCamelCase
    from: networkwatcher.json
    where: $.definitions.ProtocolConfiguration.properties.HTTPConfiguration
    reason: Accidentally shipped with wrong casing – however fixing the casing is introducing a breaking change which is worse than living with the naming violation
```

### Tag: package-2018-01 and go

These settings apply only when `--tag=package-2018-01 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2018-01' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2018-01-01/network
```

### Tag: package-2017-11 and go

These settings apply only when `--tag=package-2017-11 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2017-11' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2017-11-01/network
```

### Tag: package-2017-10 and go

These settings apply only when `--tag=package-2017-10 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2017-10' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2017-10-01/network
```

### Tag: package-2017-09 and go

These settings apply only when `--tag=package-2017-09 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2017-09' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2017-09-01/network
```

### Tag: package-2017-08 and go

These settings apply only when `--tag=package-2017-08 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2017-08' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2017-08-01/network
```

### Tag: package-2017-06 and go

These settings apply only when `--tag=package-2017-06 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2017-06' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2017-06-01/network
```

### Tag: package-2017-03 and go

These settings apply only when `--tag=package-2017-03 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2017-03' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2017-03-01/network
```

### Tag: package-2016-12 and go

These settings apply only when `--tag=package-2016-12 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2016-12' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2016-12-01/network
```

### Tag: package-2016-09 and go

These settings apply only when `--tag=package-2016-09 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2016-09' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2016-09-01/network
```

### Tag: package-2016-06 and go

These settings apply only when `--tag=package-2016-06 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2016-06' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2016-06-01/network
```

### Tag: package-2016-03 and go

These settings apply only when `--tag=package-2016-03 --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2016-03' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2016-03-30/network
```

### Tag: package-2015-06split and go

These settings apply only when `--tag=package-2015-06split --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2015-06split' && $(go)
output-folder: $(go-sdk-folder)/services/network/mgmt/2015-06-15/network
```

### Tag: package-2015-05-preview and go

These settings apply only when `--tag=package-2015-05-preview --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2015-05-preview' && $(go)
output-folder: $(go-sdk-folder)/services/preview/network/mgmt/2015-05-01-preview/network
```


## Python

These settings apply only when `--python` is specified on the command line.

``` yaml $(python)
python:
  azure-arm: true
  license-header: MICROSOFT_MIT_NO_VERSION
  payload-flattening-threshold: 2
  package-name: azure-mgmt-network
  clear-output-folder: true
  no-namespace-folders: true
```

### Python multi-api

Generate all API versions currently shipped for this package

```yaml $(python) && $(multiapi)
batch:
  - tag: package-2018-02
  - tag: package-2018-01
  - tag: package-2017-11
  - tag: package-2017-10
  - tag: package-2017-09
  - tag: package-2017-08
  - tag: package-2017-06
  - tag: package-2017-03
  - tag: package-2016-12
  - tag: package-2016-09
  - tag: package-2015-06split
```

### Tag: package-2018-02 and python

These settings apply only when `--tag=package-2018-02 --python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(tag) == 'package-2018-02' && $(python)
python:
  namespace: azure.mgmt.network.v2018_02_01
  output-folder: $(python-sdks-folder)/azure-mgmt-network/azure/mgmt/network/v2018_02_01
```

### Tag: package-2018-01 and python

These settings apply only when `--tag=package-2018-01 --python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(tag) == 'package-2018-01' && $(python)
python:
  namespace: azure.mgmt.network.v2018_01_01
  output-folder: $(python-sdks-folder)/azure-mgmt-network/azure/mgmt/network/v2018_01_01
```

### Tag: package-2017-11 and python

These settings apply only when `--tag=package-2017-11 --python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(tag) == 'package-2017-11' && $(python)
python:
  namespace: azure.mgmt.network.v2017_11_01
  output-folder: $(python-sdks-folder)/azure-mgmt-network/azure/mgmt/network/v2017_11_01
```

### Tag: package-2017-10 and python

These settings apply only when `--tag=package-2017-10 --python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(tag) == 'package-2017-10' && $(python)
python:
  namespace: azure.mgmt.network.v2017_10_01
  output-folder: $(python-sdks-folder)/azure-mgmt-network/azure/mgmt/network/v2017_10_01
```

### Tag: package-2017-09 and python

These settings apply only when `--tag=package-2017-09 --python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(tag) == 'package-2017-09' && $(python)
python:
  namespace: azure.mgmt.network.v2017_09_01
  output-folder: $(python-sdks-folder)/azure-mgmt-network/azure/mgmt/network/v2017_09_01
```

### Tag: package-2017-08 and python

These settings apply only when `--tag=package-2017-08 --python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(tag) == 'package-2017-08' && $(python)
python:
  namespace: azure.mgmt.network.v2017_08_01
  output-folder: $(python-sdks-folder)/azure-mgmt-network/azure/mgmt/network/v2017_08_01
```

### Tag: package-2017-06 and python

These settings apply only when `--tag=package-2017-06 --python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(tag) == 'package-2017-06' && $(python)
python:
  namespace: azure.mgmt.network.v2017_06_01
  output-folder: $(python-sdks-folder)/azure-mgmt-network/azure/mgmt/network/v2017_06_01
```

### Tag: package-2017-03 and python

These settings apply only when `--tag=package-2017-03 --python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(tag) == 'package-2017-03' && $(python)
python:
  namespace: azure.mgmt.network.v2017_03_01
  output-folder: $(python-sdks-folder)/azure-mgmt-network/azure/mgmt/network/v2017_03_01
```

### Tag: package-2016-12 and python

These settings apply only when `--tag=package-2016-12 --python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(tag) == 'package-2016-12' && $(python)
python:
  namespace: azure.mgmt.network.v2016_12_01
  output-folder: $(python-sdks-folder)/azure-mgmt-network/azure/mgmt/network/v2016_12_01
```

### Tag: package-2016-09 and python

These settings apply only when `--tag=package-2016-09 --python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(tag) == 'package-2016-09' && $(python)
python:
  namespace: azure.mgmt.network.v2016_09_01
  output-folder: $(python-sdks-folder)/azure-mgmt-network/azure/mgmt/network/v2016_09_01
```

### Tag: package-2015-06split and python

These settings apply only when `--tag=package-2015-06split --python` is specified on the command line.
Please also specify `--python-sdks-folder=<path to the root directory of your azure-sdk-for-python clone>`.

``` yaml $(tag) == 'package-2015-06split' && $(python)
python:
  namespace: azure.mgmt.network.v2015_06_15
  output-folder: $(python-sdks-folder)/azure-mgmt-network/azure/mgmt/network/v2015_06_15
```


## Java

These settings apply only when `--java` is specified on the command line.
Please also specify `--azure-libraries-for-java-folder=<path to the root directory of your azure-libraries-for-java clone>`.

``` yaml $(java)
java:
  azure-arm: true
  fluent: true
  namespace: com.microsoft.azure.management.network
  license-header: MICROSOFT_MIT_NO_CODEGEN
  payload-flattening-threshold: 1
  output-folder: $(azure-libraries-for-java-folder)/azure-mgmt-network
```
