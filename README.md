# OpenTracing Contributions

## New contributions

OpenTracing needs your help to proliferate. We’ve already had contributors instrument OSS projects, build tracing systems, and work on the API. If you are interested in getting involved, please drop us a note at [the mailing list](https://groups.google.com/forum/#!forum/opentracing) or say hello on [Gitter](https://gitter.im/opentracing/public) and we will work with you to come up with a useful proposal.

### Starting guides
We have prepared for you step by step guides which should help you to start contributing:
 * [java](guide_java.md)

# Projects

Many (but not all) contributed OpenTracing instrumentation can be found under the [the OpenTracing-contrib github organization](https://github.com/opentracing-contrib).

The following are known OpenTracing-compatible projects. Create a PR for any projects that should be added.

* [C++](#c)
* [C#](#c-1)
* [Crystal](#crystal)
* [Go](#go)
* [Erlang](#erlang)
* [Java](#java)
* [JavaScript](#javascript)
* [Objective-C](#objective-c)
* [Python](#python)
* [Ruby](#ruby)
* [Swift](#swift)

## [C++](https://github.com/opentracing/opentracing-cpp)

**Tracers**
* [dd-trace-cpp](https://github.com/DataDog/dd-trace-cpp) - DataDog
* [jaeger-client-cpp](https://github.com/jaegertracing/jaeger-client-cpp) - Jaeger
* [lightstep-tracer-cpp](https://github.com/lightstep/lightstep-tracer-cpp) - LightStep

**Instrumentation**
* [cpp-grpc](https://github.com/opentracing-contrib/cpp-grpc) - gRPC
* [nginx-opentracing](https://github.com/opentracing-contrib/nginx-opentracing) - NGINX

**Other Projects**

## [C#](https://github.com/opentracing/opentracing-cshape)

**Tracers**
* [dd-trace-csharp](https://github.com/DataDog/dd-trace-csharp) - DataDog
* [jaeger-client-csharp](https://github.com/jaegertracing/jaeger-client-csharp) - Jaeger

**Instrumentation**
* [csharp-grpc](https://github.com/opentracing-contrib/csharp-grpc) - gRPC
* [csharp-netcore](https://github.com/opentracing-contrib/csharp-netcore) - .NET Core

**Other Projects**

## Crystal

**Tracers**
* [crystal-sensor](https://github.com/instana/crystal-sensor) - Instana

**Instrumentation**

**Other Projects**

## [Go](https://github.com/opentracing/opentracing-go)

**Tracers**
* [appdash](https://github.com/sourcegraph/appdash) - Appdash
* [dd-trace-go](https://github.com/DataDog/dd-trace-go) - DataDog
* [go-sensor](https://github.com/instana/go-sensor) - Instana
* [jaeger-client-go](https://github.com/jaegertracing/jaeger-client-go) - Jaeger
* [lightstep-tracer-go](https://github.com/lightstep/lightstep-tracer-go) - LightStep
* [zipkin-go-opentracing](https://github.com/openzipkin-contrib/zipkin-go-opentracing) - Zipkin

**Instrumentation**
* [go-amqp](https://github.com/opentracing-contrib/go-amqp) - AMQP
* [go-gorilla](https://github.com/opentracing-contrib/go-gorilla) - Gorilla
* [go-grpc](https://github.com/opentracing-contrib/go-grpc) - gRPC
* [go-restful](https://github.com/opentracing-contrib/go-restful) - go-restful
* [go-stdlib](https://github.com/opentracing-contrib/go-stdlib) - standard library
* [perfevents](https://github.com/opentracing-contrib/perfevents/go) - Linux perfevents

**Other Projects**
* [go-observer](https://github.com/opentracing-contrib/go-observer) - Observer API
* [go-zap](https://github.com/opentracing-contrib/go-zap) - Zap interoperability

## Erlang

**Tracers**

**Instrumentation**

**Other Projects**
* [opentracing-erlang](https://github.com/opentracing-contrib/opentracing-erlang) - Opentracing API

## [Java](https://github.com/opentracing/opentracing-java)

**Tracers**
* [incubator-skywalking](https://github.com/apache/incubator-skywalking) - SkyWalking
* [inspectIT](https://inspectit-performance.atlassian.net/wiki/spaces/DOC) - inspectIT
* [instana-java-opentracing](https://github.com/instana/instana-java-opentracing) - Instana
* [jaeger-client-java](https://github.com/jaegertracing/jaeger-client-java) - Jaeger
* [java-spring-jaeger](https://github.com/opentracing-contrib/java-spring-jaeger) - Spring starter for Jaeger
* [java-spring-zipkin](https://github.com/opentracing-contrib/java-spring-zipkin) - Spring starter for Zipkin
* [lightstep-tracer-android](https://github.com/lightstep/lightstep-tracer-android) - LightStep
* [lightstep-tracer-java](https://github.com/lightstep/lightstep-tracer-java) - LightStep
* [stagemonitor](https://github.com/stagemonitor/stagemonitor) - Stagemonitor
* [zipkin-opentracing](https://github.com/lucidsoftware/zipkin-opentracing) - Zipkin

**Instrumentation**
* [feign-opentracing](https://github.com/OpenFeign/feign-opentracing) - Feign
* [java-agent](https://github.com/opentracing-contrib/java-agent) - ByteMan-based instrumentation
* [java-akka](https://github.com/opentracing-contrib/java-akka) - Java Akka
* [java-apache-httpclient](https://github.com/opentracing-contrib/java-apache-httpclient) - Apache HttpClient
* [java-asynchttpclient](https://github.com/opentracing-contrib/java-asynchttpclient) - AsyncHttpClient (AHC)
* [java-aws-sdk](https://github.com/opentracing-contrib/java-aws-sdk) - AWS SDK
* [java-cassandra-driver](https://github.com/opentracing-contrib/java-cassandra-driver) - Cassandra driver
* [java-concurrent](https://github.com/opentracing-contrib/java-concurrent) - java.util.concurrent
* [java-ejb](https://github.com/opentracing-contrib/java-ejb) - EJB
* [java-elasticsearch-client](https://github.com/opentracing-contrib/java-elasticsearch-client) - Elasticsearch client
* [java-grpc](https://github.com/opentracing-contrib/java-grpc) - gRPC
* [java-hazelcast](https://github.com/opentracing-contrib/java-hazelcast) - Hazelcast
* [java-hprose](https://github.com/opentracing-contrib/java-hprose) - Hprose
* [java-jaxrs](https://github.com/opentracing-contrib/java-jaxrs) - JAX-RS
* [java-jdbc](https://github.com/opentracing-contrib/java-jdbc) - JDBC
* [java-jdbi](https://github.com/opentracing-contrib/java-jdbi) - JDBI
* [java-jms](https://github.com/opentracing-contrib/java-jms) - JMS
* [java-kafka-client](https://github.com/opentracing-contrib/java-kafka-client) - Kafka client
* [java-memcached-client](https://github.com/opentracing-contrib/java-memcached-client) - Memcached client
* [java-mongo-driver](https://github.com/opentracing-contrib/java-mongo-driver) - Mongo driver
* [java-neo4j-driver](https://github.com/opentracing-contrib/java-neo4j-driver) - Neo4j driver
* [java-okhttp](https://github.com/opentracing-contrib/java-okhttp) - OkHttp
* [java-p6spy](https://github.com/opentracing-contrib/java-p6spy) - P6Spy
* [java-rabbitmq-client](https://github.com/opentracing-contrib/java-rabbitmq-client) - RabbitMQ client
* [java-redis-client](https://github.com/opentracing-contrib/java-redis-client) - Redis client
* [java-rxjava](https://github.com/opentracing-contrib/java-rxjava) - RxJava
* [java-solr-client](https://github.com/opentracing-contrib/java-solr-client) - Solr client
* [java-span-reporter](https://github.com/opentracing-contrib/java-span-reporter) - Logging adapter
* [java-spring-cloud](https://github.com/opentracing-contrib/java-spring-cloud) - Spring Cloud
* [java-spring-messaging](https://github.com/opentracing-contrib/java-spring-messaging) - Spring Messaging
* [java-spring-rabbitmq](https://github.com/opentracing-contrib/java-spring-rabbitmq) - RabbitMQ
* [java-spring-web](https://github.com/opentracing-contrib/java-spring-web) - Spring
* [java-thrift](https://github.com/opentracing-contrib/java-thrift) - Thrift
* [java-vertx-web](https://github.com/opentracing-contrib/java-vertx-web) - Vert.x Web
* [java-web-servlet-filter](https://github.com/opentracing-contrib/java-web-servlet-filter) - Servlet
* [motan](https://github.com/weibocom/motan/tree/master/motan-extension/filter-extension/filter-opentracing) - Motan
* [opentracing-httpcomponents](https://github.com/lucidsoftware/opentracing-httpcomponents) - Apache HttpComponents (HttpClient, HttpAsyncClient)
* [opentracing-jdbc](https://github.com/lucidsoftware/opentracing-jdbc) - JDBC
* [opentracing-metrics](https://github.com/opentracing-contrib/java-metrics) - Micrometer and Prometheus metrics
* [opentracing-playframework](https://github.com/lucidsoftware/opentracing-playframework) - Play framework
* [perfevents](https://github.com/opentracing-contrib/perfevents/java) - Linux perfevents
* [scala-akka](https://github.com/opentracing-contrib/scala-akka) - Scala Akka
* [scala-concurrent](https://github.com/opentracing-contrib/scala-concurrent) - scala.concurrent
* [scala-finagle](https://github.com/opentracing-contrib/scala-finagle) - Finagle

**Other Projects**
* [java-api-extensions](https://github.com/opentracing-contrib/java-api-extensions) - OpenTracing API extensions
* [java-cdi](https://github.com/opentracing-contrib/java-cdi) - Java EE CDI
* [java-spring-tracer-configuration](https://github.com/opentracing-contrib/java-spring-tracer-configuration) - Spring Boot auto-configuration
* [java-tracerresolver](https://github.com/opentracing-contrib/java-tracerresolver) - Tracer resolver

## [JavaScript](https://github.com/opentracing/opentracing-javascript)

**Tracers**
* [dd-trace-js](https://github.com/DataDog/dd-trace-js) - DataDog
* [hawkular-apm-opentracing-javascript](https://github.com/hawkular/hawkular-apm-opentracing-javascript) - Hawkular
* [jaeger-client-node](https://github.com/jaegertracing/jaeger-client-node) - Jaeger
* [lightstep-tracer-javascript](https://github.com/lightstep/lightstep-tracer-javascript) - LightStep
* [nodejs-sensor](https://github.com/instana/nodejs-sensor) - Instana
* [zipkin-javascript-opentracing](https://github.com/DanielMSchmidt/zipkin-javascript-opentracing) - Zipkin

**Instrumentation**
* [dd-trace-js](https://github.com/DataDog/dd-trace-js) - Node.js and common libraries
* [javascript-express](https://github.com/opentracing-contrib/javascript-express) - Express
* [javascript-promise](https://github.com/opentracing-contrib/javascript-tracedpromise) - Promise
* [koa-opentracing](https://github.com/teambition/koa-opentracing) - Koa
* [opentracing-auto](https://github.com/RisingStack/opentracing-auto) - Node.js and common libraries

**Other Projects**

## [Objective-C](https://github.com/opentracing/opentracing-objc)

**Tracers**
* [lightstep-tracer-objc](https://github.com/lightstep/lightstep-tracer-objc) - LightStep

**Instrumentation**

**Other Projects**

## [PHP](https://github.com/opentracing/opentracing-php)

**Tracers**
* [dd-trace-php](https://github.com/DataDog/dd-trace-php) - PHP
* [instana-php-opentracing](https://github.com/instana/instana-php-opentracing) - Instana
* [lightstep-tracer-php](https://github.com/lightstep/lightstep-tracer-php) - LightStep

**Instrumentation**

**Other Projects**

## [Python](https://github.com/opentracing/opentracing-python)

**Tracers**
* [jaeger-client-python](https://github.com/jaegertracing/jaeger-client-python) - Jaeger
* [lightstep-tracer-python](https://github.com/lightstep/lightstep-tracer-python) - LightStep
* [python-sensor](https://github.com/instana/python-sensor) - Instana

**Instrumentation**
* [python-django](https://github.com/opentracing-contrib/python-django) - Django
* [python-elastisearch](https://github.com/opentracing-contrib/python-elasticsearch) - Elasticsearch client
* [python-flask](https://github.com/opentracing-contrib/python-flask) - Flask
* [python-gevent](https://github.com/opentracing-contrib/python-gevent) - gevent
* [python-grpc](https://github.com/opentracing-contrib/python-grpc) - gRPC
* [python-pyramid](https://github.com/opentracing-contrib/python-pyramid) - Pyramid
* [python-redis](https://github.com/opentracing-contrib/python-redis) - Redis client
* [python-sqlalchemy](https://github.com/opentracing-contrib/python-sqlalchemy) - SQLAlchemy
* [python-tornado](https://github.com/opentracing-contrib/python-tornado) - Tornado

**Other Projects**

## [Ruby](https://github.com/opentracing/opentracing-ruby)

**Tracers**
* [jaeger-client-ruby](https://github.com/salemove/jaeger-client-ruby) - Jaeger
* [lightstep-tracer-ruby](https://github.com/lightstep/lightstep-tracer-ruby) - LightStep
* [test-ruby-opentracing](https://github.com/salemove/test-ruby-opentracing) - In memory tracer for testing
* [zipkin-ruby-opentracing](https://github.com/salemove/zipkin-ruby-opentracing) - Zipkin

**Instrumentation**
* [ruby-activerecord-opentracing](https://github.com/salemove/ruby-activerecord-opentracing) - ActiveRecord
* [ruby-faraday-tracer](https://github.com/opentracing-contrib/ruby-faraday-tracer) - Faraday
* [ruby-rack-tracer](https://github.com/opentracing-contrib/ruby-rack-tracer) - Rack
* [ruby-sensor](https://github.com/instana/ruby-sensor) - Instana

**Other Projects**

## Swift

**Tracers**
* [lightstep-tracer-objc](https://github.com/lightstep/lightstep-tracer-objc) - LightStep

**Instrumentation**

**Other Projects**
* [opentracing-swift](https://github.com/lightstep/opentracing-swift) - Opentracing API

[Here](index.md) is a index of all known tracers and instrumentations.

# Badges

Once you add OpenTracing support for an open-source project, please include an appropriate OpenTracing badge in said project's README.md, website, or similar.

You may either use...

Badge Flavor | Markdown Snippet | Demo
---------- | ---------------- | ------------
Generic | `[![OpenTracing Badge](https://img.shields.io/badge/OpenTracing-enabled-blue.svg)](http://opentracing.io)` | [![OpenTracing Badge](https://img.shields.io/badge/OpenTracing-enabled-blue.svg)](http://opentracing.io)
OT v1.0 | `[![OpenTracing-1.0 Badge](https://img.shields.io/badge/OpenTracing--1.0-enabled-blue.svg)](http://opentracing.io)` | [![OpenTracing-1.0 Badge](https://img.shields.io/badge/OpenTracing--1.0-enabled-blue.svg)](http://opentracing.io)


### Incomplete list of third-party contributions

This is by no means an exhaustive list, but what follows is an incomplete list of third-party OpenTracing integrations.

- [GRPC](https://github.com/grpc-ecosystem/grpc-opentracing), hosted within their [grpc-ecosystem](https://github.com/grpc-ecosystem) github organization

# Conference Speaking Opportunities

We like to spread the word about OpenTracing at conferences. We're always excited to collaborate with anyone who'd like to help out. If that sounds like you, please drop us a note at [hello@opentracing.com](mailto:hello@opentracing.com). Specifically we are looking for:

1. Co-presenting opportunities around OpenTracing, including workshops like the ones we've run at Kubecon/OSCON/etc
2. Advice if you have spoken at these events or are involved with the committee
3. Suggestions for any other events we should apply to speak at:

We are particularly interested in the following events:

- OSCON
- Monitorama USA
- Signal
- Strange Loop
- Surge
- GitHub Universe
- Go To
- Velocity
- SREcon
- DockerCon
- CoreOS Fest
- Fluent
- Gluecon
- Mesoscon
- PyCon
- Kubecon / CloudNativeCon
- Developer Week
- Cloud Foundry Summit

## License

[Apache 2.0 License](./LICENSE).

