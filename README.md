#GreeterRPC
This project implements gRPC on a C# server and a GO client so that they can perform efficient, contract-first communication (specifically, send greetings in this project) with each other. This project is solely for learning purpose.

##Technologies
* gRPC: A high-performance, open-source framework developed by Google.
* * Protocol Buffers (protobuf): A language-neutral, platform-neutral, extensible way of serializing structured data.

## Usage
In one terminal, navigate into the GreetRpcServer folder and run
```bash
dotnet run
```
to start the server

In another terminal, navigate to GreetRpcClient folder and run
```bash
go run *.go
```
and you should be able to see:
```bash
Greeting: Hello world
```
Or you can pass in a name paramter
```bash
go run *.go Alexander
```
and you would see:
```bash
Greeting: Hello Alexander
```
![Success Result](https://github.com/longyi1207/GreeterRPC/blob/db00cbbf5f391b494bdaf42a85b7fbde94a7248a/run%20success.jpg)


