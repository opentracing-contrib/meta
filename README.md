# OpenTracing Contributions

## New contributions

OpenTracing needs your help to proliferate. We’ve already had contributors instrument OSS projects, build tracing systems, and work on the API. If you are interested in getting involved, please drop us a note at [the mailing list](https://groups.google.com/forum/#!forum/opentracing) or say hello on [Gitter](https://gitter.im/opentracing/public) and we will work with you to come up with a useful proposal.

### Starting guides
We have prepared for you step by step guides which should help you to start contributing:
 * [java](guide_java.md)

## Existing contributions

Many (but not all) contributed OpenTracing instrumentation can be found under the [the OpenTracing-contrib github organization](https://github.com/opentracing-contrib).

Other contributions are included directly/implicitly in the codebase being instrumented, or sometimes in a contrib or ecosystem for said instrumented project.

The following are all on the OpenTracing instrumentation short-list:

- [ ] AWS client libs
- [ ] Elasticsearch
- [x] [express](https://github.com/opentracing-contrib/javascript-express)
- [x] [Feign](https://github.com/OpenFeign/feign-opentracing)
- [x] [Finagle](https://github.com/twitter/finagle/pull/520#issuecomment-249959538)... almost :confused: 
- [x] [Flask](https://github.com/opentracing-contrib/python-flask)
- [ ] gRPC:
  - [x] [Go](https://github.com/opentracing-contrib/go-grpc) 
  - [x] [Java](https://github.com/opentracing-contrib/java-grpc)
  - [x] [Python](https://github.com/opentracing-contrib/python-grpc)
  - [ ] Ruby
  - [ ] Objective-C
  - [ ] C++
- [ ] hprose:
    - [x] [Java](https://github.com/opentracing-contrib/java-hprose)
- [x] [JAX-RS](https://github.com/opentracing-contrib/java-jaxrs)
- [x] [motan](https://github.com/weibocom/motan/tree/master/motan-extension/filter-extension/filter-opentracing)
- [ ] MySQL / mariadb
- [x] [nginx](https://github.com/opentracing-contrib/nginx-opentracing)
- [x] [Okhttp client](https://github.com/opentracing-contrib/java-okhttp)
- [ ] React JS
- [x] [Spring Web interceptor](https://github.com/opentracing-contrib/java-spring-web)
- [x] [Java Web Servlet filter](https://github.com/opentracing-contrib/java-web-servlet-filter)

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

