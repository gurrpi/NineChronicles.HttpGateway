# NineChronicles.HttpGateway

![dotnet-core-version](https://img.shields.io/badge/dotnet-3.1-blue)

An application to provide HTTP API from NineChronicles RPC server.


## Quick Start

Checkout source code:
```bash
$ git clone --recurse-submodules git@github.com:planetarium/NineChronicles.HttpGateway.git
```

Build from source:
```bash
$ dotnet build
```

Running developer builds:
```bash 
$ dotnet run -- /rpcServerHost=aafd1af9c5cf111ea824802399f8ed0e-1178879563.ap-northeast-2.elb.amazonaws.com /rpcServerPort=31234
```


## About the application dependency

It imports [planetarium/NineChronicles.RPC.Shared] repository's code as git submodule 
because it must use RPC client created from code shared with NineChronicles RPC server.
 
[planetarium/NineChronicles.RPC.Shared]: https://github.com/planetarium/NineChronicles.RPC.Shared


## Docker Build

```bash
$ docker build .
```

