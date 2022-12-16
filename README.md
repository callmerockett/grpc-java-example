# grpc-java-example

Projeto java de exemplo usando gRPC. Este projeto usa Maven como ferramenta de build e gerenciamento de dependências. Para executar basta fazer um:

```mvn verify```

Para levantar o servidor execute:

```mvn exec:java -Dexec.mainClass=io.grpc.examples.routeguide.RouteGuideServer```

E o cliente:

```mvn exec:java -Dexec.mainClass=io.grpc.examples.routeguide.RouteGuideClient```
