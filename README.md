1. Unary means one request, server streaming means one request butmany responses, bi-directional means two way streams
2. TLS configuration, authentication mechanisms , and RBAC implementation
3. Concurrency and synchronization management
4. It provides automatic backpressure but less performant
5. By separating Protobuf-generated types, service logic, and transport layers
6. Validation, locking, and logging
7. gRpc enables efficient communication with cross-language platform
8. It has lower latency but higher complexity
9. It has higher latency because it is pull-based
10. It has smaller payload size and faster serialization
