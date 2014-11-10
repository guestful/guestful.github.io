Guestful OSS
============

Welcome to Guestful OSS !

This is a list of technical modules we are using at Guestful. You can also use them, and of course send us some pull requests for new versions or fixes!

**Module Categories**

- [Jersey Modules](#jersey-modules)
- [JAX-RS Client and Server Modules](#jax-rs-client-and-server-modules)
- [Reservations table](#reservations)
- [JAX-RS based API Clients](#jax-rs-based-api-clients)
- [Other Modules](#other-modules)

Jersey Modules
--------------

### jersey-container ###

Jersey Container API. Discover the implementation to use from the classpath.

```
Container container = Container.create(GuestfulResourceConfig)
    .setPort(Env.PORT)
    .setMaxWorkers(Env.WORKERS)
    .setContextPath('/api')
```

\>> `>> [Go to project](module.jersey-container) << <<

### jersey-container-undertow ###

Undertow Jersey Container implementation

`>> `>> [Go to project](module.jersey-container-undertow) << <<

### jersey-container-jetty ###

Jetty Jersey Container implementation

`>> [Go to project](module.jersey-container-jetty) <<

JAX-RS Client and Server Modules
------------------------------

### jaxrs-filter-cache ###

JAX-RX Filter handling cache control in responses through a `@Cache` annotation.

`>> [Go to project](module.jaxrs-filter-cache) <<

### jaxrs-filter-charset ###

JAX-RX Filter setting charset on top of content types through a `@Charset` annotation

`>> [Go to project](module.jaxrs-filter-charset) <<

### jaxrs-filter-client-cookie ###

JAX-RX Filter for clients to keep track of cookies to re-send them on next request

`>> [Go to project](module.jaxrs-filter-client-cookie) <<

### jaxrs-filter-cookie-removal ###

JAX-RX Filter which sends a cookie removal header for matched cookies

`>> [Go to project](module.jaxrs-filter-cookie-removal) <<

### jaxrs-filter-cors ###

JAX-RS CORS Support

`>> [Go to project](module.jaxrs-filter-cors) <<

### jaxrs-filter-jsend ###

JAX-RX Filter to support a modified [Jsend](http://labs.omniti.com/labs/jsend) body wrapper

`>> [Go to project](module.jaxrs-filter-jsend) <<

### jaxrs-filter-security ###

JAX-RS Security Filters to handle Http Basic Auth, Custom Form Auth, Authz through JSR-250, Cookie Auth, Remember-Me, etc

`>> [Go to project](module.jaxrs-filter-security) <<

### jaxrs-http-patch ###

JAX-RS Filtert to support HTTP PATCH method through a `@PATCH` annotation

`>> [Go to project](module.jaxrs-http-patch) <<

### jaxrs-media-json ###

JAX-RS Provider linked to Guestful Json Serializer interface which is pluggable with Groovy, Boon or Jackson

`>> [Go to project](module.jaxrs-media-json) <<

JAX-RS based API Clients
------------------------

### mandrill-client ###

[Mandrill](https://mandrillapp.com/) Client based on JAX-RS

`>> [Go to project](module.mandrill-client) <<

### mixpanel-client ###

[Mixpanel](https://mixpanel.com/) Client based on JAX-RS

`>> [Go to project](module.mixpanel-client) <<

### nextable-client ###

[Nextable](http://home.nextable.com/) Client based on JAX-RS

`>> [Go to project](module.nextable-client) <<

### pusher-client ###

[Pusher](http://pusher.com/) Client based on JAX-RS

`>> [Go to project](module.pusher-client) <<

### twilio-client ###

[Twilio](https://www.twilio.com/) Client based on JAX-RS

`>> [Go to project](module.twilio-client) <<

### iron-mq-client ###

[Iron MQ](http://www.iron.io/mq) Client based on JAX-RS

`>> [Go to project](module.iron-mq-client) <<

### facebook-client ###

[Facebook](https://www.facebook.com/) Client based on JAX-RS

`>> [Go to project](module.facebook-client) <<

### amazon-client ###

[Amazon AWS](http://aws.amazon.com/) Client based on JAX-RS

`>> [Go to project](module.amazon-client) <<

Other Modules
-------------

### i18n ###

Guestful I18N support based on [Unicode CLDR](http://cldr.unicode.org/)

`>> [Go to project](module.i18n) <<

### java-agent ###

Java Agent Tools to expose `Instrumentation` API, memory used, etc...

`>> [Go to project](module.java-agent) <<

### jsr310-extensions ###

JSR310 Extensions: `ZonedInterval`, Groovy serialization, Kryo serialization, Mongo serializations, Groovy extensions

`>> [Go to project](module.jsr310-extensions) <<

### eventbus ###

EventBus interface backed by several providers (Guava EventBus, Redis PubSub, IronMQ, Mongo) to support in-memory events, cluster-dispatched events, Queued events and scheduled events

`>> [Go to project](module.eventbus) <<

### json-serializer ###

JSON Serializer API backed by any provider amongst Groovy, Boon, Jackson

`>> [Go to project](module.json-serializer) <<

### simple-pool ###

Simple Object Pooling library using Java Concurrent API

`>> [Go to project](module.simple-pool) <<

### logging-extensions ###

Logging extensions for Logback, SLF4j, etc.

`>> [Go to project](module.logging-extensions) <<

### text-to-asciiart ###

Text to ASCII Art

`>> [Go to project](module.text-to-asciiart) <<
