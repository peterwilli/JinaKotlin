# Jina Client - Kotlin Example

Example code taken from [Thingy](https://github.com/peterwilli/Thingy) showcasing how to use Jina with gRPC in Kotlin. While not an official, standalone client, it does give you a head start into using Jina's services (Executor, Flow, JCloud) directly within Kotlin with enough flexibility to apply to your own use-cases.

**The example**...

- Uses [gRPC](https://github.com/grpc/grpc-kotlin).
- Has Gradle configured to automatically generate bindings for Jina's Document and DocumentArray objects.
- Showcases Python counterparts from the Jina Docs.
- Included some code I learned along the way that makes life easier like `getClient` which parses a URL directly to Kotlin's gRPC `host` and `port` parameter.

You can get started right away by opening this project in IntelliJ or any other Gradle-compatible IDE and run the project.

From here, you can replace the placeholder URL with something of your own (a [gRPC gateway](https://docs.jina.ai/fundamentals/gateway/), for example) and expand from there.

Hope this was helpful! ❤️