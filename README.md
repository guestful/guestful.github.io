Guestful OSS
============

Welcome to Guestful OSS !

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

[Go to project](https://github.com/guestful/module.jersey-container)

### jersey-container-undertow ###

Undertow Jersey Container implementation

[Go to project](https://github.com/guestful/module.jersey-container-undertow)

### jersey-container-jetty ###

Jetty Jersey Container implementation

[Go to project](https://github.com/guestful/module.jersey-container-jetty)

JAX-RS Client & Server Modules
------------------------------

### jaxrs-filter-cache ###

JAX-RX Filter handling cache control in responses through a `@Cache` annotation.

[Go to project](https://github.com/guestful/module.jaxrs-filter-cache)

### jaxrs-filter-charset ###

JAX-RX Filter setting charset on top of content types through a `@Charset` annotation

[Go to project](https://github.com/guestful/module.jaxrs-filter-charset)

### jaxrs-filter-client-cookie ###

JAX-RX Filter for clients to keep track of cookies to re-send them on next request

[Go to project](https://github.com/guestful/module.jaxrs-filter-client-cookie)

### jaxrs-filter-cookie-removal ###

JAX-RX Filter which sends a cookie removal header for matched cookies

[Go to project](https://github.com/guestful/module.jaxrs-filter-cookie-removal)

### jaxrs-filter-cors ###

JAX-RS CORS Support

[Go to project](https://github.com/guestful/module.jaxrs-filter-cors)

### jaxrs-filter-jsend ###

JAX-RX Filter to support a modified [Jsend](http://labs.omniti.com/labs/jsend) body wrapper

[Go to project](https://github.com/guestful/module.jaxrs-filter-jsend)

### jaxrs-filter-security ###

JAX-RS Security Filters to handle Http Basic Auth, Custom Form Auth, Authz through JSR-250, Cookie Auth, Remember-Me, etc

[Go to project](https://github.com/guestful/module.jaxrs-filter-security)

### jaxrs-http-patch ###

JAX-RS Filtert to support HTTP PATCH method through a `@PATCH` annotation

[Go to project](https://github.com/guestful/module.jaxrs-http-patch)

### jaxrs-media-json ###

JAX-RS Provider linked to Guestful Json Serializer interface which is pluggable with Groovy, Boon or Jackson

[Go to project](https://github.com/guestful/module.jaxrs-media-json)

JAX-RS based API Clients
------------------------

### mandrill-client ###

[Mandrill](https://mandrillapp.com/) Client based on JAX-RS

[Go to project](https://github.com/guestful/module.mandrill-client)

### mixpanel-client ###

[Mixpanel](https://mixpanel.com/) Client based on JAX-RS

[Go to project](https://github.com/guestful/module.mixpanel-client)

### nextable-client ###

[Nextable](http://home.nextable.com/) Client based on JAX-RS

[Go to project](https://github.com/guestful/module.nextable-client)

### pusher-client ###

[Pusher](http://pusher.com/) Client based on JAX-RS

[Go to project](https://github.com/guestful/module.pusher-client)

### twilio-client ###

[Twilio](https://www.twilio.com/) Client based on JAX-RS

[Go to project](https://github.com/guestful/module.twilio-client)

### iron-mq-client ###

[Iron MQ](http://www.iron.io/mq) Client based on JAX-RS

[Go to project](https://github.com/guestful/module.iron-mq-client)

### facebook-client ###

[Facebook](https://www.facebook.com/) Client based on JAX-RS

[Go to project](https://github.com/guestful/module.facebook-client)

### amazon-client ###

[Amazon AWS](http://aws.amazon.com/) Client based on JAX-RS

[Go to project](https://github.com/guestful/module.amazon-client)

Other Modules
-------------

### i18n ###

Guestful I18N support based on Unicode CLDR

[Go to project](https://github.com/guestful/module.i18n)

### java-agent ###

Java Agent Tools to expose `Instrumentation` API, memory used, etc...

[Go to project](https://github.com/guestful/module.java-agent)

### jsr310-extensions ###

JSR310 Extensions: `ZonedInterval`, Groovy serialization, Kryo serialization, Mongo serializations, Groovy extensions

[Go to project](https://github.com/guestful/module.jsr310-extensions)

### eventbus ###

EventBus interface backed by several providers (Guava EventBus, Redis PubSub, IronMQ, Mongo) to support in-memory events, cluster-dispatched events, Queued events and scheduled events

[Go to project](https://github.com/guestful/module.eventbus)

### json-serializer ###

JSON Serializer API backed by any provider amongst Groovy, Boon, Jackson

[Go to project](https://github.com/guestful/module.json-serializer)

### simple-pool ###

Simple Object Pooling library using Java Concurrent API

[Go to project](https://github.com/guestful/module.simple-pool)

### logging-extensions ###

Logging extensions for Logback, SLF4j, etc.

[Go to project](https://github.com/guestful/module.logging-extensions)

### text-to-asciiart ###

Text to ASCII Art

[Go to project](https://github.com/guestful/module.text-to-asciiart)
