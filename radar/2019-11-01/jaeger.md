---
title:      "Jaeger"
ring:       trial
quadrant:   platforms-and-operations
---

[Jaeger](https://www.jaegertracing.io/) is a tool for [Distributed Tracing](/platforms-and-operations/distributed-tracing/).
Developed at Uber and inspired by Dapper and OpenZipkin it grew into an [Cloud Native Computing Foundation](https://www.cncf.io/) project.

Jaeger is a great tool for troubleshooting distributed systems, such as microservice architectures.
Developers and Operation can quickly see communication between services, and what data is communicated where.
Errors in services can be traced to the originating system.
Global trace identifiers are communicated using B3 headers. Jaeger supports Zipkin, which allows easy migration von OpenZipkin & co.
