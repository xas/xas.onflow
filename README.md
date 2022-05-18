# Xas OnFlow project

This solution can auto-generate two nuget packages dedicated to the dotnet client access to the [Flow](https://onflow.org) SDK

## Xas.Flow.Api

This project use [NSwag](https://github.com/RicoSuter/NSwag) MSBuild generator to create the C# classes/interfaces/contracts defined by the [Flow OpenApi](https://github.com/onflow/flow/tree/master/openapi) definition.

The namespace used is `Xas.Flow.Api`.

## Xas.Flow.ProtoLibs

This project generate the C# classes defined by the [Flow Protobuf](https://github.com/onflow/flow/tree/master/protobuf/flow) specifications. This project ignores the `legacy` folder.

The namespace used is `Flow`.
